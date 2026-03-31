# 📧 Setup de Formspree para Formulario de Contacto

Guía para configurar el envío de emails desde el formulario de contacto.

---

## 🔧 Paso 1: Crear Cuenta en Formspree

1. Ve a [formspree.io](https://formspree.io)
2. Haz click en **Sign Up**
3. Registrate con email y contraseña
4. Verifica tu email

---

## 📝 Paso 2: Crear Nuevo Proyecto

1. Dashboard → **New Project**
2. Nombre: `romana-alvarez-web`
3. Click en **Create**
4. Verifica el email del proyecto

---

## 🔑 Paso 3: Obtener Form ID

1. En tu proyecto, haz click en **Settings**
2. Copia tu **Form ID** (algo como: `f/xxxxx123abc`)
3. Guarda este ID, lo necesitarás

---

## ✏️ Paso 4: Actualizar el Formulario HTML

Abre el archivo `07-contact-form.html` y busca la sección:

```javascript
// Línea aproximadamente 165
try {
  // Aquí iría la integración con tu servicio de email (Formspree, etc.)
  // Por ahora mostramos un mensaje de éxito simulado
```

**Reemplaza ese bloque por:**

```javascript
const response = await fetch('https://formspree.io/f/YOUR_FORM_ID', {
  method: 'POST',
  headers: { 'Content-Type': 'application/json' },
  body: JSON.stringify({
    name: formData.get('nombre'),
    email: formData.get('email'),
    phone: formData.get('telefono'),
    company: formData.get('empresa'),
    service: formData.get('servicio'),
    province: formData.get('provincia'),
    message: formData.get('mensaje')
  })
});

if (!response.ok) {
  throw new Error('Error al enviar');
}
```

**Cambia `YOUR_FORM_ID` por tu Form ID real:**

```javascript
// Ejemplo:
fetch('https://formspree.io/f/f/mzvwdkpq', {
  // ...
})
```

---

## 📨 Paso 5: Configurar Email de Respuesta

En Formspree Dashboard:

1. **Settings** → **Email Response**
2. Selecciona: "Send an automated reply"
3. Asunto: `Hemos recibido tu solicitud`
4. Mensaje:
```
Hola [nombre],

Gracias por contactar con Romana Álvarez.
Hemos recibido tu solicitud y nos pondremos en contacto dentro de 24 horas.

Saludos,
Equipo de Peritación
```

---

## ✅ Paso 6: Probar el Formulario

1. Ve a tu página en Elementor
2. Rellena el formulario de contacto
3. Haz click en "Enviar Solicitud"
4. Deberías recibir el email en tu bandeja

---

## 🔒 Seguridad (Importante)

Formspree proporciona:
- ✅ SPAM protection
- ✅ Email validation
- ✅ Rate limiting
- ✅ No requiere API key público

**Tu email está seguro.**

---

## 🚨 Si No Funciona

### Error 1: "CORS error"
**Solución:** Asegúrate de que estés usando `https://` en tu sitio.

### Error 2: "Invalid Form ID"
**Solución:** Verifica que copiaste el Form ID correctamente (incluye la `f/`).

### Error 3: No llega el email
**Solución:**
1. Revisa spam/carpeta de spam
2. Verifica que activaste email de respuesta
3. Comprueba el email en Formspree Dashboard

---

## 📊 Ver Estadísticas

Desde Formspree Dashboard:
- Número de envíos
- Emails correctos
- Emails fallidos
- Ver cada respuesta

---

## 💡 Alternativas a Formspree

Si prefieres otro servicio:

### Netlify Forms
- Gratis si tu sitio está en Netlify
- Integración automática

### SendGrid
- Más potente
- API profesional
- Planes pagos

### Mail Chimp
- Orientado a newsletters
- Integraciones avanzadas

---

## 🎯 Resumen

```
1. Crea cuenta en formspree.io
2. Obtén tu Form ID
3. Actualiza el código del formulario
4. Verifica que funciona
5. Recibe emails en tu bandeja
```

**¡Listo!** 🎉

---

**Última actualización:** Marzo 2026
**Compatibilidad:** Formspree API v2.0+

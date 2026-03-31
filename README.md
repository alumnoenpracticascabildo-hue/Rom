# 🎨 Widgets HTML para Romana Álvarez - Elementor Free

Colección de 7 widgets HTML autocontenidos (con CSS embebido) diseñados específicamente para funcionar con **Elementor Free**.

## 📋 Widgets Incluidos

### 1. **Hero Section** (`01-hero-section.html`)
- Presentación principal con gradiente azul
- Animaciones de entrada (slide-in)
- Estadísticas con efecto bounce
- Botones CTA primary y secondary
- **Colores**: Azul oscuro (#0d1f3c) + Azul claro (#3b82f6)

### 2. **Service Cards** (`02-service-cards.html`)
- Grid de 3 servicios (responsive)
- Hover effects con borde superior animado
- Iconos con gradientes
- Enlaces con animación de flecha
- **Animación**: Stagger en entrada + Scale en hover

### 3. **Testimonials** (`03-testimonials.html`)
- Grid de 3 testimonios
- Avatares con gradiente
- Ratings con estrellas
- Efectos de elevación en hover
- **Animación**: Slide-up progresivo

### 4. **CTA Section** (`04-cta-section.html`)
- Sección oscura con llamada a acción
- Botones animados
- Features con checkmarks
- Gradiente de fondo premium
- **Colores**: Gama azul oscura unificada

### 5. **Stats Counter** (`05-stats-counter.html`)
- Contador animado con Intersection Observer
- 4 estadísticas principales
- Gradiente de texto
- Separadores animados
- **JavaScript**: Animación de conteo en scroll

### 6. **Methodology Timeline** (`06-methodology.html`)
- Timeline vertical con 3 pasos
- Línea conectora animada
- Números con círculos
- Listas de características
- **Diseño**: Alternancia izquierda-derecha en desktop

### 7. **Contact Form** (`07-contact-form.html`)
- Formulario completo con validación
- Inputs con focus effects
- Respuesta visual (éxito/error)
- Checkbox de términos
- **JavaScript**: Manejo de formulario integrado

---

## 🚀 Cómo Implementar en Elementor Free

### Paso 1: Acceder al Editor de Elementor
1. Ve a **Página → Editar con Elementor**
2. Busca la sección donde quieres añadir el widget

### Paso 2: Insertar Bloque HTML Personalizado
1. Haz clic en el **+** para añadir elemento
2. Busca **HTML** (o "Custom HTML" si está disponible)
3. Añade el widget a la página

### Paso 3: Copiar el Código HTML
1. Abre el archivo del widget que quieras usar
2. **Copia TODO el contenido** (estilos + HTML + scripts)
3. Pégalo en el editor HTML de Elementor
4. Haz clic en **Actualizar**

### Paso 4: Ajustar si es Necesario
- Los widgets son **100% autocontenidos** con CSS embebido
- No requieren archivos CSS externos
- Funcionan inmediatamente sin configuración

---

## 🎯 Orden Recomendado en la Web

```
1. Hero Section (Portada principal)
2. Service Cards (Servicios)
3. Methodology (Proceso)
4. Stats Counter (Números)
5. Testimonials (Opiniones)
6. CTA Section (Llamada a acción)
7. Contact Form (Formulario)
```

---

## 🎨 Paleta de Colores Unificada

```
Azul Oscuro (Primario):   #0d1f3c
Azul Medio:               #1a56db
Azul Claro (Acento):      #3b82f6
Blanco:                   #ffffff
Gris claro (Fondo):       #f8f9fc
Gris oscuro (Texto):      #1f2937
Gris medio:               #6b7280
Borde:                    #e5e7eb
```

---

## 📱 Responsividad

Todos los widgets incluyen:
- ✅ Media queries para móvil (768px)
- ✅ Tipografía fluida con `clamp()`
- ✅ Grids automáticas
- ✅ Touch-friendly buttons

---

## 🎬 Animaciones Incluidas

### CSS Animations
- `slideInLeft`, `slideInRight`, `slideInUp`: Entrada de elementos
- `fadeIn`: Desvanecimiento
- `scaleIn`: Escalado
- `bounce`: Movimiento vertical repetido

### JavaScript
- **Stats Counter**: Cuenta animada al hacer scroll
- **Contact Form**: Validación y respuesta visual
- **Intersection Observer**: Activación de animaciones en viewport

---

## ⚙️ Integración con Formspree (Formulario)

Para que el formulario de contacto envíe emails reales:

1. Ve a [formspree.io](https://formspree.io)
2. Crea un proyecto y obtén tu endpoint
3. Modifica en `07-contact-form.html`:

```javascript
// Línea ~170 (dentro del try block)
const response = await fetch('https://formspree.io/f/YOUR_FORM_ID', {
  method: 'POST',
  headers: { 'Content-Type': 'application/json' },
  body: JSON.stringify({
    nombre: formData.get('nombre'),
    email: formData.get('email'),
    // ... etc
  })
});
```

---

## 📊 Tipografía

```
Títulos:     Playfair Display (serif, 700)
Cuerpo:      Inter (sans-serif, 400-600)
Acentos:     Inter Bold (600-700)
```

> **Nota**: Las fuentes se cargan automáticamente desde Google Fonts en los estilos CSS

---

## ✅ Checklist de Implementación

- [ ] Widget 1: Hero Section en portada
- [ ] Widget 2: Service Cards en sección servicios
- [ ] Widget 3: Testimonials en sección opiniones
- [ ] Widget 4: CTA Section antes del contacto
- [ ] Widget 5: Stats Counter en página apropiada
- [ ] Widget 6: Methodology en sección proceso
- [ ] Widget 7: Contact Form en página de contacto
- [ ] Configurar Formspree para emails reales
- [ ] Revisar en móvil (responsive)
- [ ] Testear animaciones en navegadores

---

## 🔧 Solución de Problemas

### Las animaciones no funcionan
- Verifica que JavaScript esté habilitado en el navegador
- Elementor Free podría bloquear algunos scripts

### Los estilos se ve diferentes
- Asegúrate de copiar **TODO** el código (style + HTML)
- Algunos temas de WordPress pueden tener conflictos CSS
- Intenta añadir `!important` si hay conflictos

### El formulario no envía
- Configura Formspree primero (ver sección anterior)
- Abre la consola (F12) para ver errores de JavaScript

---

## 📝 Notas Importantes

✅ **Ventajas de estos widgets:**
- Todo incluido (sin dependencias externas)
- Copy-paste directo en Elementor
- Funciona en Elementor Free
- Optimizado para móvil
- Animaciones suaves y profesionales

⚠️ **Limitaciones con Elementor Free:**
- No hay panel de opciones personalizable
- Para cambiar textos/colores requiere editar HTML directamente
- No hay CSS global personalizado

---

## 🎨 Personalización Rápida

Si necesitas cambiar colores, busca y reemplaza en el HTML:

```css
/* Cambiar azul principal */
--primary-blue: #1a56db;    → Tu color

/* Cambiar gris de fondo */
--bg-light: #f8f9fc;        → Tu color

/* Cambiar azul oscuro */
--primary-dark: #0d1f3c;    → Tu color
```

---

## 📞 Soporte

Para actualizaciones de widgets o problemas:
- Revisa los archivos en `/widgets/`
- Cada widget es independiente
- Puedes combinarlos en cualquier orden

---

**Versión**: 1.0
**Última actualización**: Marzo 2026
**Compatibilidad**: Elementor Free 3.0+

🚀 **¡Listo para implementar!**

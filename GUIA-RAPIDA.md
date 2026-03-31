# 🎯 Guía Rápida - Implementación en Elementor

## 5 Minutos para Tener la Web Lista

### Paso 1️⃣: Abre Elementor
Editar página → Elementor → Tu página

### Paso 2️⃣: Añade cada widget

**Para cada sección:**

1. Click en **+**
2. Busca **HTML**
3. Pega el código del widget
4. **Actualizar**

---

## 📦 Orden de Widgets (Copy-Paste)

| # | Archivo | Sección | Destino |
|---|---------|---------|---------|
| 1 | `01-hero-section.html` | Portada Principal | Primera sección |
| 2 | `02-service-cards.html` | Áreas de Actuación | Después de Hero |
| 3 | `06-methodology.html` | Nuestro Proceso | Sección servicios |
| 4 | `05-stats-counter.html` | Números Destacados | Antes de testimonios |
| 5 | `03-testimonials.html` | Opiniones Clientes | Centro página |
| 6 | `04-cta-section.html` | Llamada a Acción | Antes contacto |
| 7 | `07-contact-form.html` | Formulario Contacto | Final página |

---

## 🎨 Cambios Rápidos de Diseño

### Cambiar Colores (en cada widget)

Busca en el código:
```css
--primary-dark: #0d1f3c;      /* Azul oscuro */
--primary-blue: #1a56db;      /* Azul medio */
--light-blue: #3b82f6;        /* Azul claro */
--white: #ffffff;              /* Blanco */
--bg-light: #f8f9fc;           /* Gris fondo */
```

Reemplaza por tus colores. **Listo.**

### Cambiar Textos

Busca en el HTML:
```html
<h1>Aquí va tu título</h1>
<p>Aquí va tu texto</p>
```

Edita directamente en Elementor HTML widget.

---

## ✅ Checklist Rápido

```
□ Copié el código del widget
□ Lo pegué en HTML de Elementor
□ Hice click en Actualizar
□ Se ve bien en escritorio
□ Se ve bien en móvil
□ Cambié textos si fue necesario
```

---

## 🚀 Ejemplo Real (30 segundos)

### Copiar
```html
<!-- Abre 01-hero-section.html -->
<!-- Selecciona TODO (Ctrl+A en el editor) -->
<!-- Copia (Ctrl+C) -->
```

### Pegar en Elementor
```
1. Elementor → Editar
2. Haz click en + (nuevo elemento)
3. Busca "HTML"
4. Pega el código
5. Actualizar
```

### ¡Listo! ✅

---

## 🎬 Las Animaciones Funcionan Automáticamente

No necesitas configurar nada:
- ✅ Fade-in al cargar
- ✅ Slide-up en scroll
- ✅ Hover effects
- ✅ Contadores animados

**Todo está integrado en el CSS.**

---

## 📱 Responsive Automático

Los widgets se adaptan a:
- ✅ Desktop (1200px+)
- ✅ Tablet (768px-1200px)
- ✅ Móvil (<768px)

**Sin hacer nada extra.**

---

## 💡 Pro Tips

1. **Copia primero, personaliza después**
   - Copia tal cual, luego ajusta en Elementor

2. **Usa las imagenes placeholder**
   - Puedes cambiar URLs en el HTML

3. **El formulario necesita configuración**
   - Ver `FORMSPREE_SETUP.md` para emails reales

4. **Prueba en móvil**
   - Abre en tu teléfono para verificar responsive

---

## ⚡ Si Algo Se Ve Mal

### Opción 1: Borra y reinicia
```
1. Haz click derecho en el widget
2. Delete
3. Copia-pega de nuevo el código
```

### Opción 2: Abre la consola (F12)
- Ve a **Console**
- ¿Hay errores rojos?
- Screenshot y reporta

### Opción 3: Chequea el HTML
- ¿Copiaste TODO el código?
- ¿Incluyes `<style>` y `<script>`?

---

## 📞 Ayuda Rápida

| Problema | Solución |
|----------|----------|
| No se ven colores | Copia TODO el código (incluye `<style>`) |
| No animan | JavaScript está habilitado en navegador |
| Se ven mal en móvil | Actualiza la página (F5) |
| Formulario no envía | Configura Formspree (ver guía) |
| Textos no se ven | Aumenta tamaño de texto en Elementor |

---

## 🎯 Objetivo Final

**En 30 minutos:**
- ✅ 7 widgets implementados
- ✅ Página completa y profesional
- ✅ Animaciones incluidas
- ✅ Responsive en todos los dispositivos
- ✅ Colores unificados (blanco + azul)

**¡Vamos!** 🚀

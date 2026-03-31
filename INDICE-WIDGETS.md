# 📚 Índice Visual de Widgets

Referencia completa de los 7 widgets disponibles con características y especificaciones.

---

## 1️⃣ **Hero Section** `01-hero-section.html`

### 🎯 Propósito
Portada profesional con presentación principal del negocio

### 📸 Vista
```
┌─────────────────────────────────────────┐
│                                         │
│  Rigor de peritación al servicio       │  [Imagen]
│  de la justicia                        │  del Perito
│                                         │
│  La evidencia no miente                │
│  [Botón Solicitar] [Botón Conocer]    │
│                                         │
│  25+ años       5000+                   │
│  EXPERIENCIA    PERITACIONES           │
│                                         │
└─────────────────────────────────────────┘
```

### 🎨 Características
- ✅ Gradiente de fondo (azul oscuro)
- ✅ Animaciones de entrada (slide-in)
- ✅ Efectos hover en botones
- ✅ Badge flotante ("Experto Certificado")
- ✅ Estadísticas con efecto bounce
- ✅ Responsive 2 columnas → 1 columna

### 🔧 Secciones HTML
- `.hero-container`: Contenedor principal
- `.hero-content`: Grid 2 columnas
- `.hero-text`: Texto + botones + stats
- `.hero-image`: Imagen + badge

### 📝 Textos Editables
- Título principal (h1)
- Tagline (p.tagline)
- Descripción
- Botones (href y texto)
- Números de estadísticas

### ⏱️ Animaciones
- `slideInLeft`: Texto entra desde izquierda (0.8s)
- `slideInRight`: Imagen entra desde derecha (0.8s)
- `slideInUp`: Estadísticas suben con delay
- `bounce`: Badge sube/baja infinitamente

---

## 2️⃣ **Service Cards** `02-service-cards.html`

### 🎯 Propósito
Mostrar los 3 servicios principales con descripción

### 📸 Vista
```
Áreas de Actuación

┌──────────────┐  ┌──────────────┐  ┌──────────────┐
│    🚗        │  │    📋        │  │    🎓        │
│              │  │              │  │              │
│Peritación de │  │ Asesoría     │  │ Formación    │
│Automoción    │  │ Legal        │  │Especializada │
│              │  │              │  │              │
│Análisis... ✓ │  │Apoyo... ✓   │  │Programas...✓ │
└──────────────┘  └──────────────┘  └──────────────┘
```

### 🎨 Características
- ✅ Grid automático (3 columnas → 1 col)
- ✅ Borde superior animado en hover
- ✅ Iconos con gradiente
- ✅ Efectos de elevación (translateY)
- ✅ Sombras suaves
- ✅ Enlaces animados con flecha

### 🔧 Secciones HTML
- `.services-section`: Contenedor
- `.services-header`: Título + descripción
- `.services-grid`: Grid 3 columnas
- `.service-card`: Tarjeta individual

### 📝 Textos Editables
- Título de sección (h2)
- Descripción intro (p)
- Título de cada servicio (h3)
- Descripción de cada servicio (p)
- Enlace "Solicitar servicio" (href)

### ⏱️ Animaciones
- `slideInUp`: Cards suben con stagger (0.1s, 0.2s, 0.3s)
- `::before`: Línea superior se expande en hover
- `scale`: Iconos escalan en hover (1.1x)
- `box-shadow`: Sombra crece en hover

---

## 3️⃣ **Testimonials** `03-testimonials.html`

### 🎯 Propósito
Mostrar opiniones de clientes satisfechos

### 📸 Vista
```
Lo que Dicen Nuestros Clientes

┌──────────────────────┐  ┌──────┐  ┌──────┐
│ ⭐⭐⭐⭐⭐         │  │ ⭐⭐ │  │ ⭐⭐ │
│                      │  │      │  │      │
│ Trabajo impecable... │  │ Como │  │ Sus  │
│                      │  │perito│  │servi │
│ [Avatar] Juan Carlos │  │......│  │......│
└──────────────────────┘  └──────┘  └──────┘
  Abogado Especializado
```

### 🎨 Características
- ✅ Grid 3 columnas (responsive)
- ✅ Avatares con gradiente (iniciales)
- ✅ Ratings con estrellas
- ✅ Comillas decorativas (::before)
- ✅ Elevación en hover
- ✅ Sombras profesionales

### 🔧 Secciones HTML
- `.testimonials-section`: Contenedor
- `.testimonials-header`: Título + descripción
- `.testimonials-grid`: Grid
- `.testimonial-card`: Tarjeta individual
- `.author-avatar`: Avatar circular
- `.author-info`: Nombre + rol

### 📝 Textos Editables
- Cada testimonial (p.testimonial-text)
- Nombre (h4)
- Rol/profesión (p)
- Avatar (iniciales en div)

### ⏱️ Animaciones
- `slideInUp`: Cards suben con stagger
- `translateY`: Cards suben en hover (-12px)
- `box-shadow`: Sombra aumenta en hover

---

## 4️⃣ **CTA Section** `04-cta-section.html`

### 🎯 Propósito
Llamada a acción principal - invitar a contactar

### 📸 Vista
```
┌──────────────────────────────────────┐
│                                      │
│         PRÓXIMO PASO                 │
│                                      │
│  ¿Necesitas una Peritación          │
│  Profesional?                        │
│                                      │
│  [Botón Solicitar] [Botón Ver]      │
│                                      │
│  ✓ Respuesta 24h  ✓ Cobertura       │
│  ✓ Certificado                      │
│                                      │
└──────────────────────────────────────┘
```

### 🎨 Características
- ✅ Fondo oscuro con gradiente
- ✅ Patrones radiales de fondo
- ✅ Botones animados
- ✅ Feature list con checkmarks
- ✅ Textos en blanco
- ✅ CTA centrada

### 🔧 Secciones HTML
- `.cta-section`: Contenedor oscuro
- `.cta-content`: Contenido centrado
- `.cta-buttons`: Flex de botones
- `.cta-features`: Grid de features

### 📝 Textos Editables
- Subtítulo (cta-subtitle)
- Título (cta-title)
- Descripción (cta-description)
- Texto de botones
- Features (3 items)

### ⏱️ Animaciones
- `fadeInScale`: Contenido aparece (0.8s)
- `slideInUp`: Botones suben (0.8s + 0.2s delay)
- Transform hover: Botones bajan 3px

---

## 5️⃣ **Stats Counter** `05-stats-counter.html`

### 🎯 Propósito
Mostrar números clave con animación de conteo

### 📸 Vista
```
Números que Hablan por Sí Solos

┌────────┐  ┌────────┐  ┌────────┐  ┌────────┐
│  5000  │  │   25   │  │   98%  │  │   30   │
│───────│  │───────│  │───────│  │───────│
│PERITAC│  │ AÑOS  │  │SATISF│  │COMUNI│
│iones  │  │EXPER. │  │ACCIÓN │  │DADES │
└────────┘  └────────┘  └────────┘  └────────┘
```

### 🎨 Características
- ✅ Contador animado en scroll
- ✅ Números con gradiente de texto
- ✅ Separadores animados
- ✅ Grid 4 columnas → 1
- ✅ Intersection Observer (JS)
- ✅ Animación smooth

### 🔧 Secciones HTML
- `.stats-section`: Contenedor
- `.stats-grid`: Grid 4 items
- `.stat-card`: Tarjeta individual
- `.stat-number`: Número animado

### 📝 Textos Editables
- data-target: Número final (5000, 25, 98, 30)
- Etiqueta (stat-value)
- Descripción (stat-description)

### 🔧 JavaScript
```javascript
// Intersection Observer
// Anima conteo cuando visible
// Duración: 2000ms
// Velocidad: smooth increment
```

### ⏱️ Animaciones
- `slideInUp`: Cards aparecen con stagger
- `slideInDown`: Separadores descienden
- Contador numérico (2s al hacer scroll)

---

## 6️⃣ **Methodology** `06-methodology.html`

### 🎯 Propósito
Explicar el proceso de peritación en 3 pasos

### 📸 Vista
```
Nuestro Proceso

              1
            ────
    Inspección Inicial
    Análisis exhaustivo...
    ✓ Inspección visual
    ✓ Fotografía técnica
    ✓ Mediciones


              2
            ────
    Análisis Técnico
    Estudio profundo...


              3
            ────
    Informe Oficial
    Redacción oficial...
```

### 🎨 Características
- ✅ Timeline vertical con línea conectora
- ✅ Números en círculos (60px)
- ✅ Alternancia izquierda-derecha (desktop)
- ✅ Grid automático en móvil
- ✅ Listas de características
- ✅ Animaciones escalonadas

### 🔧 Secciones HTML
- `.methodology-timeline`: Contenedor
- `.methodology-steps`: Flex column
- `.methodology-step`: Item individual (grid)
- `.step-number`: Número (absoluto)
- `.step-content`: Contenido derecha

### 📝 Textos Editables
- Cada título (step-title)
- Cada descripción (step-description)
- Items de lista (ul.step-features li)

### ⏱️ Animaciones
- `scaleIn`: Números escalan (0.6s con delay)
- `slideInUp`: Contenido sube
- Timeline visual: Línea gradiente

---

## 7️⃣ **Contact Form** `07-contact-form.html`

### 🎯 Propósito
Formulario completo para solicitar peritación

### 📸 Vista
```
Ponte en Contacto

[Nombre Completo*]  [Email*]
[Teléfono]         [Empresa]
[Servicio*]        [Provincia*]

[Mensaje largo...]

☑ Acepto política de privacidad

[ENVIAR SOLICITUD]

✓ Solicitud enviada correctamente!
```

### 🎨 Características
- ✅ Grid 2 columnas (responsive)
- ✅ Inputs con focus effects
- ✅ Select dropdown de servicios
- ✅ Textarea para mensaje
- ✅ Checkbox de términos
- ✅ Validación HTML5
- ✅ Respuesta visual (éxito/error)
- ✅ Integración Formspree

### 🔧 Secciones HTML
- `.contact-section`: Contenedor
- `.contact-form`: Formulario
- `.form-grid`: Grid inputs
- `.form-checkbox`: Términos
- `.form-message`: Respuesta

### 📝 Campos Formulario
```
- nombre: Texto libre
- email: Email válido
- telefono: Opcional
- empresa: Texto libre
- servicio: Select (4 opciones)
- provincia: Texto libre
- mensaje: Textarea
- terminos: Checkbox (required)
```

### 🔧 JavaScript
```javascript
// Validación HTML5
// Fetch a Formspree
// Manejo de respuesta
// Mensajes de éxito/error
```

### ⏱️ Animaciones
- `fadeIn`: Header aparece
- `slideInUp`: Formulario sube
- Focus effects: Border + shadow
- Respuesta: Slide-in message

---

## 🎨 Colores Unificados

```css
:root {
  --primary-dark: #0d1f3c;    /* Navy oscuro */
  --primary-blue: #1a56db;    /* Azul profesional */
  --light-blue: #3b82f6;      /* Azul claro acento */
  --white: #ffffff;            /* Blanco puro */
  --bg-light: #f8f9fc;        /* Gris muy claro */
  --text-dark: #1f2937;       /* Gris oscuro (texto) */
  --text-light: #6b7280;      /* Gris medio */
  --border-light: #e5e7eb;    /* Borde claro */
}
```

---

## 📊 Matriz de Características

| Widget | Animaciones | Responsive | JavaScript | Formulario |
|--------|------------|-----------|-----------|-----------|
| Hero | ✅ Muchas | ✅ 2→1 col | ❌ No | ❌ No |
| Services | ✅ Hover | ✅ 3→1 col | ❌ No | ❌ No |
| Testimonials | ✅ Lift | ✅ 3→1 col | ❌ No | ❌ No |
| CTA | ✅ Fade/Slide | ✅ Stack | ❌ No | ❌ No |
| Stats | ✅ Contador | ✅ 4→1 col | ✅ Counter | ❌ No |
| Methodology | ✅ Timeline | ✅ Adapt | ❌ No | ❌ No |
| Contact | ✅ Focus | ✅ 2→1 col | ✅ Envío | ✅ Sí |

---

## 🚀 Quick Start

```bash
# 1. Copiar widget
cat widgets/01-hero-section.html

# 2. Pegar en Elementor HTML widget
# 3. Actualizar
# 4. ¡Listo!
```

---

**Última actualización**: Marzo 2026
**Total de widgets**: 7
**Líneas de código**: 2,400+
**Animaciones**: 15+
**Colores**: 8 variables unificadas

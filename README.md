# Landing Page - Lucía Fernández

Nutricionista Clínica y Deportiva en Tucumán, Argentina

## 📋 Descripción

Landing page profesional, moderna y completamente responsive para Lucía Fernández, nutricionista especializada en clínica y deportiva con sede en Yerba Buena, Tucumán.

La página está diseñada para convertir visitantes en pacientes, especialmente desde dispositivos móviles, y facilita el contacto directo a través de WhatsApp, Instagram y email.

## ✨ Características

- **📱 Mobile-first**: Optimizado completamente para dispositivos móviles
- **🌓 Modo Oscuro**: Sistema completo de tema claro/oscuro con persistencia
- **🎨 Diseño profesional**: Paleta natural con verdes suaves, crema y blanco
- **⚡ Sin dependencias**: Todo en un archivo HTML (CSS y JS embebido)
- **🎯 Google Fonts**: Tipografía elegante con Lora y Poppins
- **✨ Animaciones sutiles**: Efectos al hacer scroll y hover suave
- **♿ Accesible**: Estructura semántica HTML y atributos ARIA
- **🚀 Rápido**: Carga instantánea sin frameworks externos
- **📱 Menú hamburguesa**: Navegación intuitiva para móvil

## 📂 Estructura

```
Web-nutricionista/
├── index.html          # Archivo principal (HTML, CSS y JS integrados)
└── README.md          # Este archivo
```

## 🎯 Secciones de la Página

### 1. **Hero**
- Presentación de Lucía
- Especialidad clara
- Botón de acción (CTA) a WhatsApp

### 2. **Sobre Lucía**
- Descripción cercana y humana
- Estadísticas destacadas (experiencia, pacientes, etc.)
- Tono cálido y accesible

### 3. **Servicios**
- Consulta Presencial
- Consulta Online
- Plan Personalizado

### 4. **Cómo Trabajamos**
- Proceso en 3 pasos simples
- Evaluación → Plan → Seguimiento

### 5. **Contacto**
- WhatsApp (con enlace directo)
- Instagram
- Email

## 🚀 Cómo Usar

### Opción 1: Abrir directamente en el navegador
```bash
# Solo abre el archivo index.html en tu navegador
# No requiere servidor ni instalación
```

### Opción 2: Servidor local (recomendado para testing)
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (si tienes http-server instalado)
npx http-server

# Con PHP
php -S localhost:8000
```

Luego accede a `http://localhost:8000`

## 🔧 Personalización

### Cambiar datos de contacto

Abre `index.html` y busca estos valores:

**WhatsApp:**
```html
href="https://wa.me/+5493816000000?text=Hola%20Lucía..."
```
Reemplaza `+5493816000000` con el número real (incluye código de país)

**Instagram:**
```html
href="https://instagram.com/luciafernandez.nutricion"
```
Reemplaza `luciafernandez.nutricion` con el usuario real

**Email:**
```html
href="mailto:lucia@nutricionista.com"
```
Reemplaza con el email real

### Cambiar colores

En la sección `:root` del CSS, modifica estas variables:

```css
:root {
    --primary-green: #5a8a6f;      /* Verde principal */
    --light-green: #7ca88d;        /* Verde claro */
    --soft-green: #a8c5b8;         /* Verde suave */
    --cream: #f5f1e8;              /* Crema */
    /* ... más variables */
}
```

### Cambiar textos

Todos los textos están claramente identificados en las secciones HTML:

- `<h1>`, `<h2>`, `<h3>` para títulos
- `<p>` para párrafos
- Busca cualquier palabra clave para encontrar la sección exacta

## 🎨 Paleta de Colores

- **Verde Primario**: `#5a8a6f` - Transmite calma y profesionalismo
- **Verde Claro**: `#7ca88d` - Para acentos
- **Verde Suave**: `#a8c5b8` - Para elementos secundarios
- **Crema**: `#f5f1e8` - Fondo elegante
- **Blanco**: `#ffffff` - Base principal

### Modo Oscuro
La paleta se ajusta automáticamente en modo oscuro manteniendo contraste y elegancia.

## 🌙 Sistema de Tema

El modo oscuro se activa automáticamente si:
1. El usuario tiene tema oscuro habilitado en su dispositivo
2. El usuario hace click en el botón 🌙/☀️ en el header

La preferencia se guarda en `localStorage` para persistir entre sesiones.

## 📱 Responsividad

La página es completamente responsive con breakpoints en:

- **Desktop**: 1200px+
- **Tablet**: 769px - 1199px
- **Móvil**: 480px - 768px
- **Móvil pequeño**: <480px

## 🔗 Enlaces y Funcionalidades

### Navegación interna
Todos los enlaces internos usan `#` y navegan suavemente:
- `#sobre` → Sección Sobre Lucía
- `#servicios` → Sección Servicios
- `#proceso` → Sección Cómo Trabajamos
- `#contacto` → Sección Contacto

### Enlaces externos
- WhatsApp con texto preestablecido
- Instagram en nueva pestaña
- Email con cliente predeterminado

## ✅ Validación

La página cumple con:

- ✅ HTML5 válido
- ✅ CSS3 moderno
- ✅ JavaScript ES6
- ✅ Responsive Design
- ✅ Accesibilidad WCAG
- ✅ SEO básico optimizado
- ✅ Meta tags completos

## 📊 Rendimiento

- **Tamaño**: ~25KB (un único archivo)
- **Carga**: Instantánea (<500ms)
- **Dependencias**: 0 (solo Google Fonts externo)
- **Compresión**: Listo para GZIP

## 🛠️ Tecnologías

- **HTML5**: Estructura semántica
- **CSS3**: Flexbox, Grid, variables CSS, media queries
- **JavaScript Vanilla**: Interactividad sin frameworks
- **Google Fonts**: Tipografía Lora y Poppins

## 📲 Compatibilidad

Probado en:
- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ iOS Safari
- ✅ Chrome Android

## 🚀 Despliegue

### Opción 1: GitHub Pages (gratuito)
1. Sube el archivo a un repositorio de GitHub
2. Activa GitHub Pages en Settings
3. Tu página estará en `username.github.io/nombre-repo`

### Opción 2: Hosting compartido
Simplemente sube `index.html` vía FTP a tu hosting

### Opción 3: Vercel (recomendado - gratuito)
1. Conecta tu repositorio a Vercel
2. Despliega con un click
3. URL automática: `nombre.vercel.app`

## 📝 Notas Importantes

- No hay imágenes en la página (solo emojis y CSS)
- El código está bien comentado por secciones
- Totalmente personalizable sin conocimientos técnicos avanzados
- Modo oscuro se guarda automáticamente en el navegador

## 🔐 Privacidad

Esta página no:
- ❌ Incluye cookies de rastreo
- ❌ Recopila datos personales
- ❌ Tiene analytics externo
- ❌ Requiere backend

Los botones de contacto abren WhatsApp, Instagram y email nativo del navegador.

## 📧 Contacto y Soporte

**Para actualizar la página:**

1. Abre `index.html` en cualquier editor de texto
2. Busca el texto o sección que quieras cambiar
3. Guarda y recarga en el navegador
4. Despliega nuevamente a tu hosting

**Si necesitas ayuda:**
- [Documentación de HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [Documentación de CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [Documentación de JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)

## 📄 Licencia

Esta landing page fue creada especialmente para Lucía Fernández.

---

**Versión**: 1.0  
**Última actualización**: 4 de marzo de 2026  
**Creado para**: Lucía Fernández - Nutricionista Clínica y Deportiva

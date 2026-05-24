# Lorena Sánchez - Sitio Web de Lujo Editorial

Sitio web minimalista y elegante para salón de belleza y distribuidora cosmética, inspirado en casas de moda de lujo como Dior, Chanel y YSL.

## 📁 Estructura de Archivos

```
lorena-sanchez-github/
├── index.html          # Página principal
├── products.html       # Página de productos
├── style.css          # Estilos CSS
├── script.js          # JavaScript para interacciones
└── README.md          # Este archivo
```

## 🎨 Características de Diseño

- **Minimalismo Editorial**: Tipografía elegante (Playfair Display, Lora, Inter, Montserrat)
- **Paleta de Colores de Lujo**: Negro profundo (#0f0f0f), blanco cálido (#faf7f5), oro suave (#d4af37)
- **Animaciones Suaves**: Fade-in on scroll, hover effects elegantes, parallax effect
- **Imágenes Cinemáticas**: Fotografías de alta calidad con overlays sutiles
- **Responsive Design**: Totalmente adaptable a dispositivos móviles
- **Sin Dependencias Externas**: HTML, CSS y JavaScript puros

## 📄 Páginas Incluidas

### 1. **index.html** - Página Principal
- Hero section cinemático
- Sección editorial con tipografía grande
- Grid de servicios (Tratamientos faciales, Maquillaje, Distribución)
- Sección "Sobre nosotros" con imagen y texto
- Preview de productos
- Sección de contacto (teléfono, email, ubicación)
- Footer

### 2. **products.html** - Página de Productos
- Grid responsive de 6 productos
- Cada producto incluye:
  - Imagen
  - Categoría
  - Nombre
  - Descripción
  - Precio
  - Lista de beneficios
  - Botón "Agregar al Carrito"
- Navegación de vuelta a inicio
- Mismo navbar y footer que página principal

## 🚀 Cómo Usar

### Localmente
1. Descarga todos los archivos
2. Abre `index.html` en tu navegador
3. Los estilos y scripts se cargarán automáticamente

### En GitHub Pages
1. Crea un repositorio en GitHub llamado `lorena-sanchez` (o el nombre que prefieras)
2. Sube todos estos archivos al repositorio
3. Ve a **Settings** → **Pages**
4. Selecciona **Deploy from a branch**
5. Elige la rama `main` y carpeta `/ (root)`
6. Haz clic en **Save**
7. Tu sitio estará disponible en: `https://tu-usuario.github.io/lorena-sanchez`

## 📱 Información de Contacto (Personalizable)

Actualmente el sitio contiene:
- **Teléfono**: +34 123 456 789
- **Email**: info@lorenasanchez.com
- **Ubicación**: Melilla, España

**Para cambiar esta información**, edita los siguientes archivos:

### En `index.html` (línea ~280):
```html
<a href="tel:+34123456789" class="contact-link">+34 123 456 789</a>
<a href="mailto:info@lorenasanchez.com" class="contact-link">info@lorenasanchez.com</a>
<p class="contact-text">Melilla, España</p>
```

## 🎯 Características Principales

✅ Diseño minimalista y elegante
✅ Tipografía editorial de lujo
✅ Animaciones suaves y controladas
✅ Imágenes de alta calidad
✅ Totalmente responsive
✅ Compatible con GitHub Pages
✅ Sin frameworks ni dependencias
✅ Carga rápida
✅ SEO friendly
✅ Accesibilidad mejorada

## 🔧 Personalización

### Cambiar Colores
Edita las variables en `style.css` (líneas 6-13):
```css
:root {
    --primary: #0f0f0f;           /* Negro profundo */
    --primary-light: #faf7f5;     /* Blanco cálido */
    --accent: #d4af37;            /* Oro suave */
    /* ... más variables */
}
```

### Cambiar Fuentes
Las fuentes se cargan desde Google Fonts en `index.html` y `products.html`. Para cambiar, modifica el link en la sección `<head>`.

### Agregar/Editar Productos
En `products.html`, duplica un bloque de producto y modifica:
- Imagen (atributo `style="background-image: url(...)"`)
- Categoría
- Nombre
- Descripción
- Precio
- Beneficios

## 📊 Navegación

- **Navbar**: Fijo en la parte superior, se vuelve translúcido al hacer scroll
- **Enlaces internos**: Todos los links dentro del sitio usan scroll suave
- **Página de productos**: Accesible desde el navbar o desde la sección de productos en la página principal

## 🌐 Compatibilidad

- ✅ Chrome/Edge (últimas versiones)
- ✅ Firefox (últimas versiones)
- ✅ Safari (últimas versiones)
- ✅ Dispositivos móviles (iOS, Android)
- ✅ Tablets

## 📝 Notas Importantes

1. **Las imágenes** están alojadas en un CDN externo. Si quieres usar imágenes locales, reemplaza las URLs en los atributos `style="background-image: url(...)"`.

2. **El formulario de contacto** no está implementado. Los botones de contacto actualmente abren el cliente de email/teléfono del usuario.

3. **Los botones "Agregar al Carrito"** son placeholders. Para implementar carrito real, necesitarías backend o una solución como Shopify.

4. **Scroll suave**: Funciona en navegadores modernos. Para navegadores antiguos, el scroll será instantáneo.

## 🎓 Créditos

- Diseño inspirado en casas de moda de lujo (Dior, Chanel, YSL)
- Tipografía: Google Fonts
- Imágenes: Generadas con IA
- Desarrollo: HTML5, CSS3, JavaScript vanilla

## 📄 Licencia

Este proyecto es de uso libre para Lorena Sánchez. Siéntete libre de modificarlo según tus necesidades.

---

**¿Preguntas o problemas?** Revisa los archivos HTML y CSS para entender la estructura y hacer personalizaciones.

¡Disfruta tu sitio web de lujo! ✨

# Presentación: Análisis del Rol Directivo Escolar en Chile
## Conversatorio de Validación Cualitativa - Universidad de Concepción

---

## 📋 CAMBIOS REALIZADOS EN LA DIAPOSITIVA 10

### ✨ Mejoras Implementadas:

#### 1. **Imagen de Fondo en Blanco y Negro**
- Campanil de la Universidad de Concepción como imagen de fondo
- Aplicado filtro `grayscale(100%)` para efecto en blanco y negro
- Brillo ajustado para mejor legibilidad del texto

#### 2. **Efecto de Radiación con MagicRings**
- Componente Three.js personalizado que crea anillos radiantes
- Animación continua con colores púrpura (`#A855F7`) e índigo (`#6366F1`)
- 6 anillos concéntricos con rotación y pulsación
- Opacity variable para efecto de desvanecimiento progresivo

#### 3. **Posicionamiento del Logo y Código del Proyecto**
- Logo de la Facultad de Educación en la esquina superior izquierda (52px de altura)
- Código del proyecto "VRIMF 2631" junto al logo
- Estilos con sombra para mejor contraste en fondo oscuro

#### 4. **Tarjeta de Cita con Glasmorphism**
- Frase centrada sobre los anillos radiantes
- Fondo semi-transparente con blur (glasmorphism)
- Bordes y sombras sutiles para profundidad
- Tipografía en serif (Georgia) para énfasis

---

## 📁 ARCHIVOS INCLUIDOS

### Archivos Principales:
1. **index.html** - Estructura completa de la presentación (12 diapositivas)
2. **presentation.css** - Estilos completos (1000+ líneas)
3. **presentation.js** - Lógica de navegación y control
4. **MagicRings.js** - Componente Three.js para efecto de radiación

### Archivos de Imagen Requeridos:
- `campanil_2.jpg` - Torre/campanil de la UdeC (diapositiva 10)
- `fac_educacion-color.png` - Logo de la Facultad de Educación
- `Campanil-udec.jpg` - Imagen del campanil (diapositiva 1)
- Fotos de equipo: jorge Rojas.webp, jorge_ulloa_9611844b92.webp, ely.png, jorge.jpg, nico.png

---

## 🎮 CONTROLES DE NAVEGACIÓN

### Botones:
- **◀ Anterior** - Ir a la diapositiva anterior
- **▶ Siguiente** - Ir a la siguiente diapositiva
- **Contador** - Muestra la diapositiva actual (ej: 10 / 12)
- **Vibrante/Minimalista** - Cambiar tema de diseño
- **⛶ Pantalla Completa** - Activar modo fullscreen

### Atajos de Teclado:
- **→ o Espacio** - Siguiente diapositiva
- **← Flecha Izquierda** - Diapositiva anterior
- **F** - Pantalla completa
- **1** - Tema Vibrante
- **2** - Tema Minimalista

### Soporte Táctil:
- **Deslizar a la derecha** - Diapositiva anterior
- **Deslizar a la izquierda** - Siguiente diapositiva

---

## 🎨 ESPECIFICACIONES TÉCNICAS

### Diapositiva 10 (Cierre con MagicRings)

#### MagicRings Parameters:
```javascript
{
  color: '#A855F7',           // Color púrpura principal
  colorTwo: '#6366F1',        // Color índigo secundario
  ringCount: 6,               // Número de anillos
  speed: 1,                   // Velocidad de animación
  attenuation: 10,            // Factor de atenuación
  lineThickness: 2,           // Grosor de línea
  baseRadius: 0.35,           // Radio base
  radiusStep: 0.1,            // Paso de radio entre anillos
  scaleRate: 0.1,             // Tasa de escala pulsante
  opacity: 1,                 // Opacidad base
  fadeIn: 0.7,                // Entrada de desvanecimiento
  fadeOut: 0.5,               // Salida de desvanecimiento
  followMouse: false,         // Seguir movimiento del mouse
  hoverScale: 1.2,            // Escala al pasar mouse
  parallax: 0.05              // Efecto parallax
}
```

#### Características Visuales:
- **Tamaño del Canvas**: 600px × 600px
- **Posición**: Centrado (usando transform translate)
- **Z-index**: 4 (bajo la tarjeta de cita)
- **Animación**: Continua, suave transición

#### Tarjeta de Cita:
- **Fondo**: `rgba(255, 255, 255, 0.08)` con blur
- **Borde**: `1px solid rgba(255, 255, 255, 0.15)`
- **Sombra**: `0 8px 32px rgba(0, 0, 0, 0.3)`
- **Tipografía**: 
  - Tamaño: 1.1em
  - Family: Georgia, serif
  - Color: Blanco (#ffffff)
  - Line-height: 1.8

---

## 📝 CONTENIDO DE LA DIAPOSITIVA 10

### Frase Principal (Cita 43):
```
"Yo diría que la convivencia escolar a futuro, lo que busca es 
construir un buen ciudadano. Ten por seguro, (…) que si tú tienes 
aquí un niño que es dialogante, que logra negociar sabiendo que no 
va a ganar todo y que (…) expresa su opinión sin ofender al otro. 
Lo que estamos construyendo es un buen ciudadano y la misión del 
colegio es súper linda. En el fondo, tú necesitas buenos ciudadanos 
para tener una sociedad sana. Yo creo que convivencia escolar en 
términos inmediatos es eso, buscamos generar un ambiente propicio 
para que nuestros estudiantes aprendan y a futuro enseñarle cuál 
es la forma correcta de convivir con los otros ciudadanos (…)"
```

---

## 🚀 INSTALACIÓN Y USO

### Pasos para Usar:

1. **Descargar/Copiar archivos**
   ```
   index.html
   presentation.css
   presentation.js
   MagicRings.js
   campanil_2.jpg
   fac_educacion-color.png
   (+ otras imágenes del equipo)
   ```

2. **Estructura de carpetas recomendada**
   ```
   presentacion/
   ├── index.html
   ├── presentation.css
   ├── presentation.js
   ├── MagicRings.js
   ├── campanil_2.jpg
   ├── fac_educacion-color.png
   └── [otras imágenes]
   ```

3. **Abrir en navegador**
   - Abrir `index.html` con cualquier navegador moderno
   - Chrome, Firefox, Safari recomendados
   - Requiere activar JavaScript

4. **Modo presentación**
   - Presionar **F** o hacer clic en el botón **⛶** para fullscreen
   - Usar controles de navegación o teclado

---

## 🔧 REQUISITOS TÉCNICOS

### Navegador:
- Chrome/Chromium v60+
- Firefox v60+
- Safari 12+
- Edge 18+

### Librerías Externas:
- **Three.js** v128 - Cargado desde CDN (cdnjs.cloudflare.com)
- No se requieren dependencias adicionales

### Características Requeridas:
- WebGL (para MagicRings)
- ES6+ JavaScript
- CSS Grid y Flexbox

---

## 📊 ESTRUCTURA DE DIAPOSITIVAS

1. **Portada** - Tema y propósito
2. **Equipo** - Coordinación e investigadores
3. **Propósito** - Volumen de datos (Bento layout)
4. **Dimensión 1** - Convivencia y urgencia
5. **Reflexión 1** - Preguntas sobre convivencia
6. **Dimensión 3** - Liderazgo colaborativo (Carrusel)
7. **Reflexión 2** - Preguntas sobre liderazgo
8. **Dimensión 4** - Tensión pedagógica (Prism)
9. **Reflexión 3** - Preguntas pedagógicas
10. **Dimensión 4 (Cierre)** - Convivencia y ciudadanía **[CON MAGICINGS]** ✨
11. **Reflexión Final** - Preguntas de diálogo
12. **Cierre** - Imagen y cita (MagicRings) ✨

---

## 🎯 NOTAS IMPORTANTES

### Compatibilidad de Imágenes:
- Asegúrate que `campanil_2.jpg` esté en el mismo directorio
- La imagen debe tener buena resolución (al menos 1920×1080)
- El filtro grayscale se aplica automáticamente con CSS

### Performance:
- MagicRings usa WebGL - requiere GPU
- En dispositivos sin soporte de WebGL, se mostrará un canvas vacío
- La animación es suave en navegadores modernos

### Personalización:
- Puedes editar los parámetros de MagicRings en `presentation.js`
- Modificar colores en `--color-primary` y `--color-secondary` del CSS
- Cambiar la tipografía editando `--font-titles` y `--font-body`

---

## 🐛 Solución de Problemas

### MagicRings no aparece:
- Verificar que Three.js se cargó correctamente
- Comprobar que WebGL está habilitado en el navegador
- Revisar la consola del navegador para errores

### Imágenes no se cargan:
- Verificar rutas relativas de archivos
- Asegurarse que las imágenes están en el mismo directorio
- Comprobar permisos de lectura de archivo

### Presentación se ve cortada:
- Maximizar la ventana del navegador
- Usar modo fullscreen (F)
- Comprobar resolución del monitor (1920×1080 recomendado)

---

## 📧 Contacto y Soporte

**Proyecto**: VcM VRIMF 2631
**Institución**: Universidad de Concepción
**Facultad**: Educación
**Línea de Investigación**: Análisis del Rol Directivo Escolar

---

**Última actualización**: Julio 2026
**Versión**: 2.0 (Con MagicRings)

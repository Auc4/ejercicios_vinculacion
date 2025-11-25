# Documentación Interna - Clase 5

Este documento detalla las modificaciones y adiciones realizadas en los archivos de la Clase 5. Es la primera clase que introduce la vinculación de estilos mediante CSS. Sirve como guía de referencia para tutores y alumnos.

##  Cambios Clave en la Lección

La Clase 5 se centró en la **introducción de estilos con CSS3** y la **correcta vinculación de archivos externos**. Se añadieron nuevos archivos (`styles.css` y la carpeta `imagen/`) y se modificó el HTML para enlazarlos.

##  Detalle de Modificaciones

A continuación, se presenta una lista comparativa de las adiciones y ajustes realizados en el código.

### 1. HTML (`index.html` y `resultado.html`)

| Descripción del Cambio | Propósito / Etiqueta Afectada |
| :--- | :--- |
| **[Cambio 1: Vinculación del CSS]** | Se añadió la etiqueta `<link>` en el `<head>` para enlazar el archivo `styles.css` y aplicar los estilos (Ej.: `<link rel="stylesheet" href="styles.css">`). |
| **[Cambio 2: Adición de Clases CSS]** | Se añadieron el atributo `class` a etiquetas clave (Ej.: `class="contenedor-flexible"`) para que puedan ser seleccionadas y estilizadas desde CSS. |
| **[Cambio 3: Rutas de Imágenes]** | Se modificaron los atributos `src` de las etiquetas `<img>` para apuntar correctamente a las imágenes dentro de la nueva carpeta `/imagen`. |
| **[Cambio 4: Estructura de navegación/header]** | Se ajustó la estructura HTML del encabezado para permitir un mejor manejo del estilo con Flexbox o CSS Grid. |

***

### 2. CSS (`styles.css`)

| Descripción del Cambio | Regla/Selector Afectada |
| :--- | :--- |
| **[Cambio 1: Estilos Globales (Reset)]** | Se añadieron reglas básicas para resetear o normalizar estilos (Ej.: `box-sizing: border-box;` o estilos para `body`). |
| **[Cambio 2: Estilo de Elementos base]** | Se definieron estilos iniciales para etiquetas HTML (Ej.: `a` para quitar el subrayado o `h1, h2, h3` para fuentes). |
| **[Cambio 3: Implementación de Clases HTML]** | Se crearon selectores de clase (Ej.: `.contenedor-flexible`, `.btn-trabajo`) y se les asignaron propiedades como `display: flex` o colores de fondo. |
| **[Cambio 4: Diseño de Footer/Header]** | Se definieron reglas específicas para el `<footer>` o `<header>` para lograr la maquetación deseada. |

### 📁 Archivos Adicionales

* **Nueva Carpeta:** Se añadió la carpeta `/imagen` que contiene los archivos multimedia necesarios para la visualización del sitio (Ej.: `foto_perfil.png`, `ilustracion.png`).

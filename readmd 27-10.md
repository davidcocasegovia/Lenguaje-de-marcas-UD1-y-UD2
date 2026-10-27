# Proyecto Integrador: Real Betis Balompié

* **Autor:** Tu Nombre Completo
* **Usuario de GitHub:** tu-usuario-github
* **Asignatura:** Lenguaje de Marcas y Sistemas de Gestión de Información (2026)
* **Ruta del proyecto:** `Proyecto-Integrador-LM-2026/proyecto/`

---

## 📅 Evolución del Proyecto

### 1. Sesión Anterior (Configuración y Estructura Base)
* **Estructura inicial:** Creación de la jerarquía de carpetas y configuración del repositorio en Git y GitHub.
* **Diseño web básico:** Maquetación inicial de la página de inicio (`index.html`) y de la lista de jugadores utilizando exclusivamente etiquetas HTML puras.
* **Estructura de datos (XML):** Creación del archivo `datos.xml` con los datos estructurados de cuatro jugadores históricos del Real Betis Balompié, cumpliendo con los requisitos de elementos únicos, atributos e ID.
* **Puente de datos a vista:** Planificación de la arquitectura multipágina para enlazar los registros con páginas de detalle estáticas.

### 2. UD3 · Estructura HTML y Arquitectura Multipágina (Actual)
* **Mejora de la cabecera (`head`):** Inclusión del prólogo `<!DOCTYPE html>`, codificación `UTF-8`, metadatos completos (`description`, `keywords`, `author`) y control de escala (`viewport`).
* **Organización semántica:** Uso de bloques `div` comentados, jerarquía estricta de títulos (`h1` único, seguidos de `h2` y `h3` sin saltos), uso obligatorio de párrafos (`p`), etiquetas de separación (`hr`), citas (`blockquote`), fichas técnicas formateadas (`pre`) y entidades de caracteres (`&amp;`, `&copy;`, `&ldquo;`, etc.).
* **Estilo visual:** Incorporación de imágenes de fondo y diseño estético en línea adaptado a la identidad verdiblanca del club.
* **Arquitectura de sitio completo:** Creación de un mapa del sitio y desarrollo de múltiples páginas HTML interconectadas, permitiendo navegar desde la lista general de jugadores hasta sus fichas técnicas individuales detalladas.

---

## 🗺️ Mapa del sitio

| Fichero | Title | Qué contiene |
| :--- | :--- | :--- |
| `index.html` | Inicio \| Real Betis Balompié | Portada oficial: presentación, historia, ficha técnica del club y accesos principales. |
| `jugadores.html` | Jugadores \| Real Betis Balompié | Listado general de la plantilla histórica con enlaces directos al XML y a sus fichas. |
| `joaquin.html` | Joaquín Sánchez \| Real Betis Balompié | Ficha detallada, estadísticas y características de la leyenda bética. |
| `gordillo.html` | Rafael Gordillo \| Real Betis Balompié | Ficha detallada y características del histórico lateral izquierdo. |
| `fekir.html` | Nabil Fekir \| Real Betis Balompié | Ficha técnica y estadísticas del mediapunta francés. |
| `rubencastro.html` | Rubén Castro \| Real Betis Balompié | Ficha técnica y estadísticas del máximo goleador histórico. |
| `historia.html` | Historia \| Real Betis Balompié | Hitos deportivos y fundación del club. |
| `estadio.html` | Estadio \| Real Betis Balompié | Información detallada sobre el Benito Villamarín y Heliópolis. |

---

## 🔍 UD3 · Validación W3C y Corrección de Errores

| Fichero HTML | Errores detectados en W3C | Cómo se corrigieron |
| :--- | :--- | :--- |
| `index.html` | Ninguno (0 errores) | Validación superada tras estructurar correctamente los bloques `div` y cerrar etiquetas. |
| `jugadores.html` | Ninguno (0 errores) | Verificado mediante la herramienta de subida de ficheros del validador W3C. |
| `joaquin.html` | Ninguno (0 errores) | Comprobado cierre estricto de etiquetas y sintaxis correcta de metadatos. |
| `gordillo.html` | Ninguno (0 errores) | Validado sin incidencias. |
| `fekir.html` | Ninguno (0 errores) | Validado sin incidencias. |
| `rubencastro.html` | Ninguno (0 errores) | Validado sin incidencias. |

### Qué he hecho en esta unidad
En esta tercera unidad he transformado una página web simple en un sitio web completo y profesional sobre el Real Betis Balompié. He perfeccionado la cabecera metadatos con etiquetas W3C, organizado el contenido en bloques `div` semánticamente comentados y ampliado el proyecto a una estructura multipágina funcional. Esto me ha permitido conectar el repositorio de datos XML con páginas individuales de detalle para cada jugador, asegurando la validación estricta de todo el código.

---
*Palabra del día:* [Escribe aquí la palabra dictada por la profesora]
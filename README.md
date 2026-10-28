# 🚀 Portal Web "Innova ESPE 2026"

¡Bienvenido al repositorio oficial del portal web para el evento **Innova ESPE 2026**! Este sitio fue pensado y desarrollado desde cero como un espacio informativo, moderno y completamente adaptable para mostrar los proyectos tecnológicos y emprendimientos estudiantiles.

---

## 🎯 ¿Qué vas a encontrar en este sitio?

El portal está diseñado siguiendo la filosofía **Mobile First** y cumple con todos los estándares modernos de desarrollo frontend sin utilizar frameworks pesados:

* **Estructura semántica:** Organizado de forma limpia con etiquetas nativas de HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
* **Diseño visual impecable:** Estilos personalizados mediante CSS Grid para las tarjetas de proyectos y Flexbox para la barra de navegación y distribución de elementos.
* **Sección de bienvenida:** Un banner principal de alto impacto con la información clave del evento y un acceso directo para la inscripción.
* **Proyectos destacados:** Tarjetas interactivas que detallan las iniciativas tecnológicas más innovadoras de los estudiantes.
* **Programación y contenidos:** Una tabla detallada de actividades, acompañada de listas ordenadas y no ordenadas con los pasos para participar y los beneficios.
* **Multimedia y ubicación:** Contiene un video promocional integrado y un mapa interactivo de OpenStreetMap que ubica exactamente el campus del evento.
* **Formulario de inscripción completo:** Diseñado con campos variados (textos, correos, teléfonos, selectores de carrera, botones de opción y casillas de verificación)
* **validaciones nativas de HTML5** (`required`, patrones, etc.).

## 🐳 ¿Cómo ejecutar el proyecto con Docker?

Puedes visualizar este portal web utilizando un contenedor de Nginx Alpine de dos formas diferentes:

### Opción 1: Construyendo la imagen localmente
1. Abre tu terminal en la carpeta principal del proyecto (donde se encuentra el archivo `Dockerfile`).
2. Construye la imagen localmente con el siguiente comando:
   ```bash
   docker build -t innova-espe:v1 .
   docker run -d -p 8080:80 --name app-innova innova-espe:v1


---

## 📂 Organización de Archivos

El proyecto mantiene una estructura limpia y estandarizada:

```text
APELLIDO_NOMBRE_P1/
├── Dockerfile
├── index.html
├── css/
│   └── styles.css
├── assets/
│   ├── Imagenes/
│   └── Videos/
├── evidencias/
│   ├── escritorio.png
│   └── movil.png
└── README.md
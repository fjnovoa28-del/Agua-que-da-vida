# Agua que da vida – OVA ambiental

Proyecto educativo interactivo sobre el cuidado y uso responsable del agua en Córdoba, Colombia.

## Estructura
- `index.html`: contenido y estructura del OVA.
- `css/style.css`: diseño visual adaptable a computador, tableta y celular.
- `js/app.js`: navegación, tarjetas de consejos, evaluación, puntuación y compromisos guardados en el navegador.

## Cómo probarlo
Abre `index.html` en un navegador. Se recomienda conexión a internet para cargar la fotografía de referencia y la tipografía externa. Las actividades principales funcionan localmente y no requieren backend ni claves API.

## Cómo publicarlo con GitHub Pages
1. Inicia sesión en GitHub y crea un repositorio nuevo, por ejemplo `agua-que-da-vida`.
2. Sube los archivos y carpetas de este proyecto. `index.html` debe quedar en la raíz del repositorio.
3. En el repositorio entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que termine la publicación. La dirección tendrá el formato `https://TU-USUARIO.github.io/agua-que-da-vida/`.

## Nota
El progreso de compromisos y el mejor puntaje se guardan con `localStorage` en el navegador del dispositivo. No hay servidor ni base de datos.

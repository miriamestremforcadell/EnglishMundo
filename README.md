# EnglishMundo

Aplicación web educativa para practicar inglés mediante actividades de vocabulario, comprensión y gramática.

## Estructura

- `index.html`: aplicación principal. Mantiene la lógica y las actividades originales.
- `manifest.webmanifest`: configuración para instalar la aplicación en dispositivos compatibles.
- `service-worker.js`: caché de la aplicación para permitir abrirla sin conexión después de la primera carga.
- `icons/icon.svg`: icono de la aplicación.

## Datos y privacidad

El progreso de los alumnos se guarda en el almacenamiento local (`localStorage`) del navegador y dispositivo donde se utiliza la aplicación. No se sincroniza automáticamente entre dispositivos ni navegadores. Si se borran los datos del navegador, puede perderse ese progreso; conviene conservar el mismo dispositivo y navegador.

La aplicación incluye síntesis de voz del navegador para las actividades que la utilizan.

## Uso local

Abre `index.html` en un navegador para probar la aplicación. Para comprobar la instalación PWA y el modo sin conexión, sirve la carpeta mediante un servidor local o publícala mediante un servicio HTTPS compatible.

## Publicación

El repositorio es privado. La publicación mediante GitHub Pages desde un repositorio privado requiere un plan de GitHub que admita Pages en repositorios privados. No se ha cambiado la visibilidad del repositorio.

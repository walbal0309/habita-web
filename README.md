# HABITA — Diseño y construcción

Web estática editable en HTML, CSS y JavaScript, sin instalación de dependencias.
Incluye portada, proyectos con fichas navegables, estudio, servicios, proceso y contacto.

## Ver y editar

Abre `dist/index.html` en tu navegador. También puedes abrir la carpeta en Visual Studio Code y usar tu servidor de desarrollo habitual. Los enlaces de proyectos usan fragmentos (#proyecto/casa-patio): funcionan sin configurar redirecciones en el alojamiento.

## Cambiar fotografías

Reemplaza `dist/assets/casa.webp`, `interior.webp` y `comercial.webp` por tus imágenes, manteniendo el nombre. La primera aparece también en la portada. Usa fotografías horizontales de buena calidad; se recomienda al menos 1600 px de ancho y archivos optimizados menores de 700 KB. Si usas JPG, cambia las rutas en `dist/contenido.js` y la imagen de portada en `dist/index.html`.

## Cambiar proyectos

Edita `dist/contenido.js`. Cada proyecto contiene título, especialidad, imagen, texto alternativo, resumen, concepto, materialidad y tres decisiones de diseño. Puedes añadir proyectos copiando un objeto y dándole un `id` único sin espacios. Los ejemplos son conceptos ficticios ilustrativos, no obras de HABITA.

Al incorporar un proyecto real, cambia sus textos e imagen y establece `demo: false`. Actualiza también la nota de la sección de proyectos, el texto inferior de portada y el aviso del pie en `dist/index.html` según el material real que finalmente muestres. Nunca atribuyas una imagen de ejemplo a una obra ejecutada.

## Activar WhatsApp

En `dist/contenido.js`, escribe tu número internacional en `whatsapp`, solo con dígitos, sin + ni espacios. El formulario abrirá WhatsApp con un mensaje preparado; el visitante revisa y envía el mensaje. Con el valor vacío, descarga un archivo de texto y no transmite ni guarda información.

## Otros textos y estilo

- `dist/index.html`: nombre, presentación, servicios, proceso y pie.
- `dist/styles.css`: colores al inicio, tipografía, composición y adaptación a pantallas.
- `dist/app.js`: navegación, fichas de proyecto, menú, acordeones y formulario.

No hay cuentas, estadísticas, cookies de seguimiento ni servidor de formularios.

## Llevarlo a GitHub

Repositorio: https://github.com/walbal0309/habita-web . El contenido de la web está en `dist/`.
En Settings → Pages selecciona GitHub Actions como origen. El workflow incluido publica `dist/` al actualizar `main`; también se puede ejecutar desde Actions. Habilitar Pages es un paso de tu repositorio, no se ha realizado en esta entrega. La disponibilidad de Pages depende de la visibilidad del repositorio y de tu plan.
Guía oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages

## Referencias y dirección de diseño

Consulta realizada el 14 de septiembre de 2026. No es un ranking objetivo de las mejores webs.

- Snøhetta: https://www.snohetta.com/ — proyectos acompañados por su intención y relación con el lugar. Aplicación: relato y decisiones en cada ficha.
- Studio MK27: https://mk27.com/ — organización del portfolio por especialidad. Aplicación: categorías visibles y lectura clara del tipo de encargo.
- John Pawson: https://www.johnpawson.com/ — estructura breve con arquitectura, diseño, diario y estudio. Aplicación: navegación sencilla y prioridad al trabajo visual.
- Herzog & de Meuron: https://www.herzogdemeuron.com/ — archivo de proyectos, práctica y créditos. Aplicación: ficha con alcance y materialidad, distinguiendo claramente imágenes conceptuales.

La composición de HABITA es original: portada cinematográfica, tipografía de gran escala, fondos claros, contraste carbón y verde oliva, y un ritmo de imágenes de distintos tamaños. No se han copiado fotografías, logotipos ni código de los estudios de referencia.

Las tres imágenes son visualizaciones generadas con IA para esta demostración. Reemplázalas por fotografías y textos de tus proyectos antes del lanzamiento comercial. Confirma también los servicios y tu presentación.

## Verificación de esta entrega

Revisión de sintaxis JavaScript, referencias de archivos, datos de proyectos y dimensiones de las imágenes. CSS con disposiciones para móvil, tablet y escritorio, navegación por teclado, foco visible y preferencia de movimiento reducido. No se realizó una prueba visual en navegador ni se ejecutó el workflow en GitHub.

## Ubicación y servicios confirmados

HABITA está en Cieneguilla, Lima, Perú, cerca de la escuela de basketball 24 Segundos, según el propietario. El enlace Maps es una búsqueda por nombre, no un marcador verificado. Sustituir `mapsUrl` en `dist/contenido.js` por el enlace Compartir de la ficha exacta cuando el propietario lo facilite.

Servicios confirmados: cabañas alpinas, diseño arquitectónico y planos, diseño de interiores, remodelaciones, licencias municipales y ejecución de proyectos. Se conserva mobiliario a medida de la versión anterior.

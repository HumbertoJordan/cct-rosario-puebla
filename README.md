# Escuela Rosario Puebla de Godoy · CCT 6016

Sitio institucional estático, listo para publicar en GitHub Pages. No requiere instalar
dependencias ni compilar.

## Probarlo

Abrí `index.html` en un navegador. Para la publicación en GitHub Pages, subí los archivos
de esta carpeta a un repositorio y elegí **Settings → Pages → Deploy from a branch**,
seleccionando `main` y la carpeta `/ (root)`.

## Personalizar imágenes y logo

- Reemplazá las letras `RP` del encabezado por el logo oficial cuando lo tengas digitalizado.
- Se puede sumar una foto en el encabezado o una galería cuando haya imágenes autorizadas
  de la escuela y sus actividades.
- El encabezado ya tiene preparado el espacio para un video. Cuando haya un clip, guardalo
  como `assets/hero.mp4` y agregá dentro del elemento `<video class="hero-video">`:

  ```html
  <source src="assets/hero.mp4" type="video/mp4">
  ```

  Conviene que sea MP4/H.264, breve, sin audio, idealmente 720p y comprimido (menos de
  10 MB). Mientras tanto, se ve la ilustración de fondo y no se solicita ningún video.
- La lista de documentación de inscripción es preliminar y se limita a los datos
  confirmados. Verificá con la escuela si piden otros documentos.
- El teléfono de la escuela informado es `261 539-4803`; se muestra como llamada telefónica,
  no como WhatsApp.
- Para generar el QR informativo definitivo, primero publicá el sitio y usá la URL de
  GitHub Pages como destino hacia `#inscripcion`. No generes el código con la ruta local
  `file://`, porque no funcionará en otros dispositivos.

## Datos pendientes de confirmar

Antes de publicar, completar o verificar el listado completo de cursos, la oferta vigente,
los requisitos y fechas de inscripción, la dirección exacta y los horarios. El mapa busca
la institución por nombre y localidad; confirmá que el resultado sea el correcto.

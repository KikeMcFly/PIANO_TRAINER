# Piano Trainer

App web para aprender piano con archivos MIDI y la entrada MIDI de tu piano. Solo muestra las notas: el sonido sale siempre del piano conectado.

## Archivos
- `index.html`: la app completa (todo en un archivo)
- `sw.js`, `manifest.webmanifest`, `icon-*.png`: permiten instalarla y usarla sin internet

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `piano-trainer`).
2. Sube estos 6 archivos a la raíz del repositorio (botón **Add file → Upload files**).
3. Ve a **Settings → Pages**, elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
4. En 1–2 minutos queda en `https://TU-USUARIO.github.io/piano-trainer/`.
5. Ábrela una vez con internet y elige **Agregar a pantalla de inicio**. A partir de ahí abre a pantalla completa y funciona sin internet.

## Conectar el piano
- **Android (Chrome):** con un cable USB OTG funciona directo. Para Bluetooth, empareja primero el piano con una app como "MIDI BLE Connect" y después abre Piano Trainer.
- **PC / laptop (Chrome o Edge):** por USB, o por Bluetooth MIDI si el sistema ya lo emparejó.
- **iPhone / iPad:** Safari no puede leer MIDI. Abre la dirección dentro de la app gratuita "Web MIDI Browser".

## Modos
- **Libre:** la canción corre y no te espera.
- **Espera:** se detiene en cada línea hasta que estén presionadas todas sus notas.
- **Maestro:** divide la canción en secciones de N compases, con tiempo de reacción y golpes por acorde. Si fallas, la sección vuelve a empezar; pasas a la siguiente después de las repeticiones limpias.

Para el loop, pon la canción donde quieres empezar y toca **A**, luego en donde quieres terminar y toca **B**. El loop respeta la mano y el modo que tengas elegidos.

# Sharkware Gaming — Presentación

Deck de presentación del proyecto **Sharkware Gaming** (e-commerce de hardware gaming).
HTML estático autocontenido con los clips de demo embebidos y **narración auto-reproducible**.

## Ver online
GitHub Pages: `https://mondati.github.io/sharkware-presentacion/`

## Ver localmente
Abrir `index.html` en el navegador.

## Modo presentación narrada (auto-play)
1. Abrí la página y hacé click en **▶ Reproducir presentación** (un click es obligatorio:
   los navegadores bloquean el audio hasta que el usuario interactúa).
2. La presentación corre sola: cada slide reproduce su narración y su clip, y **avanza
   sola** cuando termina (en slides de video, cuando termina lo más largo: voz o clip).

Controles:
- **Espacio**: play / pausa · **M**: silenciar
- **← →** (o click izq/der): navegar manual · **F**: pantalla completa
- Botones de play/pausa y mute abajo a la izquierda.

### Agregar la narración
Grabá un audio por slide y dejalo en `audio/` con los nombres `slide-01.mp3` …
`slide-14.mp3`. **El texto exacto a narrar en cada sección está en `audio/README.txt`**
(listo para pasarle a quien graba). Si falta algún audio, esa slide usa un tiempo por
defecto y no se rompe.

## Exportar a un video MP4 (grabando la pantalla)
Como la narración ya está en la página, no hace falta micrófono al grabar: alcanza con
capturar pantalla + audio del sistema.

**Opción A — OBS Studio (gratis, recomendado):**
1. Instalá OBS, agregá una fuente **"Captura de pantalla" (Display Capture)** y verificá
   que **"Audio del escritorio / Desktop Audio"** esté activo en el mezclador.
2. Abrí la presentación, poné **F** (pantalla completa).
3. En OBS: **Iniciar grabación** → en la página, click **▶ Reproducir presentación**.
4. Cuando termine sola, **Detener grabación**. Queda un `.mp4` listo para subir a YouTube
   o entregar (Archivo → Mostrar grabaciones).

**Opción B — Xbox Game Bar (Windows):** `Win + G` → grabar la ventana del navegador con
el audio del sistema activado. Menos control que OBS pero sirve.

> Tip: grabá a 1920×1080. Hacé una pasada de prueba para chequear que se escuche la voz.

## Equipo
Franco Champane · Agustín Mondati · Lucca Goria · Tomás Lombardo

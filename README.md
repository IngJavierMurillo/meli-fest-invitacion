# Meli Fest · Invitación Y2K

Proyecto listo para GitHub Pages.

## Estructura

```text
meli-fest-invitacion/
├── index.html
└── assets/
    ├── meli-bg.png
    └── meli-song.mp3
```

## Uso local

Abre `index.html` en un navegador.

## Publicar en GitHub Pages

1. Crea un repositorio llamado `meli-fest-invitacion`.
2. Sube `index.html` y la carpeta `assets/`.
3. Ve a `Settings → Pages`.
4. En `Build and deployment`, selecciona `Deploy from a branch`.
5. Selecciona rama `main` y carpeta `/root`.
6. Guarda. GitHub generará el link público.

## Ajustes rápidos

Dentro de `index.html`:

- Audio inicia en segundo 10: `AUDIO_START_TIME = 10`.
- Espera antes de revelar mensaje: `MESSAGE_DELAY = 6000`.
- Posición/tamaño de la pantalla: clase `.screen` en CSS.
- Tamaño del texto: variable CSS `--msg-font` en `.screen`.

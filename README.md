# Carta de Kuromi para GitHub Pages 💜

Carta digital interactiva hecha con **HTML, CSS y JavaScript**, que incluye la ilustración principal de Kuromi de la referencia y tres imágenes adicionales del personaje extraídas de esa misma ilustración (sin los botones superpuestos de la captura de pantalla).

## Cómo verla

Abre `index.html` en tu navegador. Necesita la carpeta `assets/` junto a `index.html`.

## Cómo cambiar el texto de la carta

Abre `index.html`, busca esta línea y reemplaza solo el contenido entre las comillas invertidas:

```js
const TEXTO_DE_LA_CARTA = `Aquí aparecerá tu mensaje especial ♡`;
```

## Cómo publicarla en GitHub

1. Crea un repositorio público en GitHub (por ejemplo, `carta-kuromi`).
2. Sube **el contenido de esta carpeta** a la raíz del repositorio (`index.html`, `README.md`, `assets/`). No subas únicamente el ZIP.
3. Ve a **Settings → Pages → Build and deployment**.
4. En **Source** elige **Deploy from a branch**; selecciona la rama `main` y la carpeta `/(root)`, y guarda.
5. Tras la publicación, visita `https://TU-USUARIO.github.io/carta-kuromi/` (reemplaza TU-USUARIO).

La carta se adapta a móviles y escritorio. No necesita servidor, instalación, ni bibliotecas JavaScript externas. Usa una fuente de Google Fonts, con una alternativa del sistema si no carga.

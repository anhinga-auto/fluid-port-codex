# WebGL Port

This directory contains a browser-based port of the Processing sketch using WebGL2 shaders.
The input texture is generated procedurally in the browser to keep the demo self-contained.

## Run locally

Because the demo uses ES modules, serve the directory with a local web server:

```bash
cd web
npx serve
```

Then open the URL printed by `serve` (usually `http://localhost:3000`).

Alternatively:

```bash
cd web
python -m http.server 8000
```

Open `http://localhost:8000` in your browser.

## Controls

- **Left column images:** click or drag to reset the wave center.
- **Right sliders:** click or drag to change the blend coefficient for the adjacent output.

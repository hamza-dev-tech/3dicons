# 3dicons

Hosted 3D models for web use.

## Rotating Kaaba

- **File:** `kaaba.glb` (2.46 MB — Draco-compressed geometry + WebP textures)
- **Live demo:** open `index.html`

### Direct URL (use this in `<model-viewer>` / Claude artifacts)

```
https://raw.githubusercontent.com/hamza-dev-tech/3dicons/main/kaaba.glb
```

### Minimal embed

```html
<script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>

<model-viewer
  src="https://raw.githubusercontent.com/hamza-dev-tech/3dicons/main/kaaba.glb"
  alt="Rotating Kaaba"
  auto-rotate
  rotation-per-second="20deg"
  camera-controls
  shadow-intensity="1"
  style="width: 100%; height: 500px; background: transparent;">
</model-viewer>
```

`<model-viewer>` natively supports the Draco compression and WebP textures used here — no extra setup needed.

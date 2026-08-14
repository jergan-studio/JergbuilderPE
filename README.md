# JergBuilder PE

**PE = Pocket Edition**

JergBuilder PE is the Pocket Edition version of JergBuilder. It keeps the same simple, static-web deployment style as JergBuilder, so it can be deployed without a server or build system.

## Features

- 3D block world
- Singleplayer worlds
- WASD / arrow-key movement
- Mouse look with pointer lock
- Space to jump
- Left click to break blocks
- Right click to place blocks
- 1–8 hotbar
- Mouse wheel hotbar selection
- Skin selection UI
- FOV setting
- JavaScript mod loader
- Mobile/Pocket Edition touch controls
- No build step required
- No backend required
- Runs directly from a static web host

## Deploy

JergBuilder PE is a static website. You can deploy the repository directly to:

- GitHub Pages
- Vercel
- Netlify
- Cloudflare Pages
- Any static web host

No Node.js server is required.

## Run locally

Open `index.html` in a modern browser, or use any simple static file server.

## Controls

### PC

| Key | Action |
|---|---|
| W / A / S / D | Move |
| Arrow keys | Move |
| Mouse | Look |
| Space | Jump |
| Left click | Break block |
| Right click | Place block |
| 1–8 | Select hotbar slot |
| Mouse wheel | Change hotbar slot |
| `[` | Toggle third person |

### Pocket Edition

On phones and tablets, JergBuilder PE uses touch-friendly controls for movement, looking, jumping, and block interaction.

## Project structure

```text
JergbuilderPE/
├── Assets/
├── Js/
├── Map/
├── index.html
├── style.css
└── README.md
```

## Relationship to JergBuilder

JergBuilder PE is designed to feel like the main JergBuilder project while remaining small and easy to deploy. It uses the same general browser-based Three.js approach and compatible gameplay concepts.

## Credits

Made by **Jergan Studio**.

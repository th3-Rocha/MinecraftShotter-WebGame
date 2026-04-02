# MinecraftShotter (WebGL)

A small **Unity WebGL** 3D shooter with **Minecraft-inspired graphics**, published to run directly in the browser.

This project is mainly meant for **studying C# / Unity scripting concepts**:
- player controller logic (movement + camera/aim)
- shooting/projectile behavior (arrows)
- basic game loop + input handling
- performance options (resolution / shadows)

> If you want this repo to be a real “study C#” repository, consider adding the Unity project folder (especially `Assets/` with the `.cs` scripts). Right now this repo mostly contains the **exported WebGL build**, not the original C# source.

## Play online
- GitHub Pages: https://th3-rocha.github.io/MinecraftShotter-WebGame

## Controls
- **W A S D** — move Steve
- **Mouse** — aim + shoot arrows
- **Numpad -** — decrease resolution
- **Numpad +** — increase resolution
- **Numpad 9** — disable shadows

## Mechanics (confirmed from this repo)
- **First/third-person movement** (WASD)
- **Aiming with mouse**
- **Shooting arrows** (projectile-based shooting)
- **Graphics / performance toggles**
  - resolution scaling
  - shadows toggle

## Tech
- **Engine:** Unity (WebGL build)
- **Web wrapper:** HTML + JavaScript + CSS (Unity loader + canvas)
- **Build output:** `Build/` (Unity WebGL `.data`, `.wasm`, `.framework.js`, loader)

## Project structure (high level)
- `index.html` — page that hosts the Unity WebGL canvas and bootstraps the build
- `Build/` — Unity WebGL build files (generated)
- `TemplateData/` — Unity WebGL template styles/assets (generated)
- `StreamingAssets/` — Unity StreamingAssets packaged for WebGL

## Contributing / studying tips
- If you are studying Unity + C#, the most useful files are usually in:
  - `Assets/Scripts/*.cs` (player controller, weapon/shooting, UI, etc.)
- If you add those folders to the repo, I can read them and update this README with a **complete mechanics list** (enemies, damage, pickups, levels, UI, etc.).

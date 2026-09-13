# Storm Arena — browser battle prototype

A self-contained HTML5 canvas game inspired by the core loop of modern build-and-shoot battle royale games.

## Included
- First-person raycast rendering with no external runtime dependencies
- WASD movement, sprint, jump, mouse aim, pointer lock
- Rifle shooting, ammo, hit detection, health + shield
- 12 AI rivals with simple movement and ranged attacks
- Placeable wall/ramp/floor build pieces
- Closing safe-zone damage
- Victory / elimination state
- Desktop controls plus basic touch controls

## Run
Open `index.html` directly in a modern browser. For best pointer-lock behavior, serve the folder from a local static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080/`.

## Notes
This is an original browser implementation. It does not bundle Epic Games/Fortnite proprietary models, maps, textures, audio, or source code. The linked GitHub repository is an Unreal Engine source repository, so its native engine code is not directly portable to a canvas/web build.

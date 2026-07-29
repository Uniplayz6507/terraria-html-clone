# Terraforge

A small, original browser sandbox adventure inspired by the genre of 2D mining and building games. It is not affiliated with Terraria and uses no Terraria assets.

## Play
Open `index.html` directly, or serve the folder with any static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Current build
- Procedural pixel-style world with grass, dirt, stone, copper, crystal, trees, and caves-in-progress
- WASD/arrow movement, jumping, collision, camera follow, day/night tint
- Mouse mining and right-click building
- Animated player sprite and bouncing slimes
- Health, mana, hotbar, collection, particles, and basic crafting prompt
- Zero dependencies and no external assets, so it is easy to edit and deploy

## Roadmap
This is the foundation for a larger game, not a claim to reproduce every Terraria system. Next good slices: save/load, inventory UI, recipes, equipment, biomes, bosses, lighting, audio, multiplayer, and a proper sprite atlas. Keep additions modular so future edits stay manageable.

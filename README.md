# FPS Buildings Environment Kit

A curated collection of **CC0 (Public Domain)** assets for building urban/military FPS game environments. All assets are free to use in personal and commercial projects — no attribution required (though appreciated).

## Contents

### 🏗️ Buildings (`buildings/`)

| Pack | Format | Count | Description |
|------|--------|-------|-------------|
| **Kenney City Kit Suburban** | FBX, OBJ, GLB | ~120 models | Modular suburban buildings, shops, houses, industrial — full city blocks |
| **Kenney Modular Buildings** | FBX, OBJ, GLB | ~100+ pieces | Brick, concrete, metal building modules — walls, windows, doors, roofs |

### 🛣️ Props (`props/`)

| Pack | Format | Description |
|------|--------|-------------|
| **Kenney City Kit Roads** | FBX, OBJ, GLB | Road segments, intersections, sidewalks, crossings |

### 🌿 Environment

| Path | Format | Count | Description |
|------|--------|-------|-------------|
| `environment/vegetation/` | GLB | **68 models** | Quaternius Stylized Nature MegaKit — trees, bushes, flowers, grass, ferns, clover, dead trees |
| `environment/skyboxes/` | HDR | **4 HDRIs** | Poly Haven: urban street, alley, clear sky, overcast sky (2K) |
| `environment/ground-textures/` | JPG (PBR) | **7 packs, 40 maps** | ambientCG: Asphalt, Brick, Concrete, Grass, Ground, Metal, Road — each with Color, Normal, Roughness, Displacement, AO |

### 🪖 Military (`military/`)

| Pack | Format | Description |
|------|--------|-------------|
| **Kenney Desert Shooter Pack** | PNG + WAV | Desert-themed 2D sprites (characters, weapons, enemies, UI) + sound effects — good for prototype/placeholder |

## Quick Start

```bash
# Clone the repo (without LFS — all files are under 100MB natively)
git clone https://github.com/petroulacl/fps-buildings-env-kit.git
```

Assets are stored in standard formats (FBX, OBJ, GLB/GLTF, HDR) and can be imported directly into:

- **Unity** — Drag .fbx / .glb into Assets
- **Unreal Engine** — Import .fbx directly
- **Godot** — Import .glb / .obj natively
- **Blender** — File > Import > glTF / FBX / OBJ

## Asset Sources & Credits

All assets are **CC0 / Public Domain** — free for any use, no attribution required. Respect the original creators:

| Source | Packs | License |
|--------|-------|---------|
| **[Kenney](https://kenney.nl)** | City Kit Suburban, Modular Buildings, City Kit Roads, Desert Shooter Pack | CC0 |
| **[Quaternius](https://quaternius.com)** | Stylized Nature MegaKit (68 models) | CC0 |
| **[Poly Haven](https://polyhaven.com)** | HDRIs (urban_street_01, urban_alley_01, kloppenheim_02, kloppenheim_06) | CC0 |
| **[ambientCG](https://ambientcg.com)** | PBR ground textures (Asphalt, Brick, Concrete, Grass, Ground, Metal, Road) | CC0 |

## File Size

~623 MB total on disk, all assets under 100 MB individually — no Git LFS required.

## Automation

This repo was assembled using [Hermes Agent](https://hermes-agent.nousresearch.com) with curl+browser automation scripts for batch download and extraction. The `scripts/` directory contains any helpers used in the process.

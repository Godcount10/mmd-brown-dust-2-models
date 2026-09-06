# MMD Brown Dust 2 Models

Versioned Brown Dust 2 Spine resources for the MMD HUD.

Source: https://github.com/Zormolo/Brown-Dust-2-Assets/tree/2da10c18b4b1c963949da62591f5d1cabd69cb0b

This snapshot contains 492 Spine 4.1.11 models.
It is a community snapshot, not a guarantee of complete official game coverage.

## Layout

- assets/: original skeletons, atlases, textures and skill cutscene backgrounds.
- hud-assets/v1/packages/: external scripts registering skeleton/atlas data for MMD playback.
- hud-assets/v1/catalog.json: remote catalog using the immutable release tag.
- upstream/: original README, source index and dependency inventory.
- manifest.json: byte sizes, SHA-256 and Git blob hashes for every publication file.

Use v1.0.0, not main, for CDN URLs:

```text
https://cdn.jsdelivr.net/gh/Godcount10/mmd-brown-dust-2-models@v1.0.0/hud-assets/v1/catalog.json
```

No Git LFS is used. Models are requested individually; the complete snapshot is not a startup download.
The upstream LICENSE is preserved. Game assets remain the property of their respective rights holders;
the source repository license does not independently establish rights to all game artwork.

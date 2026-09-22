# Lumina Scenes

Public catalog of interactive wallpaper scenes for [Lumina](https://github.com/PhoenixtBlaze/Lumina).

Installed Lumina apps download updates from:

`https://raw.githubusercontent.com/PhoenixtBlaze/Lumina-Scenes/main/catalog/`

## Layout

| Path | Purpose |
|------|---------|
| `catalog/scenes.json` | Version index + SHA-256 for each package |
| `catalog/packages/*.zip` | Scene packages (HTML/JS/CSS/assets only) |

## Publishing (from the private Lumina app repo)

1. Edit a scene under `src/Lumina/Scenes/` and bump `"version"` in `scene.json`.
2. Run `tools/publish-scenes.ps1 -PushPublic` in the Lumina repo (requires this repo checked out as a sibling `Lumina-Scenes` folder).
3. Confirm the push to `main` on this repository.

The Lumina application binary is never updated from this catalog.

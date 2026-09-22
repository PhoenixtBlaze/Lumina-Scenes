# Lumina Scenes

Public catalog of interactive wallpaper scenes for Lumina.

Installed apps (1.1.1+) download updates from:

`https://raw.githubusercontent.com/PhoenixtBlaze/Lumina-Scenes/main/catalog/`

## Layout

| Path | Purpose |
|------|---------|
| `catalog/scenes.json` | Version index + SHA-256 for each package |
| `catalog/packages/*.zip` | Scene packages (HTML/JS/CSS/assets only) |

## Publishing

From the private Lumina app repo (with this repo as sibling `../Lumina-Scenes`):

```powershell
.\tools\publish-scenes.ps1 -PushPublic
```

The Lumina application binary is never updated from this catalog.

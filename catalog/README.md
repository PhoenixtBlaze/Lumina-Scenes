# Scene update catalog (staging in the private app repo)

The **live** catalog patrons download is the public repository:

https://github.com/PhoenixtBlaze/Lumina-Scenes

Catalog base URL baked into Lumina:

`https://raw.githubusercontent.com/PhoenixtBlaze/Lumina-Scenes/main/catalog/`

This `catalog/` folder is the staging copy next to the scene sources. To publish:

1. Edit a scene under `src/Lumina/Scenes/` and bump `"version"` in `scene.json`.
2. Run `tools/publish-scenes.ps1 -PushPublic` (requires `../Lumina-Scenes` cloned).
3. Optionally commit the staging `catalog/` here for history in the app repo.

See [docs/SCENE-UPDATES.md](../docs/SCENE-UPDATES.md).

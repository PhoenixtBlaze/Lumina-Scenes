# Scene update catalog

Installed Lumina apps fetch `scenes.json` from this folder on GitHub, then download newer
scene zips from `packages/`.

## Publish an update

1. Edit the scene under `src/Lumina/Scenes/`.
2. Bump `"version"` in that scene's `scene.json`.
3. Run `tools/publish-scenes.ps1`.
4. Review the diff under `catalog/`, commit, and push to `main`.

See [docs/SCENE-UPDATES.md](../docs/SCENE-UPDATES.md) for security assumptions and client behaviour.

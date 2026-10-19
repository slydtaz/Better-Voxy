# Troubleshooting

## The game does not launch

- Confirm the Minecraft and Fabric Loader versions match the Better Voxy release.
- Let the Modrinth App finish installing all files.
- Try an unchanged, clean instance.
- Record the complete error message and the latest log.

## Voxy or distant terrain is not visible

- Confirm Voxy is installed and enabled.
- Allow the game to load or generate terrain data.
- If using Chunksmith, confirm the task completed and consult its documentation for LOD support.
- Temporarily disable shaders and additional visual mods to rule out conflicts.

## Low performance or stuttering

- Lower expensive rendering settings gradually.
- Pause Chunksmith while checking whether pre-generation is responsible.
- Test without additional mods, shaders, and resource packs that you installed yourself.
- Close unnecessary applications and check available memory.

## Find logs

Open the Better Voxy instance folder from the Modrinth App. Common locations are:

- `logs/latest.log`
- `crash-reports/`

Share only the relevant log or crash report. Remove access tokens, personal data, and private server addresses. Never upload your entire Minecraft directory or a world save.

## Check for mod conflicts

Test in a duplicated instance. First reproduce the problem with the original modpack. If it works, add your extra mods back one at a time. Record any configuration changes and the result of each test.

## Report the issue

- [Minor or unknown bug](https://github.com/slydtaz/Better-Voxy/issues/new?template=03-bug-minor-or-unknown.yml)
- [Crash or serious issue](https://github.com/slydtaz/Better-Voxy/issues/new?template=04-crash-or-serious-issue.yml)

# Troubleshooting

If Better Voxy is acting up, start with the checks below. Change one thing at a time so you can narrow down what is actually causing the problem.

## Minecraft will not launch

- Check that the Minecraft and Fabric Loader versions match the Better Voxy release you installed.
- Wait for the Modrinth App to finish downloading every file.
- Try launching a clean instance without extra mods or settings changes.
- Save the full error message and the latest log so you can share the relevant part if needed.

## Voxy is not showing distant terrain

- Make sure Voxy is installed and enabled.
- Give the game time to load or generate the terrain data it needs.
- If you used Chunksmith, check that the task finished and that your versions support the LOD workflow you are using.
- Temporarily turn off shaders and extra visual mods to check whether one of them is causing a conflict.

## Low FPS or stuttering

- Lower demanding rendering settings a little at a time.
- Pause Chunksmith while testing, in case chunk pre-generation is using too many resources.
- Test without any extra mods, shaders, or resource packs you added yourself.
- Close background apps you do not need and check how much memory is available.

## Where to find logs

Open your Better Voxy instance folder in the Modrinth App. The most useful files are usually:

- `logs/latest.log`
- Files inside `crash-reports/`

Share only the relevant log excerpt or crash report. Remove access tokens, personal information, and private server addresses first. Do not upload your entire Minecraft folder or a world save.

## Check for mod conflicts

Try this in a duplicate instance so your main setup stays safe. First, reproduce the problem with Better Voxy unchanged. If it works, add your extra mods back one at a time and test after each addition. Keep track of any settings you changed, too.

## Still stuck?

- [Report a minor or unknown bug](https://github.com/slydtaz/Better-Voxy/issues/new?template=03-bug-minor-or-unknown.yml)
- [Report a crash or serious issue](https://github.com/slydtaz/Better-Voxy/issues/new?template=04-crash-or-serious-issue.yml)
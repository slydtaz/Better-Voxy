# Configuration

Better Voxy includes Voxy and several optimization mods. The exact settings and file names can change between mod versions, so use the documentation for the version you have installed rather than guessing.

## Find the configuration files

1. Open the Modrinth App.
2. Select your Better Voxy instance.
3. Open the instance menu and choose **Open folder**.
4. Look for the `config` directory.

Some mods also have their own settings screens, often available through Mod Menu. If a setting is available in-game, that is usually the easiest place to change it.

## Change settings without making a mess

1. Close Minecraft before editing a file by hand.
2. Make a copy of the file you plan to change.
3. Change one setting at a time so you can tell what made a difference.
4. Restart the game and test the result.
5. If something breaks, restore the backup and try again.

Do not guess file names or copy values from a different Minecraft or mod version. A setting that works in one release may be missing or behave differently in another.

## Voxy and rendering

If you want to adjust render distance or LOD quality, make small changes and test between them. Higher settings can use more memory, storage, and GPU resources. When tracking down a visual issue, temporarily turn off shaders so you can rule out a shader conflict.

## Chunksmith

Depending on the installed version, Chunksmith may expose server-side options through `/cs set` and client-side LOD options through `/csclient set`. Check the official documentation for the exact names and accepted values in your build.

## Reporting a configuration issue

Tell us which file or option you changed and, if you know them, the old and new values. It also helps to say whether the problem goes away when you restore the original setting. Do not include passwords, access tokens, or private server details in a public report.
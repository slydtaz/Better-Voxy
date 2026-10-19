# Configuration

Better Voxy includes Voxy and optimization mods. The exact settings and filenames depend on the version of each included mod.

## Locate the instance configuration

1. Open the Modrinth App.
2. Select the Better Voxy instance.
3. Open its menu and choose **Open folder**.
4. Look for the `config` directory.

Some mods expose options through Mod Menu or their own configuration screen. Consult each mod's official documentation before editing a file by hand.

## Safe editing

1. Close Minecraft before editing files manually.
2. Back up the file first.
3. Change one setting at a time.
4. Restart the game and test.
5. Restore the backup if the change causes problems.

Do not guess config filenames or copy values from unrelated Minecraft versions.

## Voxy and rendering

Change render-distance and LOD values gradually. Higher settings can increase memory, disk, and GPU use. If you use shaders, temporarily disable them when diagnosing visual problems.

## Chunksmith

Chunksmith versions may expose server-side settings using `/cs set` and client-side LOD settings using `/csclient set`. Check the official documentation for your installed build for the exact setting names and accepted values.

## Report a configuration issue

Include the file or option changed, the old and new values if known, and whether the issue persists after reverting the change. Remove passwords, tokens, and private server information from public reports.

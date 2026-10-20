# Release Checklist

Use this checklist before publishing a new Better Voxy version. It is worth taking a few minutes to test a clean export; that is much easier than trying to fix a broken release after people have installed it.

## Check the package

- Confirm `modrinth.index.json` is at the root of the `.mrpack`.
- Check the pack name, version, Minecraft version, and Fabric Loader metadata.
- Verify that listed files have the expected SHA-1, SHA-512, and file-size values.
- Make sure the archive contains the index and only the intended `overrides/` files.
- Import the package as a new, clean instance through the Modrinth App.
- Launch it and test Voxy, Mod Menu, Text Placeholder API, Chunksmith, and the main optimization features.

## Compatibility and permissions

- Check Minecraft and loader compatibility for every included mod.
- Complete the current Modrinth permissions process for third-party files.
- Do not claim permission to distribute a file unless its license or written authorization actually allows it.
- Remove or replace files that cannot be distributed.

## Review the project page

- Use an original project icon and gallery images that meet Modrinth's current rules.
- Read through the description, categories, version details, and changelog one more time.
- Test the source-code, issue-tracker, and documentation links.
- Open each of the four GitHub issue forms and make sure it still works.

## After publishing

- Check that the public download works.
- Keep a copy of the last known-good `.mrpack`.
- Record the changes and any known issues in the changelog.
- If a new problem comes up, add the fix or workaround to the troubleshooting guide.
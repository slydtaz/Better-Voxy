# Release Checklist

Use this checklist before publishing a new Better Voxy version.

## Package

- Confirm `modrinth.index.json` is at the root of the `.mrpack`.
- Confirm the name, version, Minecraft version, and Fabric Loader metadata.
- Verify all listed files have valid SHA-1, SHA-512, and file-size values.
- Include only the index and intended `overrides/` files in the archive.
- Import the pack as a clean instance through the Modrinth App.
- Launch and test Voxy, Mod Menu, Text Placeholder API, Chunksmith, and major optimization features.

## Compatibility and permissions

- Check Minecraft and loader compatibility for every mod.
- Complete the current Modrinth permissions workflow for third-party files.
- Do not claim distribution permission without a license or authorization that supports it.
- Remove or replace files that cannot be distributed.

## Project page

- Use an original project icon and gallery artwork that comply with current Modrinth rules.
- Check the description, categories, version metadata, and changelog.
- Verify Source, Issue tracker, and documentation links.
- Test all four GitHub issue forms.

## After release

- Verify the public download works.
- Keep a backup of the last known-good package.
- Record changes and known issues in the changelog.
- Add recurring fixes to the troubleshooting documentation.

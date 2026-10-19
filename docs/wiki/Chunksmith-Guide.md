# Chunksmith Guide

Chunksmith is the chunk pre-generation tool selected for Better Voxy in place of the normal Chunky mod. It can pre-generate world chunks and prepare LOD data for supported distant-terrain renderers such as Voxy.

Consult the [official Chunksmith project](https://github.com/Kishku7/Chunksmith) for commands and setting names that match your installed version.

## Before pre-generating

- Back up the world.
- Start with a small test area.
- Make sure you have enough disk space.
- Large areas can take a long time and use substantial CPU and storage.

## Basic example

The following is an illustrative command sequence. Confirm each command against the documentation bundled with your Chunksmith version before starting a large job.

```text
/cs world minecraft:overworld
/cs spawn
/cs radius 5000
/cs start
```

This selects the Overworld, uses world spawn as the center, sets a radius, and starts the task. A radius of 5000 is only an example; start smaller if you are unsure.

## Task controls

```text
/cs progress
/cs pause
/cs continue
```

Use the version-specific Chunksmith documentation for supported commands and options. Server-side pre-generation commands and client-side LOD commands are separate; some versions use `/csclient` for client LOD settings.

## Troubleshooting

If generation creates severe lag, pause the task and reduce its scope. If the LOD data does not appear in Voxy, check compatibility, task completion, and the official documentation.

When reporting crashes, include the Minecraft and Fabric versions, Chunksmith version, changed settings, and a sanitized crash report or relevant `logs/latest.log` excerpt.

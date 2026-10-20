# Chunksmith Guide

Better Voxy uses Chunksmith instead of the usual Chunky mod for chunk pre-generation. It can prepare world chunks and, where supported by the installed versions, help make terrain data available to distant-terrain renderers such as Voxy.

Chunk generation can put a heavy load on your CPU and storage, especially across large areas. For the exact commands and options supported by your version, check the [official Chunksmith project](https://github.com/Kishku7/Chunksmith).

## Before you start

- Back up the world first.
- Try a small area before generating a much larger one.
- Check that you have enough free disk space.
- Expect large jobs to take time and use a lot of CPU and storage.

## Example command sequence

The commands below are an example, not a substitute for the documentation for your installed Chunksmith version. Check the command names and options before starting a large task.

~~~text
/cs world minecraft:overworld
/cs spawn
/cs radius 5000
/cs start
~~~

This example selects the Overworld, uses the world spawn as the center, sets a radius, and starts the task. A radius of `5000` is only an example and can mean a very large job. Start with a much smaller area if you are unsure.

## Checking or controlling a task

~~~text
/cs progress
/cs pause
/cs continue
~~~

Use the documentation for your installed build to confirm which commands are available. Server-side chunk generation and client-side LOD settings are separate; some versions use `/csclient` for client LOD options.

## If something goes wrong

If generation causes severe lag, pause the task and reduce the area before trying again. If Voxy still does not show the expected distant terrain, check that generation finished, confirm version compatibility, and consult the official Chunksmith documentation.

When asking for help, include your Minecraft and Fabric versions, Chunksmith version, any settings you changed, and a relevant excerpt from the crash report or `logs/latest.log`. Remove private information before posting.
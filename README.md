# Lenient Death — Server-side Death QoL

Lenient Death 9minecraft Mod softens the penalty of dying in your world without turning on full keepInventory. It saves player inventories and XP during fatal accidents, letting administrators view logs and return items when unfair hazards strike. The mod also highlights dropped items on the ground and posts exact death coordinates directly into the chat window.

Death Log History: Stores the full inventory, worn armor, and XP levels of players when they die.

## What this build is

An unofficial rebuild of **JackFred**'s original work, kept running on current Minecraft releases by 9Minecraft Studios. Not affiliated with the original author and not endorsed by them.

Most of the porting work sits in the mixin layer. Each Minecraft release moves or renames the methods this mod hooks into, so the hooks are re-pointed and re-tested against that version rather than rewritten. The behaviour underneath is upstream's and is deliberately left alone — that is the part that makes the mod feel right, and it is not ours to redesign.

## Source code

This build is released under **LGPL-3.0-only**. The complete corresponding source ships inside the downloadable file under `META-INF/sources/`, next to the original licence text.

## Versions

| Minecraft | Loader |
|---|---|
| 26.3 | Fabric, fabric |
| 26.2 | Fabric, fabric |

## Getting the built mod

Install steps, the dependency list, the screenshot gallery and what changed in each release are kept together on the download page:

[9minecraft.net/lenient-death-9minecraft-mod](https://www.9minecraft.net/lenient-death-9minecraft-mod/)

## Credits

Original work by **JackFred**. Port and maintenance by 9Minecraft Studios. Licensed LGPL-3.0-only; the upstream licence text ships inside every build.

# Emberbound Odyssey Minecraft Modpack

Emberbound Odyssey is a curated Minecraft Java Edition 1.20.1 Forge modpack that combines monster mods, RPG progression, exploration, magic, dungeons, bosses, immersive audio, shaders, and performance optimization for modest gaming PCs.

## Install

1. Install Minecraft Java Edition and create a clean 1.20.1 profile.
2. Install Forge 47.x for Minecraft 1.20.1 with Java 17 64-bit.
3. Create a Forge instance named `Emberbound Odyssey`.
4. Open `modpack/mods.json` and download the Forge 1.20.1 version of each required mod from its linked official CurseForge or Modrinth page.
5. Place the downloaded mod files in the instance `mods` folder. Install the listed dependency libraries as well.
6. Download Complementary Reimagined from its official project page and place the shader file in the instance `shaderpacks` folder. The shader is optional.
7. Copy the recommended settings from `modpack/performance.md` into the instance configuration and video settings.
8. Launch the instance once so Forge can generate configuration files, then restart it before creating your main world.
9. Create a new world after installing all selected world-generation and content mods.

Do not download mod files from re-upload sites. Keep every mod on Minecraft 1.20.1 and Forge 47.x. Do not install OptiFine or Rubidium alongside Embeddium and Oculus.

## Use

1. Allocate 6144 MB of RAM to the instance. Use up to 7168 MB only for especially large worlds or shader use.
2. Set render distance to 8 chunks, simulation distance to 5 chunks, and entity distance to 75%.
3. Begin with Fast graphics, decreased particles, 2 mipmap levels, and a 60 FPS cap.
4. Disable minimap entity radar and cave mode if you want a cleaner exploration challenge.
5. Start without shaders and confirm that the base pack runs smoothly.
6. Enable Complementary Reimagined through Oculus using the Low or Potato preset.
7. For better performance, disable volumetric clouds, depth of field, motion blur, screen-space reflections, parallax mapping, and high-quality shadows.
8. Start on Normal difficulty. Move to Hard after obtaining iron gear and several early spells.
9. Use JEI for recipes, Jade for block and mob information, Nature's Compass for biomes, Explorer's Compass for structures, and Waystones for travel.
10. If exploration stutters, lower render distance to 6–7 chunks and simulation distance to 4. Disable When Dungeons Arise first if large structures cause slow generation.
11. Back up your world before changing dimensions, world-generation mods, or major content mods.

The repository contains the complete categorized dependency manifest at `modpack/mods.json`, hardware-specific settings at `modpack/performance.md`, and conservative private-server defaults at `modpack/server.properties`.

---

More Minecraft mod projects by EnderDevelopment: https://github.com/EnderDevelopment

Project page: https://dash.enderdevelopment.com/community/87515042-2ecd-4fbc-a892-4893e6022f57?utm_source=github&utm_medium=readme&utm_campaign=auto_publish&utm_content=87515042-2ecd-4fbc-a892-4893e6022f57

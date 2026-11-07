# Performance Profile

## Baseline

Use the baseline before enabling shaders:

- Java 17 64-bit.
- RAM: 6144 MB.
- Render distance: 8 chunks.
- Simulation distance: 5 chunks.
- Entity distance: 75%.
- Max FPS: 60.
- Graphics: Fast.
- Particles: Decreased.
- Clouds: Fast or Off.
- Entity shadows: Off.
- Biome blend: 0x0.
- Mipmap levels: 2.
- Chunk builder threads: default or 2 if the game offers the option.
- Disable minimap entity radar and cave mode.

The FX-6300 is the likely limit during chunk generation and crowded combat. The GTX 1050 Ti is the likely limit when shaders, particles, and high shadow settings are enabled.

## Shader profile

Use Complementary Reimagined through Oculus. Start with the Low preset and change only these values:

- Shadow resolution: 1024 or the lowest stable option.
- Shadow distance: 6 to 8 chunks.
- Volumetric clouds: Off.
- Volumetric fog: Low or Off.
- Screen-space reflections: Off.
- Parallax or POM: Off.
- Depth of field: Off.
- Motion blur: Off.
- Bloom: Low.
- Reflections: Low.
- Hand light: Fast or Off.

Cap the game at 45 FPS if 60 FPS is unstable. A stable cap is preferable to large frame-time spikes.

## Content tuning

If the world feels crowded or the server tick rate drops:

1. Lower simulation distance to 4.
2. Keep render distance at 6 to 8.
3. Reduce hostile mob spawn settings in Born in Chaos and Apotheosis before removing content mods.
4. Disable When Dungeons Arise first; its large structures affect chunk generation and exploration memory.
5. Disable Alex's Caves second if initial world creation remains slow.
6. Keep the core performance mods installed.

Do not remove biome or structure mods after generating a main world. Start a fresh world after changing world-generation content.

## Troubleshooting

- Black or broken shaders: confirm Oculus and Embeddium versions both target Forge 1.20.1, remove OptiFine, and test without a resource pack.
- Low FPS in a base: disable shaders, then test entity shadows and particles before changing content mods.
- Stutters during exploration: lower render distance, keep mipmaps at 2, and pre-generate only a small area with an appropriate Forge-compatible tool if you understand its server impact.
- Long startup: allow the first launch to finish, keep ModernFix and FerriteCore, and avoid allocating more than 7 GB on a 16 GB machine.
- Crashes after adding a mod: remove the newest jar, inspect `latest.log`, and verify every dependency and Minecraft/Forge version.

## Stability checklist

- Keep one renderer stack: Embeddium plus Oculus, or no shaders.
- Keep all mods on Minecraft 1.20.1 and Forge 47.x.
- Back up saves before changing dimensions, world-generation mods, or major content mods.
- Do not use a huge resource pack with the shader profile.

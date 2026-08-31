# XP Orb Trails

XP Orb Trails is a client-only Fabric mod for Minecraft 26.2. It gives moving
experience orbs smooth, colorful light trails and an optional pickup flash,
without requiring shaders or any server-side installation.

## Features

- Smooth interpolated trails with adjustable lifetime and performance limits.
- Solid, gradient, and animated rainbow color modes.
- Separate head, middle, and tail widths, plus ready-made shape presets.
- Adjustable opacity, glow, motion shift, camera push, render range, and fading.
- Soft, star, and ring pickup flashes with conservative defaults.
- Built-in presets and named custom profiles.
- In-game color picker and a standalone animated preview window.
- Full Simplified Chinese and English interface.

## Installation

1. Install Minecraft 26.2 with Fabric Loader 0.19.5 or newer.
2. Put `xp-orb-trails-1.0.0+mc26.2.jar` in the client `mods` folder.
3. Fabric API 0.158.0 or newer is required. The server does not need this mod.

## Configuration

Install Mod Menu and use its Config button, or bind **Open Trail Settings** in
Minecraft's Controls screen. Changes apply immediately and are saved to
`config/xp-orb-trails.json` when the screen closes. Every settings page has its
own reset button, so unrelated choices are preserved. Hover over an option for
a short description.

If the configuration file becomes unreadable, the mod preserves it as
`xp-orb-trails.json.broken` (or a numbered variant), restores safe defaults, and
continues loading.

## Compatibility

- Minecraft 26.2
- Fabric Loader 0.19.5 or newer
- Fabric API 0.158.0+26.2 or newer
- Java 25 or newer
- Mod Menu is optional but recommended

The mod is client-only. It does not need to be installed on a server. Shader
packs are not required.

## Building from source

Run `./gradlew build` with Java 25. Release jars are written to `build/libs/`.

This is an independent implementation and contains no Shine source code or
assets.

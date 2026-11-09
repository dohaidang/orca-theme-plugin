# Living ASCII Themes for Orca

![Living ASCII Themes: fifteen pixel-art wallpapers drawn in text characters](images/cover.png)

Pixel-art wallpapers that move, drawn entirely in text characters. Fifteen scenes (fourteen dark, one light), each a seamless 30-second loop, with matching terminal palettes and a file and folder icon theme. The plugin is content only: it ships data files and runs no code.

## Themes

| Theme | Scene |
|---|---|
| ASCII · Coral Sunburst | a coral sun, with faint lines of code scrolling past |
| ASCII · Cloud Drift | white clouds crossing a blue sky |
| ASCII · Honu Lagoon | sea turtles over sand, coral and swaying seaweed |
| ASCII · Koi Pond | koi, lotus flowers and spreading ripples between lily pads |
| ASCII · Jellyfish | jellyfish that pulse as they rise, trailing tentacles |
| ASCII · Paper Boats | paper boats sailing across the waves |
| ASCII · Fireflies | fireflies drifting over tall grass |
| ASCII · Moonlit | a crescent moon, stars, clouds and shooting stars |
| ASCII · Aurora | northern lights over a mountain ridge |
| ASCII · Neon City | a skyline with flickering windows and flying cars |
| ASCII · Rainy Window | rain streaks and drops over blurred city lights |
| ASCII · Coral Reef | schools of fish, swaying coral and rising bubbles |
| ASCII · Snowfall Cabin | snow falling on a cabin with a smoking chimney |
| ASCII · Cherry Blossom | petals drifting from a blossoming branch (the light theme) |
| ASCII · Việt Nam | the national flag waving at dawn over Ha Long Bay, with junks and birds |

Every scene keeps moving across the whole window, not just in one corner, and every loop closes without a seam.

## Variants

Each theme comes in three variants:

- `ASCII · <name>`: the project and file sidebars follow the theme colors.
- `ASCII · <name> (dark sidebar)`: the sidebars use Orca's built-in dark sidebar colors.
- `ASCII · <name> (light sidebar)`: the sidebars use Orca's built-in light sidebar colors.

The wallpaper, terminal and chat follow the theme in all three.

## Install

1. Use Orca **1.4.246 or newer**. Animation needs **1.4.254 or newer**; on an older Orca every theme shows its still wallpaper instead.
2. Open **Settings → Plugins**, add this repository and enable the plugin.
3. Pick a theme under **Settings → Appearance → Dark theme** (or **Light theme** for Cherry Blossom), or click a **Use now** chip on the plugin page.
4. Optionally pick the matching palette under **Settings → Terminal → Dark Theme**, and `ASCII · Icons` under **Settings → Appearance → Icon theme**.

## Showing the wallpaper

Orca paints a theme's wallpaper only behind translucent terminals and chats:

- Set **Settings → Terminal → Window → Background Opacity** below 1. Start around 0.4, then raise it until text is comfortable to read.
- Turn off **Settings → Appearance → Reduce Visual Effects**. While it is on, Orca does not paint theme wallpapers at all.

The video plays only while the Orca window is focused, and it pauses on its current frame otherwise. With your system set to reduce motion, only the still wallpaper is shown.

## What is inside

- `themes/`: 45 app themes (15 designs × 3 sidebar variants).
- `terminal/`: 15 terminal palettes, one per design.
- `icons/`: one file and folder icon theme (`ASCII · Icons`).
- `images/`: for each design a still wallpaper (1920×1080 PNG) and a looping video (960×540 H.264 MP4, 20 fps, 30 seconds, no audio, 2.5 to 5.5 MB), plus the plugin icon and cover.

The still is the fallback: it is what you see while the video loads, on an Orca without video support, and under reduced motion.

## License

MIT

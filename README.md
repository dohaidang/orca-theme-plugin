# Living ASCII Themes for Orca

Eight dark Orca themes with looping ASCII wallpapers, matching terminal palettes and a file/folder icon theme. Content only: the plugin ships data files and runs no code.

| Theme | Wallpaper |
|---|---|
| ASCII · Coral Sunburst | slowly rotating coral sunburst |
| ASCII · Cloud Drift | white clouds drifting across a blue sky |
| ASCII · Honu Lagoon | sea turtle swimming under light rays |
| ASCII · Koi Pond | koi swimming between lily pads |
| ASCII · Jellyfish | jellyfish with trailing tentacles |
| ASCII · Paper Boats | paper boats bobbing on the waves |
| ASCII · Fireflies | blinking fireflies over swaying grass |
| ASCII · Moonlit | crescent moon, twinkling stars, drifting clouds |

Each theme comes in three variants:

- `ASCII · <name>`: the project and file sidebars follow the theme colors.
- `ASCII · <name> (dark sidebar)`: the sidebars use Orca's built-in dark sidebar colors.
- `ASCII · <name> (light sidebar)`: the sidebars use Orca's built-in light sidebar colors.

The wallpaper, terminal and chat follow the theme in all three.

## Contents

- `themes/`: 24 app themes (8 designs × 3 sidebar variants).
- `terminal/`: 8 terminal palettes, one per design.
- `icons/`: one file and folder icon theme (`ASCII · Icons`).
- `images/*-live.webp`: animated wallpapers, 960×540, 24 fps, 8-second seamless loop.
- `images/*.png`: static wallpapers. Themes do not reference them; they are kept for builds that cannot show animated images.

## Install

1. Use Orca **1.4.246 or newer**.
2. Open **Settings → Plugins**, add this repository (or a local clone of it) and enable the plugin.
3. Pick a theme under **Settings → Appearance → Dark theme**, or click a **Use now** chip on the plugin page.
4. Optionally pick the matching palette under **Settings → Terminal → Dark Theme**, and `ASCII · Icons` under **Settings → Appearance → Icon theme**.

## Showing the wallpaper

Orca paints a theme's wallpaper only behind translucent terminals and chats:

- Set **Settings → Terminal → Window → Background Opacity** below 1. Start around 0.4, then raise it until text is comfortable to read.
- Turn off **Settings → Appearance → Reduce Visual Effects**. While it is on, Orca does not paint theme wallpapers at all.

## Animated wallpapers need a patched Orca

Orca 1.4.246 only accepts **static** PNG, JPEG or WebP theme backgrounds of at most **2 MB**. These wallpapers are animated WebP files, and some are larger than 2 MB.

- On an unmodified Orca, the themes still load with their colors, but the wallpaper image is dropped.
- To see the animation, the build's image checks must allow animated WebP and a larger size limit.
- To use the plugin on an unmodified Orca, point each theme's `background.path` at its static PNG, for example `images/koi.png` instead of `images/koi-live.webp`.

## License

MIT

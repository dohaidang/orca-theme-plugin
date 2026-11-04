# ASCII Themes for Orca

![Eight ASCII wallpapers](images/cover.png)

Eight dark Orca themes with ASCII pixel-art wallpapers, matching terminal palettes and a file/folder icon theme. Content only: the plugin ships data files and runs no code.

| Theme | Wallpaper |
|---|---|
| ASCII · Coral Sunburst | coral sunburst |
| ASCII · Cloud Drift | white clouds on a blue sky |
| ASCII · Honu Lagoon | sea turtle under light rays |
| ASCII · Koi Pond | koi between lily pads |
| ASCII · Jellyfish | jellyfish with trailing tentacles |
| ASCII · Paper Boats | paper boats on the waves |
| ASCII · Fireflies | fireflies over tall grass |
| ASCII · Moonlit | crescent moon, stars and clouds |

Each theme comes in three variants:

- `ASCII · <name>`: the project and file sidebars follow the theme colors.
- `ASCII · <name> (dark sidebar)`: the sidebars use Orca's built-in dark sidebar colors.
- `ASCII · <name> (light sidebar)`: the sidebars use Orca's built-in light sidebar colors.

The wallpaper, terminal and chat follow the theme in all three.

## Contents

- `themes/`: 24 app themes (8 designs × 3 sidebar variants).
- `terminal/`: 8 terminal palettes, one per design.
- `icons/`: one file and folder icon theme (`ASCII · Icons`).
- `images/`: 8 static wallpapers (1920×1080 PNG), plus the plugin icon and cover.

## Install

1. Use Orca **1.4.246 or newer**.
2. Open **Settings → Plugins**, add this repository and enable the plugin.
3. Pick a theme under **Settings → Appearance → Dark theme**, or click a **Use now** chip on the plugin page.
4. Optionally pick the matching palette under **Settings → Terminal → Dark Theme**, and `ASCII · Icons` under **Settings → Appearance → Icon theme**.

## Showing the wallpaper

Orca paints a theme's wallpaper only behind translucent terminals and chats:

- Set **Settings → Terminal → Window → Background Opacity** below 1. Start around 0.4, then raise it until text is comfortable to read.
- Turn off **Settings → Appearance → Reduce Visual Effects**. While it is on, Orca does not paint theme wallpapers at all.

## Animated wallpapers

The `animated` branch has the same themes with looping animated WebP wallpapers. Orca currently accepts only static theme backgrounds of at most 2 MB, so that branch shows no wallpaper on a stock Orca build. The `main` branch is the supported release.

## License

MIT

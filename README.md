<p align="center">
  <img src="images/icon.png" alt="ASCII Themes icon" width="88" height="88">
</p>

<h1 align="center">ASCII Themes for Orca</h1>

<p align="center">Whole worlds, drawn in characters.</p>

<p align="center">
  15 wallpaper designs · 45 app themes · 15 terminal palettes · File and folder icons
</p>

![ASCII Themes: a preview of the collection in Orca](images/cover.png)

Give your Orca workspace a pixel-art backdrop made of ASCII characters: koi in a pond, northern lights over a mountain ridge, or the Vietnamese flag over Ha Long Bay, with matching app and terminal colors, plus an ASCII file icon theme.

Every design is a 1920 × 1080 still wallpaper. Choose matching sidebars or keep a familiar dark or light sidebar alongside your wallpaper.

> **Want it to move?** The [`animated` branch](https://github.com/dohaidang/orca-theme-plugin/tree/animated) has the same designs as 30-second looping videos for Orca 1.4.254 or newer. It is not in the Orca catalog yet, because the catalog does not accept video files, so it is installed from the branch.

**Find it useful?** Please consider [giving this project a GitHub star](https://github.com/dohaidang/orca-theme-plugin). It helps other Orca users discover the themes and supports the project. Thank you!

## What's included

- **15 wallpaper designs:** 14 dark designs and one light design, Cherry Blossom.
- **45 app themes:** three sidebar variants for every design.
- **15 terminal palettes:** a matching color palette for each scene.
- **ASCII · Icons:** a file and folder icon theme to complete the workspace.

The plugin is content only: it provides themes, images, and icons. It runs no plugin code.

## Get started

### Requirements

Orca **1.4.246 or newer**.

### Install and choose a theme

1. Open **Settings → Plugins** in Orca and choose **Add plugin → From a Git URL…**.
2. Enter `https://github.com/dohaidang/orca-theme-plugin` in **Repository URL**. Install and enable the plugin.
3. Open **Settings → Appearance → Interface** and select an `ASCII · …` design under **Dark theme** or **Light theme**. You can also use **Use now** on the plugin page.
4. Select **ASCII · Icons** under **Icon theme** in the same section if you want the matching file and folder icons.
5. Under **Settings → Appearance → Terminal → Terminal Themes**, choose the corresponding palette to match your terminal colors to the wallpaper.

### Make the wallpaper visible

Wallpapers appear behind translucent terminal and chat backgrounds. Set these options first:

1. Open **Settings**, search for **Background Opacity**, and set it below `1`. Try `0.4` as a starting point, then adjust for comfortable reading.
2. Search for **Reduce Visual Effects** and turn it off. You can also find it under **Appearance → Interface → Advanced**.
3. Return to your workspace.

## Explore the collection

Theme names in Orca begin with `ASCII ·`.

| Design | Scene |
| --- | --- |
| **Coral Sunburst** | A coral sun with lines of code scrolling past |
| **Cloud Drift** | White clouds moving through a blue sky |
| **Honu Lagoon** | Sea turtles over sand, coral, and swaying seaweed |
| **Koi Pond** | Koi, lotus flowers, lily pads, and spreading ripples |
| **Jellyfish** | Pulsing jellyfish rising with trailing tentacles |
| **Paper Boats** | Paper boats sailing across rolling waves |
| **Fireflies** | Fireflies drifting above tall grass |
| **Moonlit** | A crescent moon, moving clouds, stars, and shooting stars |
| **Aurora** | Northern lights over a mountain ridge |
| **Neon City** | A skyline with flickering windows and flying cars |
| **Rainy Window** | Rain streaks and droplets over blurred city lights |
| **Coral Reef** | Schools of fish, swaying coral, and rising bubbles |
| **Snowfall Cabin** | Falling snow and a cabin with a smoking chimney |
| **Cherry Blossom** | Petals drifting from a blossoming branch; the light design |
| **Việt Nam** | The national flag waving at dawn over Ha Long Bay, with boats and birds |

## Choose your sidebar style

Each design has three variants. The wallpaper stays the same; choose how you want the project and file sidebars to look.

| Variant | Sidebar appearance |
| --- | --- |
| `ASCII · <name>` | Colors coordinated with the wallpaper |
| `ASCII · <name> (dark sidebar)` | Orca's built-in dark sidebar colors |
| `ASCII · <name> (light sidebar)` | Orca's built-in light sidebar colors |

App themes, terminal palettes, and file icons can be selected independently.

## Troubleshooting

### The wallpaper is missing

Check that an `ASCII · …` app theme is selected, **Background Opacity** is below `1`, and **Reduce Visual Effects** is off. Your system's reduced-transparency setting can also prevent the wallpaper from appearing.

### The wallpaper makes text difficult to read

Increase **Background Opacity** until text is comfortable to read, and try a dark or light sidebar variant. Keep opacity below `1` to retain the wallpaper.

## Package contents

| Folder | Contents |
| --- | --- |
| `themes/` | 45 app theme definitions |
| `terminal/` | 15 terminal color palettes |
| `icons/` | The ASCII file and folder icon theme |
| `images/` | Wallpaper stills, the plugin icon, and cover image |

Wallpaper stills are **1920 × 1080 PNGs**.

## Feedback and contributions

Found a problem or have an idea for a new scene? [Open an issue](https://github.com/dohaidang/orca-theme-plugin/issues). For display or playback issues, include your Orca version, the theme name, and a screenshot if possible.

Pull requests are welcome. Please keep changes focused and describe what they improve.

## License

[MIT](LICENSE)

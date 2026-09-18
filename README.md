# iPodOS26 Y1 — 480×360

A 480×360 Rockbox port of **iPodOS26** for the **Innioasis Y1**, designed for the Y1's Rockbox 360p build.

This project takes the original iPodOS26 theme as its visual and technical base and adapts it to the Y1's 480×360 display, including its WPS, SBS, theme configuration, graphics, and Y1-specific layout requirements.

> **100% AI-created port:** this Y1 adaptation was developed entirely with AI assistance, using the original iPodOS26 theme by **john-robotic** as the base. The original project's design, assets, and Rockbox theme work are credited to its author.

## Credits

### Original iPodOS26

**Original author:** [john-robotic](https://github.com/john-robotic)

**Original project:** [iPodOS26](https://github.com/john-robotic/iPodOS26)

The original iPodOS26 project is a custom Rockbox theme inspired by the Liquid Glass design language of iOS 26. The original author states that the graphical UI was designed from scratch in Figma and that AI assistance was used for parts of the Rockbox theme code.

This repository is **not the original iPodOS26 project**. It is a Y1-specific 480×360 adaptation based on that work.

## Features

- Native **480×360** layout for Innioasis Y1 / Rockbox 360p.
- iPodOS26 Liquid Glass-inspired visual language.
- Dark and Light theme variants.
- Scaled WPS and SBS layouts.
- Y1 `/sdcard/.rockbox/` theme path convention.
- Y1-specific theme resource directories.
- Corrected transparent-looking icon assets for Rockbox BMP rendering.
- Screen-specific WPS/SBS assets where the same source icon appears over different backgrounds.
- Rebuilt progress-bar assets to avoid scaling artifacts.
- Custom Liquid Glass Quick Screen.
- Time positioned in the upper-left corner.
- Numeric battery percentage displayed next to the battery indicator.

## Versions

| Version | Description |
| --- | --- |
| **1.0.0** | Initial 480×360 Y1 port. |
| **1.0.1** | Fixed icon, volume and progress-bar background/scaling artifacts. |
| **1.1.0** | Added Liquid Glass Quick Screen, moved the clock to the upper-left, and added numeric battery percentage. |

## Requirements

- Innioasis Y1
- Rockbox installed
- **Rockbox 360p / 480×360 build**

This theme is intended for the **480×360 Y1 build**, not the 240p build.

## Installation

1. Back up the existing `.rockbox` folder on the Y1 SD card.
2. Extract the release ZIP.
3. Merge the included `.rockbox` folder with the `.rockbox` folder on the Y1 SD card.
4. Eject the SD card/device safely.
5. In Rockbox, open:

   `Settings → Theme Settings → Browse Theme Files`

6. Select the desired iPodOS26 Y1 theme.

## Development

The port is developed iteratively against the physical Innioasis Y1.

The goal is to preserve the visual identity and interaction model of the original iPodOS26 theme while adapting its geometry and Rockbox implementation to the Y1's 480×360 display.

The project intentionally keeps the original iPodOS26 attribution and treats the Y1 version as an adaptation rather than an independent recreation.

## Important attribution / licensing note

The original work belongs to **john-robotic** and the original iPodOS26 repository:

https://github.com/john-robotic/iPodOS26

Please review the original repository's current licensing and distribution terms before redistributing original iPodOS26 assets or other derivative files. A public GitHub repository does not, by itself, grant permission to relicense or redistribute copyrighted material.

This repository should not be interpreted as claiming ownership of the original iPodOS26 design, assets, or code.

## Disclaimer

This project is an independent community adaptation for the Innioasis Y1 and is not affiliated with Apple, Innioasis, or Rockbox.

The name iPodOS26 and the original iPodOS26 theme belong to their respective owners/authors. Apple is not affiliated with this project.

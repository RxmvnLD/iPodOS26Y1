# Changelog

All notable changes to the **iPodOS26 Y1 — 480×360** port are documented here.

The version history follows the project's adaptation milestones.

---
## [1.0.0] — Initial Y1 480×360 Port

### Added

- Initial **480×360** port of iPodOS26 for the Innioasis Y1 Rockbox 360p build.

- Resized the original 320×240 backdrop assets to 480×360.

- Scaled bitmap controls by **1.5×**.

- Scaled WPS/SBS viewport and coordinate geometry by **1.5×**.

- Adapted theme `.cfg` files to the Y1 `/sdcard/.rockbox/` path convention.

- Created WPS/SBS resource folders matching the new Y1 theme names so Rockbox can resolve theme assets correctly.

- Scaled main-menu list padding from the reference 15px convention to 23px.

- Added Dark and Light theme configurations.

### Compatibility

- Target: **Innioasis Y1**
- Rockbox mode: **360p**
- Display: **480×360**

### Font note

The original `16-Inter-V.fnt` font was retained for compatibility in 1.0.0.

Larger Rockbox fonts were identified as a future typography improvement for the 480×360 layout and were intentionally left outside the scope of the initial port.

---

## Original project

This project is based on **iPodOS26**, originally created by **john-robotic**:

https://github.com/john-robotic/iPodOS26

The original project is credited as the source/base for this Y1 adaptation.

---

## Versioning

- **1.0.x** — Initial port and bug fixes.
- **1.1.x** — Feature additions and UI improvements.
- Future versions will continue to separate bug-fix releases from feature releases where practical.

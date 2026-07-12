---
title: Custom tile pattern
---

# Custom tile pattern
This command helps you to create tiles considering the gap between them.
## Steps
## Tile Pattern Generator Guide

### Parameters Introduction:
* **Tile Width / Height:** Exact dimension of each tile. In Hexagonal pattern, only the Width is used and Height is calculated automatically.
* **Tile Gap (Joint):** The spacing between tiles. If set to 0, the pattern will be drawn as continuous lines without joints.
* **Unit:** For Revit, match the unit to your project settings. For AutoCAD, the 'Unitless (for AutoCAD)' option is highly recommended.

<img src="https://pars-bim.github.io/docs/Assets/Custom-tile-settings.png" alt="Custom tile" width="500">

### HOW TO USE IN AUTOCAD :

In order to use in AutoCAD simply go to the option menu -Files - Support file search path, and browse a folder that contain exported hatch pattern files .pat

<img src="https://pars-bim.github.io/docs/Assets/Help_autocad.png" alt="Custom tile-AutoCAD" width="500">

### HOW TO USE IN Revit :

In order to use in Revit the exported .pat file must be added in one material surface pattern. Follow the instructions in picture.

<img src="https://pars-bim.github.io/docs/Assets/Help_Revit.png" alt="Custom tile-Revit" width="500">

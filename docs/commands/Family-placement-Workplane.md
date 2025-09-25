---
title: Family placement - Workplane based.
---

# Family placement - Workplane based.
This command helps you to place Revit families on AutoCAD blocks coordinations automatically.

## Steps
1. First, since Revit can not read AutoCAD blocks definitions, we need to export AutoCAD blocks coordinates from AutoCAD it self. To do this click on "Export lisp" and save it on your computer.
   It doesn't matter where you save it but, the recommanded address is: C:\Program Files\Autodesk\AutoCAD [version]\Support
2. Then open the AutoCAD and your project. Type Appload in the command bar.

<img src="https://pars-bim.github.io/docs/Assets/Appload.jpg" alt="Select levels" width="500">

3. Select the exported file and load it. By default its name is: "ExportBlockCenters.lsp"

<img src="https://pars-bim.github.io/docs/Assets/load-exportblockcenters.jpg" alt="View Templates" width="500">

4. Type "EXPORTBLOCKCENTERS" in AutoCAD command bar and press "Enter". Then save the exported block coordinates where ever you want on your computer.

<img src="https://pars-bim.github.io/docs/Assets/save-exportblockcenters.jpg" alt="View Templates" width="500">

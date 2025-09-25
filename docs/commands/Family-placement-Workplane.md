---
title: Family placement - Workplane based.
---

# Family placement - Workplane based.
This command helps you to place Revit families on AutoCAD blocks coordinations automatically.

## Steps
1. First, since Revit can not read AutoCAD blocks definitions, we need to export AutoCAD blocks coordinates from AutoCAD it self. To do this click on "Export lisp" and save it on your computer.
   It doesn't matter where you save it.
   the recommanded address is: C:\Program Files\Autodesk\AutoCAD [version]\Support
   
2. Then open the AutoCAD and your project. Type Appload in the command bar.

<img src="https://pars-bim.github.io/docs/Assets/Appload.jpg" alt="Select levels" width="500">

3. Select the exported file and load it. By default its name is: "ExportBlockCenters.lsp"

<img src="https://pars-bim.github.io/docs/Assets/load-exportblockcenters.jpg" alt="View Templates" width="500">

4. Type "EXPORTBLOCKCENTERS" in AutoCAD command bar and press "Enter". Then save the exported block coordinates where ever you want on your computer.

<img src="https://pars-bim.github.io/docs/Assets/save-exportblockcenters.jpg" alt="View Templates" width="500">

5. Now you can import exported CSV file into the Revit. AutoCAD Block centers are exported in two ways. By geometry centers or by insertion point. Insertion point is the origin of the AutoCAD Block and it is depended on where it is defined by its creator and Geometry center is the center of the geometry. In fact center of its bounding box.
Also, you can define CSV unit in Revit.

<img src="https://pars-bim.github.io/docs/Assets/importCSV.jpg" alt="View Templates" width="500">

6. In next page, select the reference DWG file which is linked to the project. It is necessary to define reference level for placement. Also, you can select the reference DWG by selecting it in the active view by clicking on "Pick in view"

<img src="https://pars-bim.github.io/docs/Assets/SelectDWGlink.jpg" alt="View Templates" width="500">

7. Now, what you see is the list of all AutoCAD blocks which you had in your DWG file. Select AutoCAD blocks which you need to place a Revit family in exchange of them.

<img src="https://pars-bim.github.io/docs/Assets/Selectblocks.jpg" alt="View Templates" width="500">

8. Next, you can assign a Revit family to each CAD Blocks that you have picked. First select the category and then select the approperiate Revit family to be placed.

<img src="https://pars-bim.github.io/docs/Assets/Assignrevitfamily.jpg" alt="View Templates" width="500">

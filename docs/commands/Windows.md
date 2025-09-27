---
title: Convert CAD windows to Revit windows
---

# Convert CAD windows to Revit windows
This command helps you to convert a AutoCAD windows into Revit windows.



1- Click on "windows" and then, from the provided list, select the widths detected by the plugin that correspond to the actual window widths in the project, and uncheck any unnecessary widths. You can also place windows by detecting AutoCAD blocks (continue at step 4).

<img src="https://pars-bim.github.io/docs/Assets/Review-window-width.jpg" alt="Select levels" width="500">

2- Assign window types to each detected window width from CAD file.

<img src="https://pars-bim.github.io/docs/Assets/windowtype.jpg" alt="Select levels" width="500">

3- Set the level and sill height for windows.

<img src="https://pars-bim.github.io/docs/Assets/Windowplacement.jpg" alt="Select levels" width="500">

4- If you want to place windows by detecting AutoCAD blocks, click on "From AutoCAD blocks".

5- Since Revit can not read AutoCAD blocks definitions, we need to export AutoCAD blocks coordinates from AutoCAD it self. To do this click on "Export lisp" and save it on your computer.
   It doesn't matter where you save it.
   the recommanded address is: C:\Program Files\Autodesk\AutoCAD [version]\Support
   
6- Then open the AutoCAD and your project. Type Appload in the command bar.

<img src="https://pars-bim.github.io/docs/Assets/Appload.jpg" alt="Select levels" width="500">

7- Select the exported file and load it. By default its name is: "ExportBlockCenters.lsp"

<img src="https://pars-bim.github.io/docs/Assets/load-exportblockcenters.jpg" alt="View Templates" width="500">

8- Type "EXPORTBLOCKCENTERS" in AutoCAD command bar and press "Enter". Then save the exported block coordinates where ever you want on your computer.

<img src="https://pars-bim.github.io/docs/Assets/save-exportblockcenters.jpg" alt="View Templates" width="500">

9-  Now you can import exported CSV file into the Revit. AutoCAD Block centers are exported in two ways. By geometry centers or by insertion point. Insertion point is the origin of the AutoCAD Block and it is depended on where it is defined by its creator and Geometry center is the center of the geometry. In fact center of its bounding box.
Also, you can define CSV unit in Revit.

<img src="https://pars-bim.github.io/docs/Assets/importCSV.jpg" alt="View Templates" width="500">

10- Now, what you see is the list of all AutoCAD blocks which you had in your DWG file. Select AutoCAD blocks which you need to place a Revit family in exchange of them.

<img src="https://pars-bim.github.io/docs/Assets/Windowblocks.jpg" alt="View Templates" width="500">

11- Next, you can assign a Revit family to each CAD Blocks that you have picked. First select the category and then select the approperiate Revit family to be placed.

<img src="https://pars-bim.github.io/docs/Assets/Assignwindowtype.jpg" alt="View Templates" width="500">

12- Set the level and sill height for windows.

<img src="https://pars-bim.github.io/docs/Assets/Windowplacement.jpg" alt="Select levels" width="500">


Here is the short video to show the process:

<iframe width="560" height="315" src="https://www.youtube.com/embed/IVCwYGVDcpM?si=SECx9WInasZ4mhrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

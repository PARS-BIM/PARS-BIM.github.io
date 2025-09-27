---
title: Convert CAD doors to Revit doors
---

# Convert CAD doors to Revit doors
This command helps you to convert a AutoCAD doors into Revit doors.


1- Click on "doors" and then, from the provided list, select the widths detected by the plugin that correspond to the actual doors widths in the project, and uncheck any unnecessary widths. You can also place doors by detecting AutoCAD blocks (continue at step 4).

<img src="https://pars-bim.github.io/docs/Assets/Review-door-width.jpg" alt="Select levels" width="500">

2- Assign door types to each detected door width from CAD file.

<img src="https://pars-bim.github.io/docs/Assets/Assigndoortype.jpg" alt="Select levels" width="500">

3- Set the level for doors and select ok.

<img src="https://pars-bim.github.io/docs/Assets/Doorlevel.jpg" alt="Select levels" width="500">

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

<img src="https://pars-bim.github.io/docs/Assets/Doorblocks.jpg" alt="View Templates" width="500">

11- Next, you can assign a Revit family to each CAD Blocks that you have picked. First select the category and then select the approperiate Revit family to be placed.

<img src="https://pars-bim.github.io/docs/Assets/Doortypes.jpg" alt="View Templates" width="500">

12- Set the level for doors and select ok.

<img src="https://pars-bim.github.io/docs/Assets/Doorlevel.jpg" alt="Select levels" width="500">


Here is the short video to show the process:


<iframe width="728" height="410" src="https://www.youtube.com/embed/JF1E3CHNmW8?si=D6dK9A_7H6fD0kxV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---
title: Line to pipe
---

# Line to pipe
With this command, you can convert Model Lines or lines imported from AutoCAD files into pipes with the specifications of your choice.

## Steps
To use this command, first go to the “Pars-BIM” tab, then in the MEP panel, from the “Pipes conduits” section, select the “Line to pipe” command.

Then, In the opened window, first define the desired pipe properties, including Pipe Type, System Type, Size, and the pipe elevation relative to a specified level.

Please note that the elevation value entered in the Elevation field uses the same units as the project's length units defined in Project Units. This value represents the offset from the Reference Level, which must be selected in the section below.

Also, please note that if the Middle Elevation option is enabled, the value entered in the Elevation field will be applied as the distance from the specified level to the centerline of the pipe.

If the Upper End Top Elevation option is enabled, the value entered in the Elevation field will represent the distance from the specified level to the top of the pipe.

Finally, if the Lower End Bottom Elevation option is enabled, the entered value will represent the distance from the specified level to the bottom of the pipe.

After defining the pipe properties, click the button in the Pick Lines column to select one or more lines in the active project view.

If you later need to add more lines to your selection, use the “+” button in the corresponding row. Likewise, if you want to remove a line from the selection, use the “-” button in that row and select the line in the active view that should be removed.

To verify which lines belong to each row, you can click the eye icon. This will highlight and display the associated lines in the project for easier identification.

Using the "Add Row" and "Duplicate Row" buttons, you can create additional rows for selecting lines and converting them into pipes with different properties.

"Add Row" creates a new row with default settings at the end of the list.
"Duplicate Row" creates a copy of the selected row (by default, the last row is selected) with the same settings, allowing you to make only minor adjustments instead of starting from scratch.

Finally, click OK to confirm your settings. The pipes will then be created and modeled according to the specified properties.

<img src="https://pars-bim.github.io/docs/Assets/Line-to-pipe.jpg" alt="Line to pipe" width="300">

If you want to convert lines from an AutoCAD file linked to the model into pipes, simply click the “Select from DWG” button first. In the opened window, select the layers that you want to be temporarily enabled for selection.

<img src="https://pars-bim.github.io/docs/Assets/Select-Layers.jpg" alt="Select CAD Layers" width="600">



Here is the short video to show the process: 

<iframe width="560" height="315" src="https://www.youtube.com/embed/77OBmAt6CIw?si=X7bn4KUL0ExHs0Ji" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

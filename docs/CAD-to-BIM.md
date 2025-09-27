---
title: CAD to BIM
---

# CAD to BIM
This command helps you to convert a AutoCAD architectural drawings into BIM model much faster than before.

## Steps
1- To use this command first you need to link at least one DWG file into Revit (You can also do it on more than one file at once). 
2- In the ribbon click on "PARS-BIM" tab and in "Architectural tools" panel click on "CADtoBIM" from "Auto modelling" dropdown button.
3- Select DWG files that need to be converted from the list.

<img src="https://pars-bim.github.io/docs/Assets/SelectDWG.jpg" alt="Select levels" width="500">

4- Next, assign each CAD layer to approperiate Revit category. 

<img src="https://pars-bim.github.io/docs/Assets/MAPCADLayers.jpg" alt="Select levels" width="500">

5- Then, if you want to convert walls, click on "Walls", and if you want to convert doors or windows, click on "Doors" or "Windows" button.
6- Click on "Walls" and define walls thickness range in the drawing. For example if you have 10 cm and 15 cm and 20 cm wall types in the drawing, your range will be from 10 cm to 20 cm.

<img src="https://pars-bim.github.io/docs/Assets/Wallrange.jpg" alt="Select levels" width="500">

7- The program will detect wall thicknesses from the AutoCAD drawings automatically. You can review detected thicknesses and uncheck unnecessary thicknesses from the list.

<img src="https://pars-bim.github.io/docs/Assets/Reviewthickness.jpg" alt="Select levels" width="500">

8- Assign wall type to each detected wall thicknesses. If your walls are same but in different thicknesses, you can select "Default wall type" and click on "Create for all" to duplicate from the default and assign them to each thickness automatically.

<img src="https://pars-bim.github.io/docs/Assets/Selectwalltype.jpg" alt="Select levels" width="500">

9- Define wall settings for each level that you had linked your DWG files to it and press ok.

<img src="https://pars-bim.github.io/docs/Assets/Placementoption.jpg" alt="Select levels" width="500">

Since each design has its unique specifications and some limitations on converting, some minor modifications and edits are inevitable. 

Here is the short video to show the process:

<iframe width="560" height="315" src="https://www.youtube.com/embed/7sJyyTMciEw?si=tG60tDsUdXCKLCt5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


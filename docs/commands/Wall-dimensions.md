---
title: Wall dimensions
---

# Wall dimensions
With this feature, you can create wall dimensions **much faster and more easily**, saving time and streamlining your modeling workflow.

## Steps
1- Select PARS-BIM tab then in the "Architecture" panel and under the "Magic dimension" dropdown bottun click on "Wall dimensions"

<img src="https://pars-bim.github.io/docs/Assets/Wall-dimensions-setting.png" alt="Wall-dimensions-setting" width="500">

In the opened window, you can customize the settings based on how you want the dimensions to be placed.

### 1. Dimension Style

In this section, you can select which **Dimension Style** should be used for the wall dimensions.

### 2. Apply to All Rooms or Selected Rooms

Here, you can choose whether to apply the dimensioning settings to **all rooms at once**, or only to the specific rooms you select.

### 3. Dimension Placement

In this section, you can define whether the dimensions should be placed **inside or outside the rooms**. You can also specify the distance between the dimensions and the walls.

### 4. Wall Dimension Reference

Here, you can choose whether the dimension reference for walls should be based on the **wall face** or the **wall centerline**.

### 5. Options for Better Dimension Display

**Option 1: Include Openings**
You can choose whether openings should be included in the dimensions. If enabled, you can specify whether you want to display the **opening width** or the **distance to the center of the opening**.

**Option 2: Display Intersecting Wall Widths**
You can choose whether the widths of intersecting walls should be included in the dimensions. If enabled, you can define a thickness range of walls to ignore for a cleaner result. For example, you can exclude **finish walls thinner than 4 cm**.

### 6. Finish Wall Detection Filter

This section allows you to define the **wall thickness range** that the plugin should recognize as finish walls.

You can also specify **which face of the finish wall** should be used as the dimension reference. This setting is used by the **“Interior Walls”** button.

Now, let’s explain what each of the buttons at the bottom does:

* **Just Openings:** When you click this button and then select a wall, the plugin will place only the dimensions related to the **openings** in that wall.

* **Interior Walls:** By selecting a room, this option creates the room’s dimensions based on the **face of its finish layer**.

* **Chain Walls:** Sometimes, several intersecting but continuous and aligned walls are present. This feature allows you to create a **single dimension representing the combined length of those walls**.

* **Wall Dimensions Individually:** With this button, you can place dimensions only for the **walls you select**.

* **OK:** Based on the settings you have configured, this button creates wall dimensions for **all rooms or only the selected rooms**, depending on the option chosen in **Setting 2**.



Here is the short video to show the process: 



<iframe width="560" height="315" src="https://www.youtube.com/embed/qKOYtZqjufc?si=dKCVFOYE0WjCm246" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

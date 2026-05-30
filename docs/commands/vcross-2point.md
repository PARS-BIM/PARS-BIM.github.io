---
title: Vertical cross - 2 point (Cross and keep elevation)
---

# Vertical cross - 2 point (Cross and keep elevation)
With this command, you can easily resolve clashes between two elements without the need to create additional sections or use cutting and remodeling tools.

## Steps
First, select the element where you want the break to occur and that should pass over the obstructing element. Then specify the two points that define the break locations.

In the opened window, you have two options. If you want to select an entire element as the obstacle, click “Select Element”. If you prefer to define the crossing logic based on a surface, choose “Select Face”.

Why is the “Select Face” option useful?

Sometimes the obstruction comes from a linked file—for example, a structural beam linked into the MEP model. In such cases, you cannot use the “Select Element” option. Instead, by selecting a face of the linked element (such as the underside of the beam), you can define the crossing logic and control how the elements pass through each other.

<img src="https://pars-bim.github.io/docs/Assets/Secondary-selection.jpg" alt="select element" width="500">

In the opened window, first specify whether you want to pass over the obstruction or under it. To do this, select either “Over” for passing above or “Below” for passing underneath the obstacle.

Next, define which part of the broken element the distance specified in the “Offset” field should be measured from. For example, you may set the distance from the top of the upper segment of the broken element to the bottom of the obstacle to be 100 mm (as shown in the image).

Finally, specify the angle at which the offset and the elbows should be created. If you select “Custom”, you can manually enter the desired angle value.

Please note that if you selected “Select Face”, the offset of the broken element (top, center, or bottom) will be measured relative to the selected face.
For example, the distance from the top of the broken duct to the bottom of the beam.

<img src="https://pars-bim.github.io/docs/Assets/Vertical-cross-options.jpg" alt="Vertical cross options" width="500">

Here is the short video to show the process: 

<iframe width="560" height="315" src="https://www.youtube.com/embed/NHrXwXIbRTk?si=FGm2Ev0-Qg0jw0xh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

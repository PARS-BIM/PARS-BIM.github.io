---
title: Multiple conduits
---

# Multiple conduits
With this command, you can model any number of electrical conduits simultaneously, each with its own unique specifications.

## Steps
To use this command, first go to the “Pars-BIM” tab, then in the MEP panel, from the “Pipes conduits” section, select the “Multiple conduits” command.

Then, in the opened window, first specify the number of conduits you want to model simultaneously.

<img src="https://pars-bim.github.io/docs/Assets/Multiple-conduits-counts.jpg" alt="Multiple conduits counts" width="300">

Then, in the opened window, specify the properties of each conduit individually. Note that the arrangement of conduits in the project is from top to bottom and from right to left. This means that the properties in the top row will be applied to the rightmost modeled conduit.

For each conduit, you can separately define its conduit type, Service Type, and size.

Also, in the lower section, specify the elevation of each conduit relative to a selected Level. At this stage, you also have the option to align the conduits based on their center, top, or bottom elevation.

<img src="https://pars-bim.github.io/docs/Assets/Multiple-conduits-specs.jpg" alt="Multiple conduits specs" width="600">

In the next step, you can define the spacing between the conduits. You have two options:

Center-to-Center:
This defines the distance between conduits from their centerlines.

Edge-to-Edge:
This adjusts the spacing based on the outer edges of the conduits, aligning them side by side.

<img src="https://pars-bim.github.io/docs/Assets/Multiple-conduits-spacing.jpg" alt="Multiple conduits spacing" width="300">

After defining the spacing between the conduits, you must specify the modeling path using a reference line. Once you finish drawing the reference line, press the Esc key twice to fully exit the line-drawing mode, and then click the “Finish” button to apply the modeling.

Make sure to draw a single continuous and connected path, and avoid creating multiple separate segments.

<img src="https://pars-bim.github.io/docs/Assets/Multiple-conduits-routes.jpg" alt="Multiple conduits routes" width="600">

Finally, you will see that your conduits have been modeled along the desired path, with the spacing you defined, both relative to each other and to the specified elevation level.



Here is the short video to show the process: 

<iframe width="560" height="315" src="https://www.youtube.com/embed/1VLcuH4NAOI?si=kpMC6CMe91ZGb0Gl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

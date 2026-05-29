---
title: Add to accessories
---

# Add to accessories
This command helps you overcome one of Revit’s annoying bugs and also allows you to model faster. For those who model piping—especially when working on mechanical rooms—it often happens that after adjusting the length of a pipe connected to a valve and a flange, the flange connected to the valve is immediately deleted. As a result, you are forced to fix the model again.

This command allows you to quickly reconnect or add the flange—or any required fitting or accessory—to the target fitting or accessory.

## Steps
In the opened window, you can first specify whether you want to work with pipes, ducts, or both. Simply activate the checkbox of each category you need.

Next, depending on which rule you want to use for executing the command—listed at the bottom of the window—you will need to adjust the related settings.

– Select in view:

In this mode, you no longer need to specify the accessories or fittings in the upper rows under “Source types,” because you will select them directly in the active project view.

So, you only need to use the “Insert type” section to determine which element should be added to the selected fittings or accessories.

As you can see, this list is organized into two tabs—one for accessories and one for fittings—to make it easier for you to find the element you need, with better categorization. A search function is also available.

After choosing the desired accessory or fitting, click “Select in view.” You will be taken to the active project view, where you can select the fittings or accessories that should receive the inserted element.

<img src="https://pars-bim.github.io/docs/Assets/Choose-accessories.jpg" alt="Select levels" width="800">

– All in active view:

If you click this option, the plugin will automatically find all the relevant fittings or accessories for you and add the selected fitting or accessory to them within the active view.

To do this, in addition to specifying in the “Insert type” section which fitting or accessory should be added, you must also define in the “Source types” section which valves or accessories should receive the added element.

For example, you can specify that all Gate Valves in the active view should have a flange added to them.

– All in project:

This option works the same way as “All in active view,” with the difference that it applies the operation to the entire project.

Here is the short video to show the process: 



<iframe width="560" height="315" src="https://www.youtube.com/embed/sNX78WqNPVo?si=D3sj6OwjI37jUPOd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

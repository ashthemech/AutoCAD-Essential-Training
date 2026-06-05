# AutoCAD 2026 Essential Training 
This repository documents my personal learning journey using an AutoCAD LinkedIn Learning course using the AutoCAD 2027 15 day trial.

**Disclaimer**: I do not own the copyright to the course videos or original exercise files. All rights belong to LinkedIn Learning and Shaun Bryant. 
**Repository Content**: The files in this repository are **my own practice drawings and notes** created while following the course. They are shared here to demonstrate my progress and understanding of AutoCAD.

The content below represents my personal notes and summaries derived from the LinkedIn Learning course "AutoCAD 2026 Essential Training" by Shaun Bryant. All original course materials (videos, exercise files) are copyright of LinkedIn Learning and are not included in this repository. The course is linked below, note that it requires authorization to access via membership.

[AutoCAD 2026 Essential Training course by Shaun Bryant](https://www.linkedin.com/learning/autocad-2026-essential-training)

### Course Learning Outcomes

<details>
<summary> 1. Introduction </summary>

Key Takeaways:

* Develop and visualize designs in 2D and 3D.
* DWG file format is recognized globally.
* Has mechanical, electrical, and architecture toolsets.
* AutoCAD interface breakdown repeated here- application menu, quick access toolbar, info bar, etc.
  
</details>

<details>
<summary> 2. The AutoCAD Interface </summary>

Key Takeaways:

* Revisited the Application Menu and its functions.
* Dove deeper into the info bar and the QAT.
* Learned the ribbon panels can be placed in the drawing area by holding and dragging them.
* Learned how to set and save custom workspaces using the status bar.
* Learned about the command line and its purposes and use cases.
* Learned about accessing the drafting settings form the status bar.
* Learned about the newer menu tools in recent versions of AutoCAD on the left of the interface.

<details>
<summary> Interface.dwg - AutoCAD Interface </summary>

  > Interface.dwg is the same office floor plan used in the previous course, "Learning AutoCAD 2026".

  **Using the Application Menu**
  * The application menu is consistent across AutoDesk software, not just AutoCAD.
  * Printing is fundamental in AutoCAD, most most commonly it is now in electronic formats.

  **Using the Info Bar**
  * You can use the info bar to search terms or functions in the "help" menu.
  * The help menu bar also allows you to download an offline version of the helper- i.e. on-site reference.
  * AutoCAD also has an AI assistant, search functions, workflows, or support help.

  **Using the Quick Access Tool Bar**
  * The QAT can be customized as well for commands that are used frequently.
  * Set the Layer toolbar to be accessible through the QAT.

  **Using the Ribbons & Panels**
  * The panels can be dragged out and placed in the drawing area by holding and dragging on their titles, and they remain in the drawing area if you go to another ribbon.

  **Customizing the Interface**
  * Done using "AutoCAD Workspaces".
  * I took the Draw and Modify panels and stuck them to the left hand side of the drawing space.
  * Went to the status bar and saved this workspace as "ALC - AutoCAD", which saves these settings in that workspace.
  * Note, the QAT will keep the same settings across workspaces.

  **Using Palettes and Dialogue Boxes**
  * Review of the palette properties.
  * Review of the properties of dialogue boxes.

  **Using the Command Line**
  * By default at the bottom of the screen.
  * Can type a word into the command line and it will pop up with functions that have that word in them.
  * The command line will show you a history of the commands used, can be used to see edit history.
  * Can configure the command line with the wrench to the left.
  * Keep an eye on the command line, might have numbers or variables that are helpful.

  **Using DYNMODE**
  * Review of toggling dynamic input on and off, and how to use it.
  * You can open the drafting settings by right clicking on the dynmode input on the status bar.

  **Using the Status Bar**
  * Midpoint OSNAP is not on by default, but is very common and good practice to keep on.
  * You can right click any of the status bar icons to access the Drafting settings for each icon.

  **Using Your AutoDesk Account**
  * Need a subscription to access your AutoDesk software and ensure licenses.

  **Navigating Model and Paper Space**
  * The last few versions have distinct tab tools on the three lines to the upper and lower left.
  * Allow you to navigate and access helpful functionality in the interface.
  
</details>
</details>

<details>
<summary> 3. Using Units and Options </summary>

  Key Takeaways:
  * How to set the units and the different types of units available.
  * How to access the options dialogue box and the different settings.
  * How to work with metric units and imperial units when drawing.
  * How to save a template file and open a new drawing from a template. 

<details>
<summary> Units&Options.dwg - How Units & Options are used and configured </summary>

  > Units&Options.dwg is the same office floor plan used in the previous modules.

  **Setting Units**
  * How do we switch on units, set units, and display units?
  * The quickest way is to type "units".
  * There are a few different types of units, architectural, engineering, decimal, etc. and you can get up to 8 points of precision.
  * Can check if the settings are set how you want by checking the coordinates in the drawing, accessed via the status bar.

  **Setting Options**
  * Quickest way to get to the options menu is use the context shortcut menu (right click).
  * Files - all of the install files in AutoCAD, only one to really worry about is the automatic save file location (ideally a cloud based folder).
  * Display - changes how various things are displayed in AutoCAD, like color, resolution, layout, and window options.
  * Lots of other options to explore- User Preferences: Insertion Scale - source units vs target drawing units, can automatically scale!

  **Working with Metric Units**
  > NEW FILE! Units-METRIC.dwg is the same office floor plan used in the previous modules.
  * We are going to draw some lines in the central part of the office floor plan.
  * The "Specify first point" is on due to DYNMODE being on, and in this drawing it is in metric mm.
  * Drew a simple rectangle using polar tracking and OSNAP using metric units.

  **Working with Imperial Units**
  > NEW FILE! Units-Imperial.dwg is the same office floor plan used in the previous modules.
  * This floor plan uses imperial units in feet and inches and in the architectural setting in the units options.
  * The biggest difference here is when specifying the length, there is an expected syntax, need to type like you are writing it out ex. 8'-6".
  * Drew a rectangle in imperial units using the new syntax of 8'-6" and 4'-2".

  **Working with Templates using DWT Files**
   > NEW FILE! SimpleTemplate.dwg is a file with a blank model tab and a simple ISO A3 Landscape with a title block.
  * Sometimes you want to have a group of settings in a drawing file that are standard, i.e. layers, unit settings, etc.
  * Need to save those settings to a template file (.dwt).
  * Using the template file, we have a few layers here (centerlines, text, titleblock, etc) and units set to metric.
  * Going to the quick access toolbar and hitting the "Save As". Changing to save as a .dwt takes the template to the default "Template" folder.
  * Hitting save prompts a template options dialogue box where you can add a description, measurement, and layer notifications.
  * Now, creating a new drawing file from that template - going to "new" and using the template folder, and opening the saved SimpleTemplate.dwt generates a new drawing with those settings preloaded.
  

</details>
</details>

<details>
<summary> 4. Navigating Drawings </summary>

  Key Takeaways:
  * Reviewed zooming and panning.
  * Reviewed model space vs paper space.
  * Learned how to save and access save views, as well as their usefulness.
  * Explored mouse click settings.
  * Learned how to navigate a 3D object model.

<details>
<summary> 00-GND Floor Plan.dwg - Navigating in Drawings </summary>
 > 00-GND Floor Plan.dwg is the same previous office building layout in the previous modules.

  **Zoom and Pan**
  * Review of zooming and panning in AutoCAD.
  * Double clicking on the mouse wheel zooms to the extent of the visible drawing.
  * Can also be done on the navigation bar or the shortcut menu.

  **Working in Model and Paper Spaces**
  * Everything done in the model tab is full size- its model space is infinite in the x and y.
  * Need the full size floor plan (30 m x 30 m) onto a piece of paper to communicate the design intent into the layout tab (paper space).
  * To do this, there is an aspect ratio - i.e. in this case a 1:100 so the model fits on the sheet of paper.

  **Saving and Restoring Views**
  * Can save different views, called "named views" in AUtoCAD.
  * The workflow for this depends on the version of AutoCAD you are using (2013 and above).
  * View tab on the ribbon and go to the "view manager" in the named view panel.
  * Also in the view controls in the upper left of the drawing.
  * We will create a large conference room view, and a restroom view.
  * View Manager -> Model views -> New -> has options for name, category, and type.
  * Note to expand the box and make sure the Save layer is checked- this saves the current layer visibility settings.
  * Created one called "Restrooms" as a 2D Plan, and used "define window" to create a bathroom view.
  * Repeated the process for the conference room, and explored named view panel to see the utility.

  **Mouse and Mouse Settings**
  * The right click is context sensitive, i.e. if you have the cursors in the drawing vs actively sketching a line.
  * Can set mouse settings in options to change the default commands, like having "enter" on the keyboard be the "close" command for lines via "time-sensitive right click".
  * Did this and played around with the quick click vs long click.

  **ViewCube and Nav Bar**
   > NEW FILE! Simple3DObject.dwg is a 3D object that looks almost like a 2x1 lego flat brick with one longer cylinder on top.
  * Can change the visual style of the 3D object via the view settings in the top left model tab.
  * Can use the top right compass cube to switch between views quickly.
  * Can set a "home" view that will take your back to your preferred view when clicking the house icon.
  * Navigation wheel can also be pulled out from the right side of the bar, but need to click and gold.
    * Orbit allows a 3D pan.
  
</details>
</details>

<details>
<summary> 5. Drawing Accurately </summary>

  Key Takeaways:
  * bueelt

<details>
<summary> DrawingAccurately.dwg - Drawing in AutoCAD </summary>
 > DrawingAccurately.dwg is a blank drawing file to work with.

  **Using Grid and Snap**
  * Grid and snap is controlled on the status bar.
  * Configured the grid settings and grid snap settings, and [drew some practice shapes]() to get the feel for it.


</details>
</details>

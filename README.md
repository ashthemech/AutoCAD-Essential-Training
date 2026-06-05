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
  * ag
<details>
<summary> 00-GND Floor Plan.dwg - Navigating in Drawings </summary>
 > 00-GND Floor Plan.dwg is the same previous offic building layout in the previous modules.

  **Zoom and Pan**
  * Review of zooming and panning in AutoCAD.
  * Double clicking on the mouse wheel zooms to the extent of the visible drawing.
  * Can also be done on the navigation bar.

  
</details>
</details>

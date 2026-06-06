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
  * Learned how to use the Grid and Snap functionality.
  * Used coordinates to draw a simple rectangle.
  * Used DYNMODE to draw a simple rectangle with polar tracking off.
  * Used DDE and polar tracking to draw the simple rectangle, fastest method.

<details>
<summary> DrawingAccurately.dwg - Drawing in AutoCAD </summary>
 > DrawingAccurately.dwg is a blank drawing file to work with.

  **Using Grid and Snap**
  * Grid and snap is controlled on the status bar.
  * Configured the grid settings and grid snap settings, and [drew some practice shapes](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/6fba188aa26534e841c9be08e6ff297a2473b512/Drawing%20Accurately/Grid%20Settings.JPG) to get the feel for it.

  **Using Coordinates**
  * How to draft using coordinate entry.
  * Now using the line command in the draw panel and hitting @, it prompts us for the coordinates instead of the length.
    * Entered 250,0 so our box through the circle is 250 in the x and 0 in the y for the first line.
    * Repeated this process to copy the previous box this time with the [corner in a circle](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/4323d413b86f040f04d25558249a5cad50866c9e/Drawing%20Accurately/Using%20Coordinates%20to%20Draw..JPG).
  * Can also use the "tab" key to achieve this.
  * @ symbol is used for relative coordinates (relative to last points selected), # symbol for absolute coordinates (relative to (0,0)).

  **Using DYNMODE**
  * Can also use dynamic input to draw the rectangle.
    * Here, need to enter the relative distance and the angle- but note no negatives here, the cursor must be in the general direction you want to draw.
  * Drew the standard 250mm by 150mm rectangle, the same as the last two sections.

  **Using Direct Distance Entry**
  * Drew the exact same rectangle as the previous sections, this time using DDE and polar tracking.
  * Main difference here, is that with polar tracking on and set to 90 degrees, its easy to type in the preferred distances and use the green polar tracking line.
  * Also way quicker than the other methods above.

</details>
</details>

<details>
<summary> 6. Simple Geometry: The Basics </summary> 
  
  Key Takeaways:
  * Reviewed OSNAP and AUTOSNAP to create a rectangular table with 3 different methods.
  * Reviewed using POLAR and ORTHO for drawing the rectangular table.
  * Reviewed using lies, arcs, and circles by making a landscape area and creating a rounded rectangular table.
  * Reviewed using polylines and splines by recreating the rounded table and creating a dividing wall.
  * Reviewed using offset, extend, and match properties tools on the dividing wall.

<details>
<summary> GND Floor Plan.dwg - Basics of Simple Geometry </summary>
 > GND Floor Plan.dwg is the same previous office building layout in previous modules.

  **OSNAP and AUTOSNAP**
  * Going to draw some furniture here, so I made sure I had the furniture layer selected (A-700-M_FFE).
  * Used the rectangle tool to draw a 3500mm by 2500mm table.
  * Now, using 3 different ways to draw a circular insert on the table I just drew - first using the simplest method.
    * Used the line tool to divide the table into [2 triangles](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/f49831615a64033b9f0e10f9897b4fe2f090501e/Simple%20Geometry%3A%20The%20Basics/Table%20into%20Triangles.JPG).
    * Used the midpoint snap of the intersecting line to [insert a circle](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/71445037d961300dc98faec79319f956ec866cfc/Simple%20Geometry%3A%20The%20Basics/Table%20with%20Triangles%20and%20Circle%20Insert.JPG) of radius 900 using circle, radius command.
    * Then erased the intersection line, leaving just the [circular insert in the table](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/a83956935a17019a677b6c87ede5a516ff50daa0/Simple%20Geometry%3A%20The%20Basics/Table%20with%20Circle%20Insert%20Method%201.JPG).
  * Next method will be using the AUTOSNAP tool.
    * Erased the circle from the previous method, leaving just the table.
    * Used the midpoint of the width and length of the table to find the center of the table with [AUTOSNAP and polar tracking](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/bbb43524d142a8aaaba9ea8d859052a16e0cafe6/Simple%20Geometry%3A%20The%20Basics/Midpoint%20AutoSnap.png).
    * Entered the radius of 900, and had the [insert added into the table](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/6ab00c218ce63f4986621558b24c06115d901c58/Simple%20Geometry%3A%20The%20Basics/Table%20with%20Circle%20Insert%20Method%202.JPG).
  * The last method used ObjectSnap, since the table is closed polyline it has a midpoint of its own.
    * Using the radius, center tool and hovering in the middle of the table we can shift right click to bring up the snap override menu.
    * Then, can select geometric center and hover on one of the lines of the table that will highlight the [center of our table](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/d1c0c8a9cd1462af375c074c48909de02049dc3f/Simple%20Geometry%3A%20The%20Basics/Geometric%20Center%20ObjectSnap.png).
    * As in the previous steps, enter 900 for the circle's radius and we again have our table with the [circular insert](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/73d8dec8ab8122518b7e2286e1f77bba92f7427b/Simple%20Geometry%3A%20The%20Basics/Table%20with%20Circle%20Insert%20Method%203.JPG).

  **POLAR and ORTHO**
  * In the same layer, we are drawing the table again but using different tools.
  * We will draw the table using a [closed polyline](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/7e244db35b9ec854d41c35517d0b72c50f880bef/Simple%20Geometry%3A%20The%20Basics/Polyline%20and%20Polar%20Tracking.png) instead of the rectangle tool, with polar tracking set to 90 degrees.
  * Polar tracking can also be set to specify specific angles in the settings (i.e. additional angles, 67 degrees - ONE additional angle, not increments of 67).
  * Another way to draw the table is to use orthogonal tracking.
  * Turning polar off ans switching orthagonal on, which [limits the cursor to horizontal and vertical lines](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/83ccdbb2a044ca4264687abc099e13f7592202ee/Simple%20Geometry%3A%20The%20Basics/Orthoganal%20Tracking.png).

  **Creating Lines, Arcs and Circles**
  * Changed the layer to L_910-M_SITE to place a rectangular group of site lines for a landscaping area.
  * Used the [line tool and intersection snapping](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/a7ce5957bdbd30a2eb69a0dc18fba3b6b9ac4ee4/Simple%20Geometry%3A%20The%20Basics/Intersection%20Snapping.png) to outline the [borders of the landscaping area](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/3e7a33af322399482c828dd456b8f2513d08cd71/Simple%20Geometry%3A%20The%20Basics/Boundary%20of%20the%20Landscape%20Area.JPG) outside of the office.
  * Going back to the furniture layer (A-700-M_FFE) to add some arcs to our table.
    * What happens if you click the start, center, end arc tool in the wrong order i.e. clockwise? - hit the "undo" and redraw the arc.
    * BUT, if you are drawing the arc, you can use CTRL to switch the direction.
  * Made the table with arcs, but the [rectangle is still one object](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/946816a64fabe223a978a9db52ef13973a7625a2/Simple%20Geometry%3A%20The%20Basics/Table%20with%20Arcs.JPG) - can fix that using modify - explode, which breaks that polyline object into its coponents.
  * This makes it possible to delete the two vertical lines, so we now have an [oval-ish table](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/0ef816dd8665806dc6d01c1204ee64f43164c1c9/Simple%20Geometry%3A%20The%20Basics/Oval%20Style%20Table.JPG).
  * Note that the circular tool remembers the default of the last circle you made- i.e. our circle of radius 900, when using say diameter, center will default to 1800.
    * Very fast method if you have lots of circles with the same diameter.

  **Creating Polylines and Splines Quickly**
  * First, we will make a fully closed polyline that contains line and arc segments.
  * To do this, I used the polyline command starting with a line at 3500 mm, then right clicked to change it to an arc of 2500 mm in length, and repeated for the bottom and left.
  * Then added the circular insert with a radius of 800 mm, and [table was created again](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/5ad71b2906e2617358414a3d6e1aa5264af35b2b/Simple%20Geometry%3A%20The%20Basics/Closed%20Polyline%20Table%20with%20Circular%20Insert.JPG).
  * Now moving over to the walls, but we will stay in the same layer for now using the spline command.
  * Used the spline fit tool to create an irregular curve to seperate the [stairs and the seating](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/ea8a06ebd114fe63b1fb82fa32fa509337001b65/Simple%20Geometry%3A%20The%20Basics/Stair%20and%20Seating%20Spline%20Fit.JPG).
  * Then, I offset it to give it a thickness by using the "measure" tool to measure the walls thinckness, then used [offset to match the wall thickness](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/87a515814ba391841e96a2865da9f8a89be12dfc/Simple%20Geometry%3A%20The%20Basics/Offset%20Spline%20Wall.JPG) of 120.65mm.
  * Then I used the [line and extend command](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/00a29068999e914e6bbe4ccabfc74db88b6b7509/Simple%20Geometry%3A%20The%20Basics/Line%20and%20Extend%20on%20Spline%20Wall.JPG) to close the left side of the wall and extend the lower segment to the rest of the wall.
  * Finally, used the "Match Properties" tool to match the new spline wall to the proper layer of the [existing walls](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/24839c3094a3457cfdbe143fbb6e3045e42e2a3d/Simple%20Geometry%3A%20The%20Basics/Layer%20match%20of%20Spline%20Wall%20to%20Wall.JPG).

</details>
</details>

<details>
<summary> 7. Other Drafting Tools </summary>  
  
  Key Takeaways:
  * Reviewed creating rectangles and polygons by creating two tables in the landscape area.
  * Learned how to create setting out points using layers by creating bike bays in the landscape using the divide and copy functions.
  * Learned how to make a setting out point highlight by using the donut tool.
  * Learned how to create ellipses by creating an isomatric representation of a cylinder.
  * Learned how to use ISODRAFT to create isometric models by completing an isometric rectangle.

<details>
  <summary> GND Floor Plan_REV2.dwg - More Drafting Tools </summary>
   > GND Floor Plan_REV2.dwg is the same previous office building layout in previous modules, with some added furniture in the previously empty rooms.

  **Creating Rectangles and Polygons Quickly**
  * Going to the landscape now, and checking I am in the furniture layer (A-700-M_FFE).
  * Using the create rectangle tool and selecting a spot in the landscape, then right clicking the mouse I hit dimensions.
  * I entered 3500 mm for the width, and 2500 mm for the height, and explored the way the rectangle can be rotated about the initial selection point.
  * Then, I placed a circle in the top left area of the landscape to use as a guide to create an octagon.
  * Selected polygon draw tool, specified 8 sides, then chose circumscribed about the circle, and used Autosnap to [size it to the circle](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/f8b37c994b77c782394a25107e3a71b4056ebdf9/Other%20Drafting%20Tools/Octagon%20Table.JPG).
  * Then, deleted the circle to have just the octagon remaining.

  **Creating Points and Donuts as Reference Points**
  * Going to make some bike bays in the landscape area for people to bring their bikes.
  * Layers panel - layer properties, where we want to create 2 new layers.
    * Bike Bays layer in magenta.
    * Bike Bays-SO Points (setting out points) also in magenta.
  * Need to set a point style now, using utilities flyout and opening the point styles dialogue box.
    * Selected the circle with the diagonal crosshair.
  * Now in the draw panel, selected Multiple Points - but using this would require measuring and dividing by a calculator, so instead we can use the "Divide" option.
    *Using divide, I selected the right side of the landscape boundary and entered 10 for 10 [bike bay points](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/51de4b058d2d32788a9466f8d467e39826960e2f/Other%20Drafting%20Tools/Bike%20Bay%20Points%20using%20Divide.JPG).
  * Then, zooming out I tried the "REGEN" command, and saw the bike bay points resize to the 5% of screen size based on the settings for the bike point layer.
  * Now in the Bike Bays layer, I turned node snapping on to create a 4 m long line on the top bike bay point. Then, I used copy selection and filled in the [remaining bays](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/69e3726f421121d98b03c04f753326bf5d53536f/Other%20Drafting%20Tools/Bike%20Bays%20with%20Set%20Out%20Points.JPG).
  * Since we used two layers, we can click on the sun symbol to freeze the SO bay layer to hide the [node points](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/fb10234dcecbde99937ed562e6bd1726a4c2703d/Other%20Drafting%20Tools/Bike%20Bays%20without%20Set%20Out%20Points.JPG).
  * Now, going to the lower left of the building we will create a donut to highlight a setting out point at the intersection of two gridlines.
    * Did this by selecting the donut in the draw panel, setting inside radius to 250 mm and outside radius to 500 mm, and snapping to the gridline [intersection point])(https://github.com/ashthemech/AutoCAD-Essential-Training/blob/8f0d02707d70033c8f4160935b40e96c21239a31/Other%20Drafting%20Tools/Donut%20at%20Grid%20Intersection.JPG).

  **Creating Ellipses Quickly**
  > NEW FILE: Cylinder.dwg - a drawing with two vertical lines where I will finish the cylinder on a 2D drawing to look like a 3D representation.
  * Used the center, end ellipse tool to [create an ellipse at the top](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/711b49d74c4f6d80d1c5a82e57116407d440d0ab/Other%20Drafting%20Tools/Cylinder%20with%20Top%20Ellipse.JPG) of the two vertical lines, specifying 60 degrees (since we want an isometric representation) using the rotation option.
  * Now need an elliptical arc along the bottom - I did this using the elliptical arc tool on the [botom of the two vertical lines](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/021b5a2bdd1450458f1418c02dbfef8d4c7e6819/Other%20Drafting%20Tools/Completed%20Cylinder.JPG).
    * Set the rotation again to 60 degrees, and then specified the start angle by going counterclockwise from the left vertical line to the right vertical line.

  **Using Isometric Drafting (ISODRAFT)**
  > NEW FILE: Isometric.dwg - a drawing with a half completed isometric rectangle.
  * Can generate isometric drawings - uses 30 or 60 degree angles to make what looks like a 3D object.
  * On the status bar we have ISODRAFT, can also set the Isoplane to top, left, or right.
  * Using the left setting and OSNAP on, we can complete the left side of the isometric rectangle, where the polar snapping follows the left [Isoplane axes](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/6c46bae65558cbd42b112b0873628c2c01c64f9c/Other%20Drafting%20Tools/Isometric%20Rectangle%20Left.png).
  * Can do the same on the top Isoplane to complete the [isometric rectangle](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/7601f7d575c8c1370e2f586e968189f83366634c/Other%20Drafting%20Tools/Completed%20Isometric%20Rectangle.JPG).

</details>
</details>

<details>
<summary> 8. Exploring the Interface Further </summary>
  
  Key Takeaways:
  * Reviewed working with File Tabs and the context shortcut menu.

<details>
<summary> GND Floor Plan_REV3.dwg - More Drafting Tools </summary>
 > GND Floor Plan_REV3.dwg is the same previous office building layout in previous module, with our bike bays and tables in the landscaping area.
  
  **Working with File Tabs**
  * The drawing file tab bar is in the upper left above the drafting area.
  * An asterisk on an open file lets you know something has changed and it is not yet saved.
  * If you hover over the file tab, you can see and navigate the different layout tabs in a mini picture.
  * Can also plot and publish from there as well.
  * You also have the three lines on the top and bottom left in newer versions of AutoCAD.

  **Using the Shortcut Menu**
  * Also known as right click menu
  * Context sensitive, so it depends on what tool you are currently using.
  * On the default right click, you can find objects, count them, etc. - lots of functionalities.
  
</details>
</details>

<details>
<summary> 9. Modifying Objects </summary>
  
  Key Takeaways:
  * Learned how to select objects and the many tools available, namely window vs crossing selections and blocks.

<details>
<summary> OfficeLayout.dwg - Modifying Objects </summary>
 > OfficeLayout.dwg is a simple office layout with walls and some objects outside of the walls.
  
  **Selecting Objects**
  * To be able to modify objects, need to know how to select them.
  * Quickest way is to move the crosshairs over the object, and it will highlight, then left click and will turn pale blue.
  * A block is a group of lines that have been converted into a "block" - here, it is a desk.
  * Can select multiple objects at once into a selection set.
  * To remove from a selection set, use shift click.
  * Quickest way to select more than one object is to left click once, release the mouse button, and use the window to select.
  * Crossing selection goes from right to left - do not need to encompass all of the objects.
  * Window selection goes from left to right - need to encompass all objects.
  * Lasso tool - from left to right is the window selection, and right to left is the encompass selection. Freehand draw by clicking and holding.

  **Using Move and Copy**
  * Can use move and copy commands from the modify menu or the shortcut menu.
  * When moving, it will prompt for a point to move from, then left you decide where to move the object to.
  * When copying, it will also ask you for a base point, then will let you make a copy to an endpoint. Note it will keep copying until you hit esc or enter.
  * I moved the desk into one of the cubicles, and made a copy of it and added that copy into a different cubicle.
  * Did the same process with the plant, then moved the computer and chair into the [upper cubicle](). 
  
</details>
</details>

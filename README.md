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
  * Learned how to use move and copy to move the desk, chair, omputer, and plant into the cubicles.
  * Learned how to use the rotate function by rotating a computer and chair to face the desks properly.
  * Learned how to use the scale function by copying a plant object and scaling it down.
  * Learned how to use the mirror tool by mirroring an office desk setup into the adjacent cubicle.
  * Learned about the smart block feature in AutoCAD 2025 and beyond.
  * Learned how to move lines on the wrong layer to the correct one though the layer dropdown.
  * Learned how to use the join and break commands to clean up lines.
  * Learned how to use the match properties of the hatching menu to copy a hatching.
  * Learned how to use boundary tools and how to add hatching to a boundary object.
  * Learned how to use grips to mirror object selections by coping a desk setup using the grip and mirror command.
  * Learned how to use fillet and chamfer to round and bevel multiple corners by using those tools on desks.
  * Reviewed how to use the divide and measure commands to place nodes and copy plants along set distances on a line.
  * Learned how to explode polylines and reconnect them back together and how to edit spline verticies.
  * Learned how to use Trim and Extend with boundary/cutting edges and fence tool.
  * Learned how to create an array of objects in rectantular, polar, and path formats.
  * Learned how to use stretch and lengthen to modify objects and lines instead of using extend.

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
  * Did the same process with the plant, then moved the computer and chair into the [upper cubicle](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/f83f5c8ebe689bdc28ea0637c2c1b7735296cff2/Modifying%20Objects/Copied%20and%20Moved%20Objects.JPG).

  **Using Rotate and Scale**
  * In the upper cubicle from the last section, the computer and chair aren't oriented corrently.
  * Went to Polar tracking to change 45 degree increments on, then selected the computer and rotated it so it faces the chair area.
  * Can also rotate by angle value- remember counterclockwise is positive, clockwise is negative.
  * I repeated the process for the chair, so now both the computer and the chair are [aligned correctly](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/ccc3706403e1a8ab42722314fe3f6b5380524395/Modifying%20Objects/Rotated%20Office%20Chair%20and%20Computer.JPG).
  * Next, I copied the plant and moved it to be on the top of the deck object, and used the scale function to scale it down to 60% of the original so it [fits nicely](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/a854395eada758fa0cec3b9c09205c0cfebfd82a/Modifying%20Objects/Scaling%20Plant.JPG).
  * Then, I copied the desk setup from the previous setup onto the other desk in the lower [left corner](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/4768f4c5cd65100c993ef5df43d83355a2c24264/Modifying%20Objects/Copied%20and%20Moved%20Desk%20Setup.JPG).

  **Using Mirror and Offset**
  * Note - these ones are not on the shortcut menu! Need to go to the modify panel.
  * I selected the office setup using the crossing lasso tool, then clicked mirror in the modify panel.
  * I set the mirror line to the midpoint of the cibicle division wall, then followed through to the end of the divider so the [setup is mirrored](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/32ebc60c32bfe452aa5fa32d68a627d6097704e2/Modifying%20Objects/Mirror%20the%20Office%20Setup%20to%20Right%20Cubicle.JPG).
  * Then to fix the lower left desk setup, I selected the objects in the cubicle and used the repeat mirorr command to flip the setup so the [desk is accessible](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/1cd00f1c02fbbac4b2046d2f521e338260c18d9c/Modifying%20Objects/Flip%20the%20Desk%20Setup.JPG). This time, deleting the original objects.
  * Then, in the "walls" layer, I drew two new lines offshooting from the office for trash storage. Uisng he measure tool to measure the inside wall width, I then set the offset to 150 to [complete the outline](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/017a79c820a6bdb4f27a3099fca57146a6fa8d89/Modifying%20Objects/New%20Wall%20for%20Office.JPG).
  * To tidy them up, I trimmed the crossing lines and added the end of the wall to [finish it off](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/65dc848abd0855771d41df3ca1c9125a0193b5f3/Modifying%20Objects/Trash%20Walls%20Trimmed%20Up.JPG).

  **Using Smart Placement of Blocks**
  * Available since the 2025 version of AutoCAD, implements AI into the workflow.
  * AutoCAd learns from what you do and it can assist you in your workflow.
  * I went to insert and selected desk, and then hovered next to the wall in the above cubicle and it placed it where it thinks [I may want it](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/adc9d6431a7a142b4ae579a87026c3a142480142/Modifying%20Objects/Smart%20Placement.png).
  * Pretty neat little feature!

  **Using Break and Join**
  * Moved the door lines from the "walls" layer to the "doors" layer by highlighting them and then selecting the appropriate layer in the drop down.
  * Moved the objects and chair from the lower desk to the upper desk using the mirror command, and then deleted the lower desk.
  * Changed the hatching in the walls from the wall layer to the "hatching" layer using the same process as the door.
  * Now, we want to move the door over to the lefthand side.
    * To do this, I selected the door and the frame, I selected mirror tool, opened the snap override from shortcut menu and selected midpoint between 2 points, and chose the corners of the outer wall.
    * Then, used polar tracking to go along the midpoint of the outer wall to move the door to the left.
    * To fix the holes the door left, I used the join tool to join the walls back together.
    * Then, to erase the walls within the door I used the break tool to make an opening for the door using first point and end point, [completing this section](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/c088539b96b03131d8bfef8ef34f909ebc911950/Modifying%20Objects/Office%20after%20Join%20and%20Break%20Section.JPG).

  ***Using Grips and Grip Editing**
  * To add the hatching back to the building, I went to the drawl panel and selected hatching.
  * Then, I selected the match properties, selected the previous hatching and copied it over to the [new wall layout](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/06f1bf375b7b6332aae1c54b521990ef05f154b3/Modifying%20Objects/Adding%20Back%20the%20Hatching.JPG).
  * I deleted the upper left desk setup as we are going to use the grip editing tool to mirror the adjacent setup over.
  * Then, selecting the cubicle setup from the adjacent cubicle (desk, plant, computer, chair) I select the grip on the desk to make it a "hot grip" (turning red).
  * I can mirror the setup by hitting mirror in the shortcut menu, then shortcut menu again and selecting "base point".
  * I selected the base point to be the middle of the dividor again, then selected copy from the shortcut menu before finising to ensure it [copied over](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/902a11755c5a015491d6370a8f27b2799a64c260/Modifying%20Objects/Mirror%20using%20Grip%20Editing.png).

  **Using Boundaries**
   > NEW FILE: OfficeLayout_2.dwg is the same previous office layout, now with added rubbish bins, a welcome desk, and some landscaping.
  * We are going to add a boundary in the "hardstanding" layer in the landscape area.
  * I selected the "boundary" tool from the hatching menu and selected the center [landscape block](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/88c0316d87112282da8b9b76a225611b867cff12/Modifying%20Objects/Added%20Boundary.JPG).
  * Boundaries allow you to add hatching in a different way.
  * Selected the hatching tool, and the "ANGLE" pattern at a scale of 250 to add to the center [landscape block](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/137e87661873b283f259ba07eb9d7199ee8b7041/Modifying%20Objects/Adding%20Hatching%20to%20the%20Boundary.JPG).
  * You can also go into the boundaries tab in the hatching menu, and select the objects you want to be the boundary.

  **Using Fillet and Chamfer**
  * Fillet - add a radius to a corner, Chamfer - beveled edge.
  * Easy way to enhance the geometry, but have a certain workflow that needs to be followed.
  * On the modify panel of the home ribbon.
  * Fillet will prompt you to select an object, but you need to make sure the settings you want are set first.
  * Right click, and radius which I set to 150.
    * NOTE, this will only allow you to do 1 fillet! Right click again, and go into multiple model
  * Similar workflow for Chamfer, but there are two methods: distance, angle. Can also use method to bounce between them.
  * I used the fillet tool on the [first desk with the computer](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/b25629861f9cc4a896e34d33d8d89f1a25097a45/Modifying%20Objects/Fillet%20on%20Desk.png), with radius set to 150 mm and selected multiple to the two corners.
  * Then, I used the Chamfer tool on the second desk with the distance set to 150 mm as well, and used that on the [second desk](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/cc112a537e71436e4630eb484021def51cd0cdf3/Modifying%20Objects/Fillet%20and%20Chamfer%20on%20Desk.png).

  **Divide and Measure**
  * Allows us to divide and measure geometries to place objects on those points.
  * Ensuring I was on the "nodes" layer, then clicked utilities and Point Style, using the circle and the diagonal cross.
  * Selected divide to add 5 node points to the landscaping near the [trash bins](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/ae639323b9722bf9b89de151a615e25ece1d4c77/Modifying%20Objects/Nodes%20Near%20Trash.png).
  * Then, copied the plant over and placed it over the nodes along the [landscape line](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/3f9ab958bc55ef63f0c95affe3e586f36cc59517/Modifying%20Objects/Plants%20Near%20Trash.png).
  * Now we will do a similar thing, but using measure along the bottom row of landscaping.
  * Used the measure function in the draw to put equal [spaces of 1000](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/4933cae4fbd401ebd8d0ab9de8dac45852f7cf34/Modifying%20Objects/Nodes%20on%20Bottom.png), if we did not know the spacing needed, we would need to measure that line and find the spacing.
  * Then, copying the plant again I placed the plants on the [node spaces](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/22036acae25291c2bef0db34886387e56a63a7cc/Modifying%20Objects/Plants%20on%20Bottom.png).
  * Now, we need to get rid of the nodes on the drawing and can do so by freezing the nodes layer.
  * We can also use just the line itself, and using blocks BUT need to make sure the block is sized for the right scale.
    * Using the divide function, before entering the number of nodes right click and hit "Block" then enter "plant", but they look [very large](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/b08750a473f932807ddf1d6470d4764ad0b4d49a/Modifying%20Objects/Large%20Plants.png)!

  **Editing Polylines and Splines**
  * Took the previous 2 desks that I added fillets and chamfers to and exploded them into their line segments.
  * Moved the bottom edges of the desk up by 150 mm, then used the trim tool to remove the remaining [segments leftover](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/c8f014613bb008f7e37bca4f7690b15bbbb64d7f/Modifying%20Objects/Resizing%20the%20Desks.png).
  * Now, we need to make the exploded polylines back into a polyline, we can do this through a keyboard entry shortcut.
    * pe is the command, polyline edit. Using this, I de-exploded the desks back into polylines.
  * Added electrical blocks near the [desks](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/95f3add62b0b1045166c0fa43360cbc7ba72205d/Modifying%20Objects/Adding%20Electrical%20Boxes.png) in the electrical layer.
  * Added a spline to the landscaping on the left to connect the two bush rows.
  * Using the shortcut menu, you can go into the Spline option and edit, I played around with the control [verticies function](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/4ead1f386793ba14fe9e101969292f3a796a46ae/Modifying%20Objects/Spline%20Verticies%20Function.png). 

  **Using Trim and Extend**
   > NEW FILE: OfficeLayout_3.dwg is the same previous office layout, now with added features up at the top.
  * Extend lets you extend geometry to another piece of geometry.
  * Using extend, I selected boundary to select the landscape spine as the endpoint for our extend.
  * In newer versions of AutoCAD, you can drag through the objects to extend using the ["fence" tool](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/274b2f87982fee719a4a07851498b33a395a67f8/Modifying%20Objects/Using%20Extend.png).
  * Now, we want to trim them inside that circle for the decking, so using the same process as above but using the ["trim" tool](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/93b0a721917bf720e79d5649b0ad283569c245a8/Modifying%20Objects/Using%20Trim.png), I did so.
    *Note for this, it is called "cutting edge" instead of "boundary".

  **Creating and Using Arrays**
  * Now in the plants layer, utilize the array tools to modify the plans object.
  * Array is essentially a copy command, but with many variables to copy objects more effectively.
  * Using the [rectangular array](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/2236479ef702829a3a333fe63560d8c370867e5d/Modifying%20Objects/Privacy%20Array%201.png) in the modify panel, I built a [privacy screen of plants](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/a01948d8f356766bd0da27414656af6840729eb0/Modifying%20Objects/Privacy%20Array%202.png) for the decking with 10 rows and 2 columns. with spacing of 650.
  * In later versions of AutoCAD, arrays become associative- the array becomes all one object. Makes it easier to change layers if necessary.
  * Using a similar process for the circular landscaping in the deck, I used the polar array this time to fit to that inner circle.
  * This time it asks for a center point, which I selected using object snapping on the circle. Then I chose 12 objects to [fill the circle](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/28c2eb7292d3fd37e5cea1141f2a438313f9a1fa/Modifying%20Objects/Center%20Circle%20Polar%20Array.png) more (default was 6).
  * Again, this is an associative array but a polar one.
  * Now, a path array along a spline using the ["path" array](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/c8858ef8ceee2286834835fe164a0d8da69680a3/Modifying%20Objects/Spline%20Array%201.png) tool.
    * Note, you can use the [divide and measure tool](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/6d0d9cc0aff0dd0a4984c739537ec2ae1a756e0c/Modifying%20Objects/Spine%20Array%202.png) in the array ribbon itself!
    * Can also use the grip to make the distance smaller or bigger (more or less dense). 

  **Using Stretch and Lengthen**
  * In the office layout, we are adding carpet for the cubicles.
  * We could use extend, but we will explore another command called lengthen on the Modify flyout (pointy line with dot).
  * Clicking on the carpet line with lengthen, there is delta, percent, total, and dynamic.
  * I used dynamic, and simply snapped it to the end of the [wall intersection](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/3148c33320de29b07dcdd941efdd41bb321ca55a/Modifying%20Objects/Lengthening%20the%20Carpet%20Line.png).
  * But now, the partitions do not match to the carpet line so we will be utilizing stretch on the partitions.
    * Note, NOT available on the shortcut menu- need the modify panel to access.
    * Also need to use selection window (crossing) to highlight the bottom of the partition.
  * I used the stretch command and made a crossing window, then stretched the [partition to the carpetline](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/4603a647d05698626960b6541cc0cfd113409b17/Modifying%20Objects/Stretching%20the%20Partition.png). I repeated for the other partition on the [other cubicle partition](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/d061460a73b76c50ef51d569db99b88bffdc26c5/Modifying%20Objects/Both%20Cubicle%20Partitions%20Done.png). 

</details>
</details>

<details>
<summary> 10. Hatching and Gradients </summary>

Key Takeaways:

* Learned how to place hatching in a section view to highlight what has been sliced.
* Learned how to add color gradients to enhance mechanical views.
* Learned how to reorder the gradient and hatching objects so gradient is below the hatching.
* Learned how to edit gradients and hatchings to space them out and use a cylindrical gradient.  

<details>
<summary> MetalPlate_001.dwg - Hatching and Gradients </summary>
  > MetalPlate_001.dwg is a mechanical diagram of a metal plate, with section view, side view, plan view, and dimensions.

  **Using Hatch to Highlight Areas**
  * Made sure I was on the "hatching" layer, and the pattern was "ANSI31".
  * If you select "Create Separate Hatches" in the options panel, you can create distinct hatches in areas- good to know, but we aren't using it for this.
  * Hatched the areas that are being [cut through in the section view](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/4b66a4e9e0b9909e56b3372bc2dfa03bcd81c616/Hatching%20and%20Gradients/Hatching%20the%20Section%20View.png), leaving the center alone where the filleted hole is.
  * Did a sanity check to make sure the hatching created is all one object, and [it is](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/2007fdf1d76704a78e19e1f6869ab92c644876fe/Hatching%20and%20Gradients/Sanity%20Check%20on%20Section%20View%20Hatching.png).

  **Using the Gradient Command for Enhanced Colors**
  * Ensured I was on the gradient fill layer, in general want it on a separate layer for independent freeze/thaw control.
  * We used the linear gradient pattern, and changed the angle to 90 degrees so its a vertical gradient.
  * Changed the colors from blue/yellow to a gray/bluish to make it appear metallic and [applied the gradient](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/391f0af5f53f3d65bb87c18fe6a171be4b880c71/Hatching%20and%20Gradients/Adding%20the%20Gradient%20to%20Section%20View.png).
  * But now, the hatch pattern is behind the gradient fill, which we will address in a later section.
  * Added the gradient to the [side view](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/88e399411e95f3bb16ffd25a083d367b734dbb26/Hatching%20and%20Gradients/Adding%20the%20Gradient%20to%20Side%20View.png) as well.

  **Using Draw Order to properly Display Gradients and Hatches**
  * Selecting the gradient and hatching on the metal plate by left clicking, we can then right click and select "draw order".
  * I sent the gradient to the back so the hatching appears [overlayed on the gradient](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/095dd2a61c31307aee0151a1c04d0cf74a554f4f/Hatching%20and%20Gradients/Using%20Draw%20Order.png).
  * This can apply to hatchings, gradients, or even objects as well.

  **Editing Gradients and Hatchings**
  * How we can change the settings in gradients and hatchings in our drawings.
  * Going into the layers and freezing the gradient layer, I made sure I was on the Hatching layer.
  * Then, changed the scale from 1 to 2.5 to make the [hatching more spaced out](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/7db1b8f1297fa258c4bf8c2a45e5f89c9e288e26/Hatching%20and%20Gradients/Editing%20the%20Hatching%20Scale.png).
  * To have some fun with the gradient, I added a cylindrical gradient to the plan view to make it [look metallic](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/e797f3dd155f1d68975ff0bfe1411ba4348e0378/Hatching%20and%20Gradients/Plan%20View%20Gradient.png), using similar steps from previous sections.
    * I selected the Plan view object with the gradient tool, chose GR_CYLIN, changed the angle to 45 degrees, and used a gray/dark gray color combination.
    * Then, I made sure the gradient was sent to the back so the dimensions can still be easily read. 
 
</details>
</details>

<details>
<summary> 11. Annotating Designs </summary>

Key Takeaways:

* Reviewed how to create a new text style templated from a previous style.
* Reviewed how to add text to drawings and layouts in single line and multiline format.
* Reviewed how to create a dimension style from an existing one and alter the settings.
* Reviewed adding dimensions annotatively with the viewport scales, adding linear, diameter, and radius dimensions.
* Reviewed how to use QLEADER for labeling in annotative style, and how to add an outline to the labels.
* Learned how to create a table style by creating a table style for the types of holes in our drawing.
* Learned how to add, edit, and alter data types in a table by adding a "Hole Types" table for the drawing.
* Learned how to create a new multileader style from an existing Annotative template.
* Learned how to place multileaders, add multileaders, and use the attributes text box.
* Reviewed how to reposition text using object snapping and midpoint snaping.

<details>
<summary> 11. MetalPlate_002.dwg - Annotating Designs </summary>
  > MetalPlate_002.dwg is the same as the previous section, but without and dimensions or labels.

  **Creating and Using Text Styles**
  * Annotation in AutoCAD is to communicate design intent.
  * Created a new text style called Notes_LAYOUT_3.5mm from the Title_LAYOUT text style, changing the height to 3.5mm and regular text in Calibri.
  * Created another text style called Labels_MODEL_15mm, changing height to 25mm and Bold text in Calibri.

  **Single Line and MultiLine Text**
  * Made sure I was on the correct layer of "Text".
  * Justified to Middle Left, set rotation to 0 degrees and labeled the ["Section View"](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/d121b84816a4ebe055ea4d9f8433db758a77faa5/Annotating%20Designs/Section%20View%20Label.png).
  * I copied the ["Section View"](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/194623cb7d10f120a126a1b9218f8c362d5f5a18/Annotating%20Designs/Copying%20Text.png) text and added it to the right of the side view and plan view.
  * Then, I edited the texts on each to [label accordingly](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/c940b388ca7e0bd5ae64bcaef155c86f992fe0c5/Annotating%20Designs/Labeling%20Views.png) "Side View" and "Plan View".
  * I switched the tab to the "Plan View" Layout, and added a [note block](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/a1e8980fe9c253d2e33fb961c78077862ba659ff/Annotating%20Designs/Adding%20a%20Note%20Block.png) to communicate notes in the layout.


  **Creating and Using Dimension Styles**
  * Made sure I was on the dimensions layer.
  * Created a new annotation style called "Training_ANNO" from the Annotative default, using for all dimensions.
  * Set all of the Dimension Line options to "by layer" so it adopts the properties of the layer it is on, and put baseline spacing to 10mm.
  * Set all of the Extension Line options to by layer as well.
  * Set extend beyond dim lines to 2.5 mm, and offset from origin to 4 mm.
  * Changed leader option to "dot", and arrow size to 3.5 mm, and turned off center marks.
  * Changed the text style to the preset one for this course (Dims_MODEL), changed text color to by layer and no fill color. 
  * Changes text height to 3.5 mm and offset from dim line to 1.5 mm.
  * Changed decimal separator to period and ticked suppress trailing zeros.

  **Adding Dimensions**
  * Recall, in the Annotate tab you can set a dim layer override to make sure all dimensions using a dimension style are in the dimensions layer.
  * Recall the little blue symbol next to our text style means it is an annotative style, meaning we need to set the scale to match the viewport.
    * Going into the Sects & Elevs layout and hovering over the viewport, the scale is 1:2, so we need to match that in the model tab.
  * I placed linear dimensions on the Section view geometry.
    * Note, if you have node snaps "on", dimensions will [node snap](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/4959dd7057c1cc2c11d50055d3b7e121748e8a87/Annotating%20Designs/Node%20Snapping%20in%20Dimensions.png) to existing dimensions but really should be snapping to geometry so I turned that off.
  * Added some dimensions to the [side view](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/b736ab8fb4be0310445e0adc3b47a1b31c8fd3e4/Annotating%20Designs/Section%20and%20Side%20View%20Dimensions.png) as well.
  * Checking the viewport scale of the Plan View, it is also 1:2 but get in the habit of checking when dimensioning!
  * Added some [basic dimensions](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/573d291df53c279fd16b843b95acc3ce0bf1e818/Annotating%20Designs/Plan%20View%20Dimensions.png) to the Plan View following the video.

  **Using Quick Leader**
  * We set that "leader" setting in our annotation style to "dot", so we are exploring thta using quick leader.
  * Recall that dim override does NOT APPLY to QLEADER!
  * Added a label using quick leader to [denote the slotted hole](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/3ab9e37f000fe69213a927e5fa69a533fa9267f9/Annotating%20Designs/Section%20View%20Slotted%20Hole%20Label.png) in the section view.
  * Repeating the command for QLEADER for the slotted hole in plan view, you can right click to go into the settings.
    * I checked "frame text" for this one.
    * Note, you can use "reuse next" if you are placing a lot of QLEADER lines!
  * Added the QLEADER label for the [slotted hole](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/407033614aef582630442f0f63512b695b9244d3/Annotating%20Designs/Plan%20View%20Slotted%20Hole%20Label.png) in the plan view, this time with the text outlined.

  **Creating and Using Table Styles**
  * Can be used to annotate data in drawings in the tables.
  * We are creating a "holes type table", so we want a table to list those types of holes.
  * Again in the annotation flyout, we can create a table style.
    * Note in the Table panel in the Annotate ribbon, you can extract data from the drawing and link data to the drawing.
  * Created a new table style called "Hole Types", changing text style to Dims_MODEL and text color by layer to be consistent in the title, header, and data sections.
  * Changed alignment to middle center in data section, as it defaults to top center.

  **Adding a Table to a Drawing**
  * Note, tables also do not use the dim layer override, so make sure you are on the correct layer!
  * For now, we are putting it on the "text" layer.
  * Clicked the "table" button, starting from an empty table, specify an insertion point, columns = 3, width = 75 mm, data rows is 2 and row height of 1.
  * Used standard cell style settings, and placed under the [Side View](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/d84cad2656d9b4f425a5f2ad30e870d2eb3be8af/Annotating%20Designs/Placing%20a%20Table.png).
  * After placing, the multiline text editor kicks in automatically.
  * Added title, hole type number, radius, and diameter information in the table.
    * Note, you can highlight cells and it will open the [cell editor](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/433c1cbee6488f86b25ea94912ea9cb6b69c31f4/Annotating%20Designs/Cell%20Editor.png). Changed to "middle alignment" in the alignment drop down. 
  * To edit the information in the cell, double click the cell and it will bring the text editor back in.
  * The Hole Type information is not very descriptive, so I added "Bolt hole" and "Slotted hole" in the [Hole Type No column](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/3c7277af1dd9d2ba6de37fa49adf123cbb7a1d92/Annotating%20Designs/Finished%20Table.png).
    * But, remember how we formatted the table to have "data"? An [action screen will pop up](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/4adacbc2c58db17caec0101112573c037430f291/Annotating%20Designs/Pop%20Up%20Warning.png), and we can click "change data type" to relieve this.
  * The table will also display in the [Sections & Elevations layout tab](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/4e33e3fd6454c9c1d3dc298fa1f61bacfb514f7f/Annotating%20Designs/Table%20in%20Layout.png), which is nice.


  **Creating and Using MultiLeader Styles**
  * So looking at our Plan View, we have 4 bolt holes and 1 slotted hole - we can place leaders to show which is which using multileaders.
  * On the annotate tab and the annotate layer on the model tab.
  * We need to set up a multileader style first, they act similar to text styles and dimension styles.
  * Going into the Multileader style manager, we start with the Annotative style and name this one "Training_ANNO".
  * Changed multileader type to "block" - we want to use one of the default source blocks, we will be using a circle.
  * Clicking set current and save, we now have a new multileader style.

  **Working with Multileaders**
  * Clicking on the multileader button in the annotate panel, we can place a multileader.
  * We place it on one of our bolt holes and drag, then [click to place it](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/78ea82d8a0cdb3f083effc92510ee833f1b444b0/Annotating%20Designs/Placing%20a%20Multileader.png).
    * Now, it brings us a [dialogue box](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/1a82b1bd37da04926ae92d4edcad319979d00f3d/Annotating%20Designs/Multileader%20Atrribute%20Box.png) called "Attributes" with "Tag Number" - we want to label it as 1 (to match our data table).
  * So right clicking and repeating MLEADER for another bolt hole, we enter the tag number again for type 1 and repeat for all [bolt holes](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/eb1f6563c1e827abcfceb2722d79325897e3948e/Annotating%20Designs/All%20Bolt%20Holes%20Numbered.png).
  * Then, we can add it for our [slotted hole](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/db84b484e7afb1a46d5a1b538de6574f91e30c2b/Annotating%20Designs/Slotted%20Hole%20Labeled.png) but this time labeling it as 2.
  * Note, since we set the spline for the multileader text style, they are easy to distinguish due to that curved line. 
  * We can also join the bolt hole multileader lines so they just form 1 label between the two by using "align" and [aligning both labels to overlap](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/17cb156d069ee76e5528fc33c577001bda1e1aae/Annotating%20Designs/Aligning%20Overlapping%20Labels.png).
  * You can also connect a multileader to an existing one by using the "add multileader" tool, then [selecting where](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/092089c132362702fdafa7d8a24239b063b4de7e/Annotating%20Designs/Adding%20a%20Multileader.png) to put that dot point. This is a better method than above.

**Aligning Text Precisely and Accurately**
  > NEW FILE! GND Floor Plan_REV4.dwg - Ground floor plan of an office building with bathrooms, conference rooms, bike stations etc. used in previous modules.
  * We are going to focus on the little circular table and 4 chairs in the upper left corner of the office.
  * Ensured I was on the "A-010-H_ROOM" layer before proceeding, the text layer for rooms in this drawing.
  * We are moving the EL4 name room to be vertical along the left side instead of at the top.
  * Justified the text to "Align", then selected the start point and end point of the new "box" for the text to go in.
  * But, if we try to [adjust the height](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/5f88af7273a5e8e89b2f1656c8c860ba3f979bf3/Annotating%20Designs/EL4%20Height%20Problem.png), it doesn't work since we only aligned to the length of the box.
  * [Instead](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/64314743d344a65f1318ca230c222c49ebe1b7ea/Annotating%20Designs/EL4%20Fixed.png), we can justify to "middle center", then use midpoint snapping to find the midpoint of the box, set rotation to 90, and change the height to 150 mm.
  * We can finish it off by then deleting the other room label and now we have our text vertically.

</details>  
</details>

<details>
<summary> 12. More Dimensioning Techniques </summary>

  Key Takeaways:
  * Learned what UNO means and how to use the text override function in the properties panel for dimensions.
  * Learned how to use the dim space and dim break to clean up dimension lines in the same area of the drawing.

<details>
<summary> Gnd Floor Plan.dwg - More Dimensioning Techniques </summary>
  
  > Gnd Floor Plan.dwg is an empty floor plan with some landscaping outside, walls, and dimensions for the walls and landscaping.

  **Editing Dimensions and Dimension Overrides**
  * Note - UNO means "Unless noted otherwise", seen on annotation drawings especially for buildings or architectural installations, i.e. tolerances not listed.
  * Going into the properties panel when a dimension is selected, note there is a "text override" option.
  * Here we put a note ["Measure onsite - <>"](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/2e46a4a7a47fede5d3bb7048aa3c55abbb2d4b40/More%20Dimensioning%20Techniques/Text%20Override%20Properties%20Box.png). The <> tells AutoCAD to put the [measurement box above it into that <>](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/776e3290ca796878dba2d88f7740d145ef0cc8f0/More%20Dimensioning%20Techniques/Text%20Override%20Result.png).

  **Breaking and Spacing Dimensions**
  * Going to look at "dim break" and "dim space", where you can add break areas and adjust the spacing of dimensions.
  * We are going to clean up this area [here](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/9c7f98b8c0fd724c395b13b5c45753292ef85f39/More%20Dimensioning%20Techniques/Dimension%20Area%20to%20Clean%20Up.png).
  * I clicked on the dim space tool and selected the [6420, 7501, and 14701](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/efab2613ff45edb2b54ed0416bef3cb10fc90772/More%20Dimensioning%20Techniques/Selecting%20Dimensions%20to%20Space.png). It has an auto setting but be careful, especially with annotative scaling.
  * I entered 250, and it [nicely spaced](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/3746f3700d651aaa257456a415cdc2678283dc16/More%20Dimensioning%20Techniques/Spaced%20Dimensions%20with%20Junction.png) the dimensions, but now we have a bit of a junction on the left.
  * Now, we are going to use "dim break".
  * Using the break tool, I selected 6420 and the 2791, which broke the first selection through the second one.
  * I repeated the process for the other two dimension limes to break, now the [junction is gone](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/dd87bf99778a78f5c92d27e8a2eed874e33e5573/More%20Dimensioning%20Techniques/Junction%20Cleaned%20with%20Dim%20Break.png).

  **Using Continue and Baseline**
  * Now going up to the top of the building, we place a linear dimension on the [upper left corner](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/fc115e9cda1ef6d740f98de2f397d097f97e30c8/More%20Dimensioning%20Techniques/First%20Dimension%20for%20Continue.png).
  * Continue and baseline automatically search for the last linear dimension placed, and [continue from there](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/955811735b3b16cf8f0be84b3d256f882806c178/More%20Dimensioning%20Techniques/Using%20Continue%20Tool.png).
  * I dimensioned the [rest of the top](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/11dfff65a731d5361486c84b9132a23a25d5f97a/More%20Dimensioning%20Techniques/Finishing%20the%20Top%20Dimensions%20with%20Continue.png) of the building using the continue tool.
  * Now on the left side of the building, we will do something similar but with baseline.
  * Again, selected linear and made the first dimension on that left side.
  * The [continued the rest with baseline](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/d8833d77f9d6e65c74e215ce0a75cf7de6ba6f43/More%20Dimensioning%20Techniques/Using%20Baselin%20on%20the%20Left%20of%20Building.png), but notice how it used that first dimension line as the baseline for all the others, and is inside/outside specific.

  **Using Automatic Dimensioning**
  * The icon with the sun on it in the dimensions tab lets you create multiple kinds of dimensions in a single session, eliminating the need to select dimension type.
  * AutoCAD can recognize the geometry and select the appropriate type - pretty neat!
  * Put a [linear dimension](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/6f4697cfb8c25dbe57738abe0036390608103b62/More%20Dimensioning%20Techniques/Linear%20Dimension%20using%20DIM.png) for the landscaping line and immediately after a [radius dimension](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/1759f1545f478bcb9b26bed97ffc51a3437727dd/More%20Dimensioning%20Techniques/Radius%20Dimension%20using%20DIM.png) for the bush.
  * Can also right click at any time to select what kind of dimension you want.
  
</details>  
</details>

<details>
<summary> 13. Object and Layer Properties </summary>

  Key Takeaways:
  * Learned about individual object properties and object properties grouped by layer.
  * Learned how to change individual properties into layer properties and correct line type scale in the object properties manager.
  * Learned how to use isolate and hide objects to obscure parts of the drawing in congested areas.
  * Learned how to create a new layer, delete an unneeded layer, and change the layers of objects through the layer panel.
  * Explored the various layer tools available on the layers panel, like freeze/thaw, on/off, make current and match.
  * Learned how to create new layer states and their purpose. 

<details>
 <summary> GND Floor Plan_REV5.dwg - Objects & Layers </summary> 
  > GND Floor Plan_REV5.dwg is the ground floor of the office space used in previous modules, with conference rooms, bike racks, bathrooms, etc.

  **Working with Object Properties**
  * Zooming into the table in the landscape area, we can see that it is inheriting the properties of the layer in linetype,lineweight and color.
  * We can change the color, lineweight and linetype by going into the properties panel, and the object will update but it is still on the same layer.
  * The idea of "ByLayer" is that it allows you to set properties of an object to the properties of that layer.
  * There might be hundreds of objects in a drawing using that layer, and it's a pain to go in and manually change all of the individual object properties.
  * Instead, you can change the properties of all those objects on the layer in one swift motion in the layer properties panel.
  * Properties of an object can be individual or set to properties of the entire layer.

  **Changing the Linetype Scale**
  * Looking at the gridline properties, we notice that the Linetype is set to [individual](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/deb6f2b436b6998d1ef34ac86f6db7689f5cc7ff/Object%20and%20Layer%20Properties/Gridline%20Properties.png) instead of Bylayer.
  * Going to use the tool called select similar by clicking on a gridline, then right clicking and clicking "select similar".
  * This selects all of the gridlines, then going to the properties panel can select "ByLayer".
  * But then we [lose our dashes](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/bc581f13378c0a86bb75ed3f8ebc379217588fe5/Object%20and%20Layer%20Properties/Gridline%20Dashes%20Lost.png)! Time to go into the Layer properties manager and [correct that](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/76bc7b9cdfbcee7b4339210e95499971d0fb4e53/Object%20and%20Layer%20Properties/Setting%20Gridline%20Properties%20to%20ByLayer.png). Then we have our grid line linetype back for [our grid](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/957523604794ab7c964d865461ac4caa0a30f9b7/Object%20and%20Layer%20Properties/Dashed%20Gridlines%20in%20Layer%20Property.png).
  * But now, when we zoom out they still look like continuous lines, so let's change the Linetype scale (LT Scale).
    * Be careful here, if you look up LT Scale in the dyn input, it will change for the whole drawing- we only want it for this layer.
  * Instead, we select a grid line and use select similar again, then go into their properties and change the [LT scale to 20](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/3359205826eaeaa55d40d92afadf63b83b3c4374/Object%20and%20Layer%20Properties/Setting%20Gridline%20Linetype%20Scale.png).
  * Now we have much more [obvious grid lines](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/63f083999cc63b516626acd4cebc4f5e1000d5a6/Object%20and%20Layer%20Properties/Corrected%20gridline%20LT%20Scale.png) when the drawing is in extended zoom.

  **Using Hide and Isolate**
  * Physically change the properties of objects in the drawing do you can work quicker and easier.
  * In the floor plan we are working on, there are some restrooms so we zoom in on those.
  * We are going to select the objects in the restrooms (toilets, sinks) so they can be hidden, to say work on the walls.
  * Dragging a window selection across the bathroom, then using the short cut menu we can "hide" or "isolate" objects.
  * Hiding makes the selected objects go away, while isolate isolates the objects and hides everything else.
  * To get the hidden objects back, right click again and hit "end object isolation".

  **Creating New Layers & Layer Dropdown**
  * Can create a new layer in the layer properties manager.
  * I created a new layer called "Landscaping", with a green color (102), continuous line type and set as the current layer.
  * Now if we hover over the landscaping in the drawing, we see that the landscaping outline is on the site layer really should be on the landscaping layer we just created.
  * We can select the landscaping outline, and [change the layer](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/ae2bcead3eba1af479e270b21b07d26b253bdb0f/Object%20and%20Layer%20Properties/Changing%20the%20Layer%20in%20the%20Panel.png) right in the layer panel in the homebar. And if we hover over it, as can see [it has updated](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/9dc7405f0c72568b7479239143ec7f807f2636a1/Object%20and%20Layer%20Properties/Landscaping%20Layer%20Check.png).
  * We can delete layers in the Layer Properties Manager by selecting the layer we wish to delete, and hitting the red X.

  **Using the Layer Tools**
  * The Make Current tool allows you to select an object whose layer you want to be working on.
  * The Match Layer tool allows you to change a selected objects layer to a "destination layer" of a different object.
  * The Off tool lets you turn off a layer of a selected object, can also use the On tool to do this in reverse.
  * You also have Freeze and Thaw, note you cannot freeze the current layer you are working on! But, you CAN turn off the current layer.
  * There are a lot of layer tools, like Layer Walk that lets you see what is only on the selected layers.

  **Working with Layer States**
  * Allow you to save specific layer settings in each "layer state".
  * For this, we are going to highlight our Landscaping area, make sure the Layers Panel is pinned out.
  * Click the drop down on "Unsaved Layer States" and hit Manage Layer States, this opens up to the Layer States Manager.
  * Created an "EXISTING" layer state to tell AutoCAD that everything as we have it set now is our "Existing" later settings.
  * Went into the landscaping layer and the bike bays layer to [change the color to red](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/81cfeeb070a49dde5a978db246ee9d630559270e/Object%20and%20Layer%20Properties/Changing%20Bays-Landscape%20to%20Red.png).
  * Going back into the Layer States Manager, we see that the "Same as DWG" now says no.
  * Now clicking on new, we can create one called HIGHLIGHT and add the description, and that one says yes it is the [same as the drawing](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/36dde93c8f632b3a6b21f4743c934d20cdf89516/Object%20and%20Layer%20Properties/Layer%20States.png).
  * Can tab  between them in the layer states pinout - great to highlight areas that need work or are complete. 

</details>
</details>

<details>
<summary> 14. Reusing Content </summary> 

  Key Takeaways:
  * Learned how to navigate the groups panel and create a new group in the group manager.
  * Learned how to create a new block from existing blocks using the Create Block tool. 

<details>
<summary> New Office Project.dwg - Reusing Content </summary> 
  > New Office Project.dwg is back to our small office layout with the 3 cubicles and reception desk.
  
  **Using Groups with Geometry**
  * Its helpful to reuse content so you are not creating everything from scratch every time.
  * Exploring the "Groups Tools" - to do this we are going to zoom in on the [trash bins]() and create a "bins" group.
  * Groups panel is in the home ribbon, make sure group bounding box is always on. Gives you a boundary around your group.
  * Best way to create groups is in the Group Manager to give it a name.
  * In the manager panel as well, as you make a group you can tick "selectable" so they can be selected.
  * Created the new Bins group by selecting "new" in the manager and then using a crossing window to select all the bins, and now [they are grouped]().
  * Have Group Edit and Ungroup - note groups do not have a shortcut menu unless you select group edit. 

  **Creating and Inserting a Block into a Drawing**
  * You can create blocks of blocks in AutoCAD, basically individual blocks can be made into another block (also called a nested block).
  * Zooming in on the [executive desk](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/64b319de5dc70c7bdaec06facda74a18d60fbcfe/Reusing%20Content/Executive%20Office%20Seperate%20Blocks.png), we are going to create a workstation block that includes a desk, chair, plant, and computer.
  * I created a layer for our stations called "Workstations".
  * But, the blocks we want currently are on their respective layers, so I selected all of the workstation blocks and moved them to layer 0.
    * We do this so that when we create a block and bring it into the drawing, it will automatically assume the current layer (workstations).
  * On the insert ribbon, I clicked on Create Block which opens a Block Definition dialogue box.
  * I used pick point to specify the endpoint of the existing desk in the lower left corner of the cubicle.
  * Then I selected the objects to add into our block - the chair, desk, PC, and plant.
  * I selected "delete" in the Objects tab to delete the objects (but the block will remain in the drawing).
  * I made sure scale uniformly and allow exploding was ticked, then I could hit ok to [create the block](https://github.com/ashthemech/AutoCAD-Essential-Training/blob/4a6b2e9bbb512b2974ee7b09063d1092d5d4c43c/Reusing%20Content/Block%20Definition%20Setup.png).
  * Everything disappears! But do not panic, we just have a new block in the .dwg file (good time to save the drawing).
  * Then, we go to insert and we can see the [workstation block](), and place it in the [executive office](). 
  
</details>
</details>

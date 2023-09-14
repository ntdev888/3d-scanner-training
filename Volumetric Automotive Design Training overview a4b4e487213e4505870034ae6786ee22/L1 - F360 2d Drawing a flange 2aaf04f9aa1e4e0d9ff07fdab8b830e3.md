# L1 - F360 2d Drawing a flange

### Foreword

These lessons are for entertainment and educational purposes.
The information provided cannot be considered wholly accurate. 
We are not an officially recognised educational provider, school or training company.

As a creator, our intention of these lessons are to show the design process Volumetric undertake to produce our designs. This may and will differ from what is recommended by the manufacturers of the software products and equipment used in these lessons.

Volumetric NZ has no affiliation with Solidwork's, Fusion360, Xtract3d, Einscan, Creaform, Meshlab, GOM Inspect or any other brands or equipment used and shown throughout these lessons.

The resources provided with this lesson are for the purchaser to use as reference material, and is not to be sold, shared, uploaded or distributed.
All lesson Content was created by Eva Mechanica Ltd trading as Volumetric NZ.
And it took us a pretty long time to do it.

All software shown is licensed and owned my Eva Mechanica Ltd
We do not endorse or support the piracy of software.

---

## None of these parts or designs are intended for final use.

---

This lesson is to go through the process of drawing a 2d turbo flange from a pencil rubbing

- Rubbing from gasket or flange
- import into sketch in solidworks
- orientate and scale appropriately
- dimension and check against original part
- extrude
- save file

Rubbing from Gasket or Flange;

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled.png)

The most straight forward process that is accurate enough for fabrication is to take a rubbing of a flange or gasket.

This way you can purchase a gasket from a retailer for the flange you require which you will use anyway in the final application, take a rubbing of this, then organise to get it profile cut.

For 2 years I worked for a large Fabrication and Laser cutting company here in New Zealand, and this was still a process used by experienced engineers.

The most import thing is scaling. 

When we scan the rubbing into a 2d printer it will never be dimensionally accurate. However when we manipulate this in CAD we will be able to scale and check the size at this point.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%201.png)

Gasket Rubbing

I will often take a rubbing of the gasket for dimensions, as it will give me clear defined edges. But during this process it is quite easy for the paper to move so you get ghosting which you can see in the upper left corner.

For this reason I also like to trace the gasket;

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%202.png)

Traced Gasket

This will give us positional accuracy, however the dimensions of the interior and exterior profiles will be out by half the thickness of the pen or pencil we are using.

One thing to be clear, this process is only useful for the replication of profiles that are to be used for assemblies and components where 0.5mm errors are acceptable. 

As outlined earlier, we are only going to touch on the basics of CAD throughout this material.

There are a lot of good tutorials and exercises all over the internet that are very well written and very comprehensive.

This is not why your here though, you are here to learn the Gems, the gold, and have those 'aha' moments. 

So lets get into that.

Create a new empty part.
If fusion has a part already open you want to keep, press the + symbol up the top right.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%203.png)

Insert our Traced Gasket sketch into our Fusion 360 component by selecting Insert → Canvas

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%204.png)

Select “insert from computer” and locate the traced gasket that was included with this lesson content.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%205.png)

For continuity when you import the flange, ensure that the orientation cube in the top right corner shows the word TOP the correct way around.

If it doesn’t, rotate your canvas like I have below so that it is in the correct orientation.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%206.png)

What I like to do is try and position that flange as close as we can so that the origin is central to the flange or the bottom left have hole.

I choose to go off the lower left hole for ease of orientating the sketch.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%207.png)

Once you are happy with location, complete the operation by clicking the OK button on the CANVAS dialog window.

You may notice that the part is not scaled correctly.

Go to the browser tree and find Canvases, expand this out, and right click on the tracing we have just imported.

Here we will get the option to calibrate, select this.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%208.png)

The mouse cursor will change to a + symbol.

While in this function, select the edges of the flange in the longest direction (X Axis)

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%209.png)

We can see that our Canvas scale is not correct to what we have traced.

Change this value to 107mm (the measured size of this flange using Digital Calipers.

**As with everything there will be hiccups.
Part of these lessons I want to explore is the fact that mistakes do happen, and how to work through them.**

When we select the origin, we can see that it is no longer in the position we want.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2010.png)

To move it, right click the canvas in the BROWSER and select ‘Edit Canvas’

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2011.png)

This will return us back to the familiar menu we saw when we first imported our traced gasket.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2012.png)

Select the eye so that we can see the component origin and move the tracing into position.

We are not yet finished with positioning our traced gasket yet.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2013.png)

Now we want to create a sketch to check our position and orientation.

Select create sketch and pick the TOP Plane (XY Plane in the BROWSER)

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2014.png)

A grid will appear and the menu will change to allow us to Sketch over our Canvas.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2015.png)

Create a 3 point circle by selecting a circle option from the sketch menu.
Then change the option to 3 point.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2016.png)

We will use 3-Point Circle a lot throughout the modelling of 2d and 3d Scans. 

Pick your first point somewhere on the circle perimeter.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2017.png)

Do your second an even distance around the circle as if you were cutting it into thirds.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2018.png)

Then the last position the same again, equal spacing from the last 2 points

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2019.png)

Do the same again to the opposite hole on the gasket.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2020.png)

Now we are going to draw a construction line from the centre points of each circle.

Click the line/arc tool and change it to ‘Construction’

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2021.png)

After creating the centre point lines, create a horizontal line, add the Horizontal relationship to this line.

**Note: I have changed my background for this next image to show the construction lines.**

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2022.png)

Dimension between the 2 lines to measure the amount we need to rotate our Canvas by to properly align it. Record this number down.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2023.png)

Finish the sketch and edit our Canvas.

Click and drag the rotational marker (the blue circle), it will move more than the desired amount but a dialog box will appear.

Put our measured amount into this box.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2024.png)

Click the Rectangle in the move marker and position our Canvas over our origin again.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2025.png)

**NOTE: Fusion 360 move tool for Bodies. Meshes and Components gives us the ability to relocate the centre of rotation for it. I have put forward to Autodesk that we have the same ability for Insert → Canvas functionality as this will reduce the micro-adjusting we need to do to position our Canvas.**

Create a sketch on the top plane.

Hide the construction sketch we used to align our Canvas in the Browser window by clicking the ‘Eye’.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2026.png)

From our sketch we can see that our opposite hole looks very central relative to the grid lines.

Go through and 3 point circle the 4 bolt holes for our gasket.

If you make a mistake and position one of your circles in the wrong place.
Select the centre of the circle and click and hole it to reposition it.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2027.png)

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2028.png)

Go through and just use the dimension tool to validate our hole positions on our sketch.

This will show us if our scale is out.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2029.png)

When lasercutting parts, a positional tolerance of +-0.2mm is acceptable as we will have clearance on these holes as well.

Next use the rectangle tool to draw a rectangle oversized to the outter size of the flange.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2030.png)

I try to line up one edge as best as possible to reduce time.

Next go through and line each line edge as best fit for the outside of the flange.

This is when we see the inaccuracies of this process.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2031.png)

Align the line as best as possible so that our traced line is ‘average’ about the traced edge.

Select the fillet tool and start picking the 4 corners.
Do not worry if the dimension is incorrect at this stage.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2032.png)

Now click and move the Arrow positioned at one of the corners until we have a fillet of best fit on all 4 corners.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2033.png)

This looks to be 10.5mm

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2034.png)

Repeat the entire process again for the flange inside edges.

Select and draw a rectangle oversize to the flange port size, lining up one edge as best as possible.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2035.png)

Drag the other 3 lines to best fit over the port.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2036.png)

This time we are going to dimension this port as this is critical to the final product.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2037.png)

Go through and fillet select the 4 corners like we did previously.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2038.png)

Again it looks to be 10.50mm is the best fit for these.

Click finish sketch once you are happy with tweaking your sketch.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2039.png)

Now we wish to make a 3d model of our Sketch, we can ‘Extrude’ our sketch.

However we are going to start using the Push/Pull Tool as much as possible.

Select this from the tool bar and pick select the area of your sketch you wish to make into a solid.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2040.png)

Create a 10mm thick flange.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2041.png)

And select OK in the Extrude Dialog Box.

We now have our flange!

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2042.png)

The next thing we want to do is 3d print this so that we can check it on our turbo before we laser cut the final part.

I highly recommend this in EVERY situation as it will show you instantly if there is a mistake.

Fusion 360 is quite a comprehensive package and we are able to 3d print from within the package.
There will be a separate lesson process for that covered in our Print to Cast series.

For this situation we are going to export out model as a STL to print in our proprietary 3d printing software (in my case I have been using Simplify3d since 2013 so will be using this)

First we need to save our document.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2043.png)

I suggest creating a folder just for this course.
I have called this file ‘Lesson 1 - 2d Flange’

Hit Save.

Now that we have saved our project, we have the ability to export our files.

Click file → Export

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2044.png)

In the file type, drop down to STL and select the location you wish to save your file.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2045.png)

Click Export.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%2046.png)

DONE!
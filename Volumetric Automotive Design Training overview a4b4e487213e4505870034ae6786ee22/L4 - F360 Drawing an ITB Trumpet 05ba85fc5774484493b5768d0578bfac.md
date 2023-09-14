# L4 - F360 Drawing an ITB Trumpet

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

This process is going to be a hybrid of 2 things we have done so far.

- Revolving a shape
- Drawing a flange

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled.png)

There is a lot of discussion on the optimal Trumpet shape, and this is an area that we can all talk about until we are blue in the face.

The purpose of this lesson is to teach you how to draw your own, and in no way is recommending this as the final desired shape.

From the downloaded resources, we are going to use the Flange Block for a 4age Silvertop (AE101) ITB inlet flange.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%201.png)

We can do this by importing the DXF onto the Top plane.

Go Insert → Insert DXF 

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%202.png)

Select the Top plane, then click on the small folder next to ‘Select DXF File’ in the Dialog Window.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%203.png)

Explore to the location of the downloaded resources for this lesson and open the DXF ‘4age ITB Silvertop Flange’

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%204.png)

Make sure the units are in millimetres and ensure you are happy with the position of the DXF when imported.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%205.png)

We will now see the sketch in our Browser

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%206.png)

If we open and Edit the Sketch, it is a dumb sketch with no dimensions.

Just add the centre hole dimension, and 2 hole positions so that we know that it has imported correctly.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%207.png)

Convert the horizontal line into a construction line so that it does not interfere with the extruded body we produce.

Finish Sketch

Create a new sketch on the front plane.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%208.png)

Orientate our view to look onto the Front plane.

Now draw a centre line 75mm long from our sketch upwards.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%209.png)

Next I create a line with the minimum distance between ports. This helps show what the maximum trumpet diameter can be before trimming. 

This is 93.50mm about the Centre line.

Make this a construction line.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2010.png)

We are now going to create a line under our flange face with a 7 degree taper outwards connecting to the edge of the 50mm Diameter.

Use the line tool and hover the mouser cursor over the horizontal line that represents our flange.

Move it towards the outside until the X has a Triangle appear next to it.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2011.png)

This signals that the tool has found a entity edge that we can join our line to.

Start our line here and move the cursor downwards.

If we rotate our model view around we can see that the line intersects the edge of our Trumpet bore.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2012.png)

Rotate back to the front view and add a dimension between this newly created line, and our 75mm long Centreline.

Make this 7 degrees.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2013.png)

Next we want to use the Spline tool and create a 2 point spline from the end point of this line, the the end point of our 93.50mm Construction line.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2014.png)

Click the spline tool.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2015.png)

Now click each of these 2 points to produce a straight line and press enter.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2016.png)

Using the Tangent relationship tool from the constraints menu, create a tangent relationship between out spline and the 7 degree construction line.

It will adjust itself.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2017.png)

Now create a Tangent relationship between the horizontal 93.50mm line and our spline.

We will get this funky looking result.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2018.png)

When we select the spline now, 2 control handles will appear.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2019.png)

Start with the top one, pull the left hand control point to the right towards the 93.50mm line end point until we get a result like below.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2020.png)

Do the some for the bottom control hand until we get a gentle flowing spline feeding into our inlet port.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2021.png)

Using the offset entity, select this spline and offset 2.00mm

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2022.png)

Using the line tool, join the Offset line to the spline we initially created to create an enclosed region that we can revolve.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2023.png)

Close you sketch.

Now using the revolve tool 360 revolve this new shape.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2024.png)

Press OK

Select the lower flange shape and Push Extrude this down to create the flange face 5.00mm

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2025.png)

If we peak inside we will see some strangeness.

**NOTE: As we know we straight extruded down our flange, but we are feeding a tapered shape into this.**

**In other CAD packages you would need to do a revolve cut to clean this up, or just leave it with a stepped face.**

**However Fusion 360 has some powerful Direct Modelling tools hiding inside it.**

The 2 features that are causing issues I have selected in blue

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2026.png)

If we now press the DELETE key on our keyboard, Fusion will remove these and extend the internal trumpet face downwards until it meets the bottom face.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2027.png)

Now we have a smooth uniform face!

Next fillet the Trumpet edge where it meets the flange face on the outside.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2028.png)

I push it until it fails when it meets the hole edge (Dimension 3.347mm)

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2029.png)

Now our bolt head will not come up flush against the flange face.

For this we will need to create a sketch on the flange face and draw 2 circle concentric to the bolt holes at the size of our cap screw head (M8 Capscrew has a head diameter of 10mm)

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2030.png)

Draw a 11mm Diameter circle as this will give us clearance on a M8 capscrew head and account for any descrepency in the Screw casting.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2031.png)

You will notice now that the original DXF is a little generous with the M8 clearance having a 9.50mm hole.

We can fix this by using the Push/Pull tool to adjust the diameter of the hole.

Select the 2 faces and select Push/Pull

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2032.png)

The arrow indicates the direction of the measurement we put in the dialog box.

Enter 0.50mm (this is working in radii, so this is a change of 1mm in the diameter)

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2033.png)

Click OK

When we select the upper edge and check the dimension in the bottom left we will see the holes new diameter.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2034.png)

Select all of our Sketch region on both sides.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2035.png)

Now Push/Pull upwards to extrude cut through the fillet.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2036.png)

We now have our completed Trumpet.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled%2037.png)

Work with the spline and the distances to achieve different designs.

Save as an STL and print 2 samples in low Cost PLA to trial fit next to each other.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled.jpeg)

Advanced 3d Printed trumpet designed by Volumetric for ITB V6 NSX Motor

PLA Test fit shown.
(Special thanks to Cody for letting us share photos from his project)
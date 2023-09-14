# L9 - F360 Turbo Dump Pipe

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

Go into the data management window, and upload the GT25 Turbo 3d Scan.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled.png)

Go to the Mesh tab, and use the Scale tool to reduce to 0.1 around the origin to convert from CM to MM

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%201.png)

Click OK and Save.

If your computer is struggling with the size of the Mesh file.

Go to the Reduce tool and decimate the mesh down to 25% triangle density.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%202.png)

Remember not to try and use Fusion while this green bar is loading or you are likely to crash the software.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%203.png)

Now we have a very good representation of our GT25 without being too intense on our resources.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%204.png)

Orientate your Turbo 3d scan to be aligned to either Top mount or Bottom Mount for our vehicle.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%205.png)

Create a sketch on the front Plane and put in the below dimensions.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%206.png)

This is going to produce a gradual transition for our dump pipe to meet up to and existing manifold.

For the purpose of this tutorial this is hypothetical, however real dimensions are achievable by using string lines to triangulate the positions of your parts. Or going a step further to take a full car scan and position everything in that (future lessons will cover this)

Create a perpendicular line from the 80mm construction line.

Then draw a 2 point spline connecting to the end of this line and the origin of your sketch.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%207.png)

Next create tangent relation ship between your spline and the perpendicular line.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%208.png)

Next create a tangent relationship between our 2 point spline and the horizontal construction line.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%209.png)

This is the center line path for our dump pipe to follow.

Finish the sketch and hide it.

For the complexity of this and future models, it is best to start naming your sketches to keep track of what they are.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2010.png)

You do this by single clicking slowly on the sketch name then typing in what you would like to call it. Then press enter.

Next create a plane through 3 points on the rear flange face of our Turbo.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2011.png)

Create a Sketch on this face, and ‘Look At’ it.

Use 3 point circles to capture the positions of the inner cavity edges.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2012.png)

Fix their position so that they are not accidently modified using the Fix relationship tool.

Draw straight lines between each circle.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2013.png)

Now create tangent relationships between each line and each circle they connect to.

The 2 vertical lines on the left hand side should have ‘vertical’ relationships.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2014.png)

Using the Trim tool, trim away the inside of all the sketch.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2015.png)

Our fixed relation ships will disappear. 

We only wanted these to ensure that creating the tangent relationships do not influence their diameter.

Create 3 point circles capturing the stud positions for our flange.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2016.png)

Finish the Sketch and name it “flange geometry”

We are going to project from this sketch and modify that information, rather than risk modifying geometry captured from the 3d scan.

Create another sketch on the same plane, and project all the geometry from “Flange Geometry” sketch onto it.

We should have something that looks like below.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2017.png)

Create an offset sketch of 7mm

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2018.png)

Create centre circles around the stud positions.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2019.png)

Adjust these to cover the material on the flange face.

And trim away all the geometry that is unnecessary. 

We will be left behind with geometry below.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2020.png)

Extrude this 12mm

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2021.png)

Now we are going to turn our Centerline Path Sketch back on.

Go to Construct → Plane along path

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2022.png)

Then select the Spline in our Sketch.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2023.png)

Drag the arrow until the plane ‘Notches’ to the end point.

The distance should read 0.315

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2024.png)

Click OK.

Import DXF and select the ‘50mm Exhaust Flange’ DXF

It will come in out of position, however we will fix this in the sketch itself.

Click OK and leave the flange where it is.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2025.png)

Go into the browser, right click 50mm Exhaust Flange and edit it.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2026.png)

Select the Geometry and press ‘M’ (or select Move from the modify menu)

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2027.png)

We are going to use the point to point command.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2028.png)

Select the Point to Point → Pick the Centre of the Circle → Pick the End point of the Spline.

The geometry will move into position.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2029.png)

Click OK and Finish sketch.

Extrude this profile up 12mm

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2030.png)

Create a sketch on the 50mm Exhaust flange face closest to the Turbo.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2031.png)

Offset the inner edge 2.5mm outwards.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2032.png)

Click OK And Finish sketch.

Create a sketch on the exhaust outlet flange on the Turbo on the face closest to the 50mm Exhaust Flange.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2033.png)

Offset line 2.5mm from the inner edge.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2034.png)

Click OK and Finish the Sketch.

Loft from the 2 Sketches we have just created using the outter regions.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2035.png)

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2036.png)

This time, instead of using guide rails, we are going to use a centerline rail.

Change the Guide type to Centerline

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2037.png)

Then select our spline.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2038.png)

We can see that Fusion has filled in the Dump pipe.

I was expecting this as Solid Modelling software of every type can often struggle with Pipe Lofiting.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2039.png)

Click Loft → Select the inner face on the turbo side for the first profile.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2040.png)

Rotate around and select the 50mm Inner face for the second profile.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2041.png)

Fusion has defaulted to Cutting, which is what we want, however its path cuts through the side.

As with before, change the guide type to Centreline then select the spline.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2042.png)

Click OK to complete the operation.

It is good at this point to take a section analysis of the model to ensure that everything looks good.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2043.png)

We are looking for any area that is particularly thin or any ‘flickering’ when moving the section tool.

The flickering will show any inflections (twisted surfaces) that may have occurred during the lofting operation.

Time to do some house keeping and add fillets to our flanges.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2044.png)

Add a 8mm Fillet to the edges.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2045.png)

Due to this crease we are unable to fillet from the flange to the dump pipe body just yet.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2046.png)

Select these 2 edges

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2047.png)

Then apply a 4mm Fillet to them.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2048.png)

Next we need to fillet the inside 1.5mm to account for the material offset of 2.5mm.

This helps with the casting process and allows material to flow more uniformly through the pattern.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2049.png)

Now we will be able to add a filled to the Flange/Dump body edge

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2050.png)

Apply a 3mm Fillet to this edge

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2051.png)

Do the same process to the 50mm Exhaust Flange side.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2052.png)

You may notice something that is often an oversight on aftermarket dump pipes.

This is a flat face for the screw to mount against.

Create a Sketch on the Turbo Flange outer face.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2053.png)

Draw 5 center point circles on each of the bolt hole locations.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2054.png)

For ease of install we will be using M8 Cap screws to attach our Dump pipe to the turbo.

The maximum allowable head diameter on a M8 Capscrew is 13.27mm, we will dimension our circles at 14mm.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2055.png)

Finish the sketch, then extrude cut these regions through our fillet.

we want to go high enough it clears away the fillet region, but not so high it eats into our dump pipe body.

About 5.3-5.5mm will work.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2056.png)

Its the little things that make life easier later on.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2057.png)

There is more than enough material here that we could push this cutout further.

One last thing we need to do is increase our M8 holes to be clearance on an M8 Screw.

One way is to do a sketch and draw circles at these hole locations.

The other way is to use the offset tool and move the surfaces the clearance amount we need.

From the Modify tool bar select the Offset face tool → set the side to 4.5mm (or 9mm in diameter) to give 0.5mm clearance a side on our Cap Screws.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2058.png)

We now have a completed Dump pipe.

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2059.png)

![Untitled](L9%20-%20F360%20Turbo%20Dump%20Pipe%208fb1740593d943dc9c4d0f8fb8dac7a9/Untitled%2060.png)
# L6 - F360 Flange from 3d Scan

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

For this lesson we are going to model off a 3d scan.

Fusion 360 does not need any plugin or external software to do this.

However, Fusion 360 is more resource hungry compared to other packages when handling Mesh data, so it is highly recommended that you decimate (reduce point cloud density) in a 3d party package such as Meshlab before importing it into Fusion 360.

How to do this will be covered in our ‘3d scanning data’ course.

We are going to need to import the Beams 3sge scan into fusion 360.

In a new component file go to the Mesh Menu
Then go Create → Insert Mesh

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled.png)

Explore to the location of our 3sge Beams Head 25p and import.

Ensure that the unit of measurement is Millimetres NOT Centremeters 

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%201.png)

**NOTE: There is a Bug in Fusion 360 that imports meshes in Centremetres when using the “upload” function**. **Avoid using this process**

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%202.png)

---

This 3d Mesh of the 3sge Beams head we have imported is at 25% of the detail that the scan recorded. To further reduce the detail we will need to decimate it in MeshLab (tutorial is part of the 3d scanning course)

---

Go back to the Solid Menu and create a sketch on the front Plane.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%203.png)

We are going to go through and model the intake flange in preparation for designing an ITB manifold.

Zoom in on a stud and draw a 3 point circle around it.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%204.png)

Go through and pick points as Tightly as possible to the stud position.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%205.png)

This sketch will be used as reference for future sketches that we need for modelling our flange.

Go through and grab all the stud positions using the 3 point circle tool.

For this process we are looking for positional accuracy not diametric as we will tell the software what size we want for the holes when it comes time to drawing the flange.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%206.png)

During scanning artefacts will become obvious.

It is why it is best to do this part of the process while having access to the physical part.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%207.png)

We can see that there is a variance in our hole making it not round.

This could be damage to the casting, inaccuracy in the scanner, or in our case it was a clump of scanning powder (talc powder) that stuck to the side of this stud hole.

Also while you have the physical part, it is good to double check dimensions.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%208.png)

In our scanned part we have a distance of 363.94mm from the furthest studs. 

I am unable to measure this with the equipment I have but it would be safe to assume that this distance should be 364.00mm.

2 Stud positions we can measure are the top 2

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%209.png)

We get a position of 189.869mm

Measured with a Pair of Mitutoyo Digital callipers I get a measured distance of 189.90mm which is well within manufacturing specifications of a casting.

Next we are going to draw the port shapes. 

What we will learn from this process is that castings can have variance in them. Some intake ports often vary and in some circumstances (such as on the JZ engine) they can be completely different shapes on the same cylinder head.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2010.png)

When we try to draw a 3 point circle on the first port we can see that the port isn’t a ‘slot’ shape.

From the trumpet tutorial we are going to call upon the spline tool.

First create 2 lines at the top and bottom of the port.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2011.png)

Now draw a spline creating 3 points along the edge of the port.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2012.png)

From the Oil Relocator tutorial we are going to use the fix constraint.

Apply these to our lines so they to not move when applying tangent relationships.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2013.png)

Again as we did with the trumpet tutorial, go through and apply tangent relationships to the spline and the upper and lower lines.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2014.png)

Using the control markers on our spline, pull and push them so we get the desired contour.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2015.png)

Looking pretty good now.

We cannot guarantee that the port will be symmetrical, so repeat the process for the opposite side.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2016.png)

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2017.png)

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2018.png)

Using the Move/Copy tool copy this port to the other 3 locations.

Ensure “Create Copy” is turned on before you move your geometry.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2019.png)

As you process the geometry across the flange do not be suprised if you have to move the geometry up/down to accommodate the casting.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2020.png)

The older the casting, the more this will vary.

When copying our port geometry you will notice that our lines did not translate across.
This is because they have a fixed relationship to the sketch.

we can either delete this relationship before moving the port geo, or recreate it at each location.

I choose to recreate at each position.

This gives me the opportunity to inspect each port position and their shape.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2021.png)

If we are designing a part for a specific head and HP is involved, you may want to tweak and change your port shape to match each one respectively.

However if you are intending to produce a family of parts, it maybe best to do geometry of “best fit”

**NOTE: “Best Fit” is a piece of geometry that is the average of the information recorded into our CAD software.**

Finish our sketch.

During our processing of our mesh you will may have noticed the yellow exclamation mark next to our mesh.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2022.png)

This is the software informing us that our STL mesh body is not water tight or sealed.

It implies that it is not 3d printable.

As we process more and more meshes, we will actually be using the least amount of 3d scanning data as possible to achieve the desired result.

This is because 3d scanning time costs money and less can sometimes be more.
Limitations in the technology also do not allow us to go in and 3dscan inside each of the ports (we explain this in further detail in the 3d scanning course).

Create a new sketch on the front plane and create the outline of our flange.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2023.png)

I turn off the mesh to allow Fusion 360 to operate faster while working with the geometry data we have capture.

Trim for extrusion

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2024.png)

Extrude 12mm

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2025.png)

Fillet

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2026.png)

Turn on our positional geometry and Push/Pull cut our ports through our flange.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2027.png)

Turn our Positional Geometry sketch back on (once Fusion completes an operation with a particular sketch, it will hide it from the view window, we need to go back into the browser and turn this back on)

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2028.png)

Go to the hole function and place 5x M8 through holes at our stud positions.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2029.png)

You may need to toggle the hole direction using the 2 arrows next to the ‘Extents’ option

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2030.png)

Hide our sketches.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2031.png)

Now turn on our 3d scan to check our flange against our freshly created flange.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2032.png)

Now it is to time to Export as an STL and 3d print to check on our cylinder head.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2033.png)

You can split the design into pieces to fit on a standard 3d printer and produce in pieces.

Here we can see a finished 3d printed manifold attached to a 3sge engine

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled.jpeg)

Material Markforged Onyx, car a 1999 Toyota Altezza running a Link G4+ ECU
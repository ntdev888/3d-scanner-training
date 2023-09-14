# L6 - Flange from 3d Scan

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

Like lesson 1 and 2 we are going to create a flange from a 3d scan.

As covered in the Tools and Software portion of the course we will be utilising the functionality of xtract3d.

This is where Fusion360s basic functionality exceeds that of Solidworks.
However for the cost of Xtract3d and the ease of workflow once you have it, I cannot recommend it highly enough.

Start a new blank work document, navigate to the Xtract3d tab and import a new mesh.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled.png)

If you cannot see this tab after installing xtract3d, right click any tabs and see if it is available

Tick it on if it is turned off

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%201.png)

If you STILL do not see it, 

Go to Tools → Add-ins

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%202.png)

Ensure that both ticks are on for Xtract3d

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%203.png)

Failing this, if reinstalling Xtract3d does not work, please go to Polyga for further in-depth support.

Import our 3dscan material that has been supplied with this lesson.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%204.png)

A dialog box will appear. We wish to work in millimeters and all 3d scans are material in millimeters

An option that is turned on by default is 'Centre on Import'

Turn this off as the training material has already been aligned.

Further lessons on how to align 3d meshes for CAD are under the 3d Scanning training material on this site.

In our design tree we can see that the scan information is now here.If we wish to do anything to the 3d scan using Xtract3d, we need to first select the scan here before any options become available to use in the Xtract3d menu.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%205.png)

Now we have a 3d scan of our cylinder head.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%206.png)

Note; 'Smash' is a term used for a quick 3d scan of an item to quickly grab is data.
often repeating geometry or areas of little/no importance is disregarded. 

Selecting the front plane and moving the view in CAD we can see that the front plain has already been aligned to the 3d scan.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%207.png)

We will be using this plane to create our flange from.

Select the front plane → Create a Sketch → View 'Normal to'

As we did in lesson 2, we are going to create a sketch of all our reference geometry, then create other sketches on the same plane that reference this.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%208.png)

Create all the geometry as close to the scan as possible. 

Note that we are creating the reference geometry to create our flange from, not the finished product. This ensures accuracy.

We will then go through and build profiles, and offset clearances on all of our hole positions.

When doing the ports it will be quite common to discover that these are not uniform in shape, constant or even the same across the cylinder head.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%209.png)

We can see that although the upper portion of the port conforms to a standard arc we can see that the lower portion deviates.

We will need to use the spline tool to create the port edges.

First we are going to create some construction geometry to create the port edges. 
Easiest way to start is to draw 2 straight lines ending as close as we can to where the port edge finishes.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2010.png)

Now we create a spline clicking in 3 points

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2011.png)

As we did with the ITB lesson we are going to make the the spline tanget to the top and bottom line in relationship

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2012.png)

Now we have a pretty good start point to adjust our spline to suit the port shape

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2013.png)

Grabbing the Spline control points, adjust these until we get nice smooth curvature of the port.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2014.png)

We have now quickly created a non-uniform port shape quite accurate to what we have scanned

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2015.png)

Repeat for process for the other side

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2016.png)

Select the Port geometry we have just created.

As per lesson 2 lets convert this into a block
Tools → Blocks → Make
Confirm

Copy and past this block and move it over the second port position

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2017.png)

We are fortunate that with this model engine (Altezza 3sge) that the port shape is the same across the cylinder head

Copy and past the blocks 2x more times and align.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2018.png)

Depending on the era of the casting (when in history that it was undertaken) it is common to see between 0.20-1.0mm variation in position and form of some castings. 

The information on casting tolerances is readily available online from many foundries.

At this point it is good dimension the stud positions and do a quick check against the cylinder head.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2019.png)

Setting a Fixed position relationship to the first stud will allow us to make any minor tweaks if required. However their positions appear relatively accurate when measured with a Caliper.

Another quick check we can do is to measure the 'meat' between 2 ports and make sure that this is correct.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2020.png)

Close the sketch and rename it 'Reference Geometry'

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2021.png)

At this point depending on how good your computer is, it might be best to hide our 3d scan to allow Solidworks to do future operations without needing to generate the mesh every time we move our camera to view what we are doing.

Right click the scan in our feature tree and click the eye to hide it from the graphic window.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2022.png)

Now we have our redementry geometry that we can now model a flange from.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2023.png)

Now we want to create a new sketch on the front plane, as we did in lesson 2, create offset edges to our ports to create a flange design.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2024.png)

Now we use my favourite tool, Power Trim.

Use this to leave us with the outer profile shape.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2025.png)

Extrude this 12mm to create our flange.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2026.png)

Next we are going to create the clearance hole for our bolts and our port holes.

Create a Sketch on the front plane → Create circles with the center point on the hole locations → equal relationship these with each other.
Dimension these to be 10mm for clearance on the M8 bolt positions.

NOTE: If you are using gas cut profiling you will want a loose tolerance vs Laser or Waterjet cutting
If we are to waterjet cut this from Aluminum you can tight this right up to 8.5mm
However due to slag, we may get issues if we were to laser cut this size at this thickness.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2027.png)

Next Convert Entities the Port Geometry from the Reference Sketch.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2028.png)

Extrude Cut this through all the flange

Make sure that the direction is correct so that it cuts this geometry away from the flange

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2029.png)

Now we can check to see how our flange is looking compared to our 3d scan

Right click the scan in the feature tree and turn it back on.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2030.png)

At this point I would suggest saving the part as a STL and 3d printing a sample to ensure that the design fits the cylinder head and does not cause any issues.

If your 3d printer is too small, splitting the model in half by cutting a 1mm slit down the middle is helpful.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2031.png)

Extrude cut this through all.

You will be prompted 'Bodies to keep' 

We want to ensure that 'All Bodies' is selected

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2032.png)

When saving for 3d printing, select the face of one half before clicking File → Save as

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2033.png)

Give the file a unique name with a suffix to denote part 1 or 2

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2034.png)

It will now ask what Parts of the solidwork model do you wish to export?

Select 'Selected Bodies'

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2035.png)

When we bring the STL into our 3d printing software we can see that it is only the half that we selected that has been exported.

![Untitled](L6%20-%20F360%20Flange%20from%203d%20Scan%202939cf2ac48a4f7e93df0cf27b55fe41/Untitled%2033.png)

We can now print this and the other half and test fit on our engine.

Inside Solidworks we can roll back the history of what we have done by moving the blue line at the bottom and moving it up above the operation we want to work before.

Doing this we can move before we created the slit and finish our flange with any additional work we wish to do to it such as chamfers pockets, and recesses for port tubes.

![Untitled](L6%20-%20Flange%20from%203d%20Scan%20dd0d1d8a696d485780c37b263f829ab3/Untitled%2036.png)
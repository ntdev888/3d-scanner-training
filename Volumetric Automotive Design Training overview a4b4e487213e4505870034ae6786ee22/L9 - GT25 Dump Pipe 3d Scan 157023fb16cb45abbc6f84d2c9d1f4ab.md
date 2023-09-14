# L9 - GT25 Dump Pipe 3d Scan

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

We are going to produce a GT25 dump pipe to be 3d printed in PLA then investment cast in 304 stainless.

Create a new part → xtract3d 'Import' mesh → select our GT25 3d Scan

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled.png)

Remember to have 'Center on Import' turned OFF when bringing in pre-aligned mesh models.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%201.png)

Create a sketch on the front plane and set view normal to (CTRL + 8)

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%202.png)

It is not helpful for us to be looking at the turbo in this direction, so press CTRL + 8 or select 'View Normal To' again to flip the side of the plane we are looking at.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%203.png)

Create a sketch on this plane and start creating our reference geometry for our rear flange.

Using perimeter circles produce arcs of best fit to the critical geometry we need to capture

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%204.png)

As previously we are going to draw tangent lines between our circles for our port holes and power trim away the un-needed geometry.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%205.png)

Close the sketch and label this 'Reference Geometry'

Create a new sketch on the front plane, offset entities tool create a profile from the Reference Geometry to get the basic outline for our flange.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%206.png)

Powertrim

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%207.png)

Extrude 10mm and create.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%208.png)

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%209.png)

Next we are going to 'Cut' our holes for our exhaust ports and our stud holes.

Starting with the studs, create a sketch on the front plane, then draw center circles on the 5 points for the studs.

Give these created circles an equal relationship to each other.

Dimension these for clearance on our studs. 
As this part will be investment cast so we will need to have a little bit of clearance on our bolt holes to allow for any defects in the casting process.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2010.png)

Extrude Cut through all.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2011.png)

Front Face → Sketch → Select port geometry → Convert Entities

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2012.png)

Extrude cut, through all

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2013.png)

Now we are going to fillet the stud positions to the outer flange profile.

Discussed before we want to avoid adding fillets to our sketches where possible, 
but now we do not want to leave it to the end as we will be using this profile shape to help us with our design process.
We will be creating advanced geometry using the lofting tool which can conflict with the fillet tool when used at a later stage.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2014.png)

I have used a 10mm Radius, however smaller or bigger is fine.

We now have a flange that if we want can be laser cut for fabrication.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2015.png)

I would also suggest at this stage to do a 3d print of this component for checking and fit.

As we did last time we are going to create some construction geometry that we will be using to drive the profile and paths for our design

First we will create a new sketch on the Right Plane to create the path for our dump pump.

Create a horizontal construction line going from the flange face to the left of our part
Then create a 3 point spline starting from the end of this construction line and create the general shape of the dump pipe path.

Tangent relationship the spline to the construction line.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2016.png)

What we need to consider, and what is covered in the design intent, we need to know what size exhaust we are going to run and what flange type we are going to use.

For this we are going to model a 2.5" exhaust off the turbo and use a standard 2 bolt exhaust flange.

To get a representation of this flange, draw a construction line.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2017.png)

Select the end point of the spline and the line, create a midpoint relationship between them

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2018.png)

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2019.png)

Next, select the line and the spline and create a Perpindicular relationship between the 2

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2020.png)

Now our construction line will follow our spline and always be 'end on' to it.

Add dimension between the line and the flange face using the dimension tool and set it to 55 degrees.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2021.png)

It is always worth while to put in visual aids wherever process when designing.
The more the better.

For this reason I have create a construction line that represents the firewall for this project.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2022.png)

I can see from this that I either need to increase the angle of my dump pipe or reduce the distance.

It is also good to add the dimensions to your flange as well.

I have increased the angle to 80 degrees and added 82mm outside edge to my flange.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2023.png)

This shows I have good clearance to the firewall and our dump pipe should be able to removed off the turbo without needing to take the turbo off the exhaust manifold.

Close this sketch.

Now we are going to create a plane at the end of our spline, similar to what we did with creating the thread in the Gear Knob lesson.

Feature → Reference Geometry → Plane
Select the Spline end point and the spline itself.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2024.png)

We have now created our reference plane.

This plane is needed to create the geometry for the 2 bolt exhaust flange.

We are essentially creating the 2 ends of our dump pipe, then we are going to transitionally morph the shape from the turbo to the exhaust flange.

Select our new plane → Create Sketch

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2025.png)

Below is a drawing of a 2.5" exhaust flange that is available lasercut off the shelf where I am (New Zealand), however it is best to purchase and source this flange before designing the turbo dump pipe.

Create the horizontal construction line first, create a relationship between the center of this and the end of our construction spline.

Use this line as the hole center dimension between the 2 bolt holes and draw all the geometry around this

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2026.png)

Power trim

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2027.png)

Extrude this 10mm for our exhaust end

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2028.png)

Looking pretty good.

Now comes the fun part, we are going to create the transition from our exhaust port shape to a 2.5" round.

The process we are going to use is

Loft Using Centre line → Join → Loft Cut

I like to visualise all the possible issues that could appear as I go through designing the part.
For this reason I create a sketch on the face of the Turbo flange.
Then using the polygon tool, create a 6 sided polygon centered on one of the stud positions with the dimensions of the nuts I am planning to use.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2029.png)

From this we can see the maximum offset we can have to clear our nut when fitting.

Using the measuring tool I measure from the polygon point to the edge of our port.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2030.png)

We can see we will be pushing our luck if we want a wall thickness more than 2mm, but when it comes to investment casting, particularly a turbo dump pipe we want at least 3mm if not more of material.

This is the 'Many ways to do the same task' point.

We could extrude it at 3mm offset, then hand finish the final part, or source cap screws to fit the turbo.

However we are going to get a little creative.

Create another sketch, create center point circles on the stud positions with equal relationships
Then create a dimension from the end of the nut to the edge of the circle.

If it keeps trying to dimension from this point to the center of the circle, hold the shift key while selecting points to add a dimension as per below.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2031.png)

Close this sketch, and create another one on the flange face.

Convert Entities the main port hole, and the 3 circles we just created that break into the port space.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2032.png)

POWER TRIMMMMM

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2033.png)

Now convert the stud holes and the outer profile of our flange.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2034.png)

Extrude this 5mm

Fillet the 3 ledges we have created 4mm to blend the transition

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2035.png)

If we hide our 3d scan we can see the fillets we just created

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2036.png)

Fillet the transitional edges of these by 4mm to get a nice blend.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2037.png)

NOTE: "I thought we did all the filleting at the end of the design?"
We are going to use the inner profile these fillets create to drive our geometry for our lofted transition.
If we don't do this now, we will not get a smooth transition from our Exhaust shape to our 2.5" hole.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2038.png)

Create a new sketch on our flange face, then use the offset geometry tool from the port edge to create our outer dump pipe shape.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2039.png)

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2040.png)

Close this sketch and do the same on the 2.5" exhaust flange, offset from the exhaust hole.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2041.png)

Open the loft command and loft between these 2 sketchs.

You will get the below result

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2042.png)

I have highlighted the 'Centerline Parameters' menu as it is usually minimised when using this tool.

However we want to add our spline to the loft too so that we get the outcome we want.

Maximise this, and select our spline

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2043.png)

We now have our external transitional shape.

It is good to rotate the part around and ensure that the shape does not twist or distort.

If it does move the green markers around until you have a smooth uniform shape.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2044.png)

Scroll to the bottom of the menu and TURN OFF 'Merge Results'

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2045.png)

We are going to hollow (Shell) out this shape before we attach it to our flanges.

Once you have turned off merge results, confirm by clicking the green tick.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2046.png)

Go to the solids folder in the feature tree, right click and hide our flanges and the turbo scan.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2047.png)

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2048.png)

---

Now we are going to execute the shell command on our loft.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2049.png)

Select the 2 faces and set the shell parameter to 3mm for our wall thickness.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2050.png)

You will likely get this warning, agree and let it process.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2051.png)

Congradulations you have now created a piece of very complex geometry within Solidworks

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2052.png)

We now need to attach this to our flanges.

Unhide our flange solid bodies.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2053.png)

For this we will be using the Combine tool.

Go; Insert → Features → Combine

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2054.png)

Now select 'Add' and click on all our solid bodies on the screen.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2055.png)

Use the section view tool in the graphical window to ensure that no twisting or anomilies occur in our finished part.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2056.png)

One last thing we are going to do is improve the strength of our dump pipe by filleting between the flanges and the transition.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2057.png)

Add a 1.5mm fillet all around both edges.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2058.png)

Remember to save often doing projects like this. Nothing is more painful then loosing hours of work for some unforeseen reason. (during writing this tutorial my computer did a windows update and rebooted without my knowing)

We are done

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2059.png)

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2060.png)

Now we can export as an STL 3d print and test fit to our turbo.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2061.png)

---

# Note; The below process failed, and sometimes it will. For this reason we had to do a more complex shell then join body operation.

However I have included this process in the lesson to show that even when things go wrong, there is always another way to succeed.

---

Unhide our flange solid bodies.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2062.png)

We are going to combine all of our parts together before cutting away the inside of our dump pipe.

Go; Insert → Features → Combine

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2054.png)

Select 'Add' then pick the 3 bodies we wish to combine into 1

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2063.png)

Confirm this operation by clicking the tick.

We are going to repeat the process we did before for lofting but this time we are going to cut away the profile from the dump pipe body.

Create a sketch on the inside face of the turbo side of our dump pipe, while it is highlighted blue, select 'convert entity' 

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2064.png)

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2065.png)

Close the Sketch and repeat the same process at the Exhaust end of the dump pipe

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2066.png)

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2067.png)

Close the sketch.

We may need to expand the previous lofting operation to retrieve the spline sketch that we need to drive our loft Centerline Parameter.

Click the small arrow next to the loft command in our feature tree.

If it is hidden, right click the relevant sketch for the spline and press 'Show'

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2068.png)

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2069.png)

Now we are going to use the loft cut command in the same way we used loft.

You can find this on Features → Loft Cut on the tool bar.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2070.png)

Click on this command and begin.

Select the 2 sketches we just created that represent the inner dimensions for our dump pipe.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2071.png)

Like before, the Centerline Parameters menu is hidden

Expand this and select our centerline spline.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2072.png)

Confirm the command by clicking the green tick.

NOTE: This process failed no matter which way it was adjusted.
Shelling the shape before combining will always yield better results, however this method will work when shelling failures and vice versa.

![Untitled](L9%20-%20GT25%20Dump%20Pipe%203d%20Scan%20157023fb16cb45abbc6f84d2c9d1f4ab/Untitled%2073.png)
# L8 - ITB Manifold from 3d Scan

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

We are going to draw a ITB Manifold to 3d print in Carbon Fiber Nylon.

This works very well and Volumetric has designed and made dozens ITB Manifolds in Onyx material.

Create a new Part in Solidworks → Xtract3d → Import 'Mazda BP Head Flange - Aligned.STL'

Ensure 'Center on Import' is turned off.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled.png)

When we create a sketch we can see that the head is 'upside down' this will be difficult to model from as it will be disorientating to work with.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%201.png)

Select the Sketch in the feature tree, go into Xtract3d and press 'Move Mesh'

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%202.png)

We can now manipulate our mesh in solidworks.

Looking at the Triad in the bottom left corner we can work out which axis we need to rotate around.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%203.png)

For this situation we need to rotate around the Y axis. 

Go into the move mesh window and put 180 in the Y axis rotate dialog box.

Press tab and the mesh will visually update on the screen.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%204.png)

Press the green tick and confirm the changes you want to make.

Click on the top plane and create a sketch.

We can see that our scan is the 'right way around'

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%205.png)

Go through and draw the ports and and hole positions

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%206.png)

Drawing a horiztonal line, then a line from the hole centers of the ports we can see that the head is on a 0.67 degree tilt.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%207.png)

We can fix this by selecting the scan → Xtract3d → Move Mesh and putting this value into the Y axis rotation.
Dont worry about our sketch just yet, we will fix that too.

We can now see that all of our work is now out of position.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%208.png)

However we can fix this using the 'Rotate Entities' tool under 'Move entities' menu

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%209.png)

Execute this operation and select all the geometry you wish to rotate

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2010.png)

For the 'Center of Rotation' we are going to select the part origin from the feature tree

Click on the red triad in the middle of the sketch

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2011.png)

Now put 0.67deg into the rotation amount dialog box.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2012.png)

Press Tab, and we can see our sketch updates in the graphical window.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2013.png)

Confirm the action by clicking the green tick.

Delete our 2x measurement lines as we no longer need these.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2014.png)

Close the Sketch and name it 'Reference Geometry'

On the Top plane create a sketch and create the outline for our flange.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2015.png)

Power trim

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2016.png)

Extrude this 12mm
Note: I use 12mm as it is fairly close to 1/2" material this gives us more options if we choose to use this design for fabricating and decide to profile cut this from plate instead. It will have little influence over the final design if the material is 12.25mm as plate material can have a variance of +-0.5mm from the steel merchants.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2017.png)

Now it is time to create our ITB flanges.

Create a reference plane 60mm above our top plane.
Features → Reference Geometry → Plane

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2018.png)

Confirm and create.

Create a sketch on our new reference 'Plane 1', and import the 'SilvertopITB-Flange' Block supplied with the training material.

Tools → Blocks → Insert → Browse → SilvertopITB-Flange.SLDBLOCK 

When we look at the block we can see the letter F 

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2019.png)

This is backwards, which means that the block is the wrong way around relative to our sketch face.

Create a Center line from our sketch datum going up.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2020.png)

Select Mirror entities with no geometry selected.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2021.png)

Under 'Entities to Mirror" select our Flange Block
Untick the 'Copy' function
And select our center line under "mirror about"

A preview ghost will appear showing us what our results will be

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2022.png)

We can see that our F is now the right way around.

Confirm by clicking the green tick.

When setting the locations of the ITB positions we need to consider 2x things.

- Will we use the factory linkages?
- do we want the throttle cable at the top or bottom of our manifold

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2024.png)

I always like to use as much factory features as possible, this reduces the need to 'reinvent the wheel'

For this reason I am going to space my ITBs at the factory distances.

Copy and past the ITB Block 3 more times, align them horizontally from each other and draw a construction line 89.5mm long between the centers of each.

I draw 3 lines, connect them horizontally to the blocks, give them equal relationships
Then dimension 1 of them

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2023.png)

If we quickly mock up our newly created sketch over our reference geometry we can see that the port spacing ever so slightly creeps out of position if we make the first flange center to the cylinder head port.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2024.png)

for this reason I am going to centralise the ITB spacing so that it is even across the whole manifold.

Move the ITB Flange geometry out of the way by dragging it down.
Create a construction line diagonally from the end point of one port arc to the other.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2025.png)

Using this we will be able to centralise the ITB flanges relative to the 

Note: "Why not just create a horiztonal line between the 2x arc centres?"
Solidworks does not like geometry that is overlaid ontop of each other, particularly in the same sketch. It also makes it difficult to tell if there is an issue or if you have succeed in aligning features.

Hover the mouse cursor over the middle of the center line on our ITB flange, the center point will appear and allow you to select it. 

Do this, then holding the control key do the same for the diagonal line we have just created for our head flange.

Make these 2 points coincident 

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2026.png)

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2027.png)

Close the sketch, name this 'ITB Reference'

Create a new sketch on reference 'Plane 1' and convert entities the profiles of our ITB Positions.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2028.png)

I have learnt from producing a few of these manifolds in Carbon Nylon that the spring resistance "prys' the flanges apart from each other. 

For this reason we are going to add a stiffening brace into our design. We need to consider the articulation of the linkages so this will be across the top and bottom of our flanges.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2029.png)

Power - Trim

Extrude our ITB Flange downward 12mm

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2030.png)

It is time to join our 2 flanges with our ports.

To do this, I am going to create a sketch on the reference 'Plane 1' and offset geometry 5mm from the port shape for the first port.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2031.png)

Confirm and close the sketch.

Do the same, create a sketch on the top plane for our Head intake port → Offset Entities → 5mm

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2032.png)

Confirm and close our Sketch.

We are now going to Loft extrude our oval to our circle.

Go to Features → Loft Base/Boss, then select the 2 sketches we just created

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2033.png)

And Confirm

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2034.png)

Looking good.

Note: "Why did we loft through the flange and not up to the top face?"
When we go to loft cut away the runner, we want the transition to go from the ITB Port shape to the Intake port shape as smoothly as possible.
If we did it off the top faces we would have parallel sections which will only affect the airflow slightly, if we have the opportunity to produce the best results possible without any additional work we might as well do it.

Next Create a Sketch on Reference 'Plane 1' and 'Convert Entities' the ITB Port for the first runner.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2035.png)

Close the sketch.

Create a new Sketch on the top plane and 'Convert Entities" our intake port for runner 1.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2036.png)

Confirm and close our Sketch

Now we are going to do a loft cut from our ITB Port to our Runner Port.

Features → Loft Cut

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2037.png)

Select our newly created sketches and confirm the operation.

Make sure that the transition marker is not twisted.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2038.png)

Confirm.

we now have our first runner completed!

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2039.png)

In real world applications this is really handy for more complex port transitions such as Blacktop ITBs to Oval ports.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2040.png)

(Dummy ITB Manifold for test fitting Volumetric NZ 2018)

To keep things tidy lets do some house keeping in the Feature tree.

Select the 2x operations we have just created (Loft Bose and Loft Cut) 

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2041.png)

While holding the CTRL key left click on them and select "Add To New folder"

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2042.png)

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2043.png)

Name this folder "Port 1"

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2044.png)

At this point I suggest saving your part.

Repeat this process for the other 3 Ports.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2045.png)

Lets start finishing this manifold and add some holes.

For the top face for the M6 holes I am going to use the 'Hole Wizard'

Features → Hole Wizard

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2046.png)

Screw holes will be Threaded, ISO Tapped Hole, M6

Unlike the Oil Relocator tutorial, we want to set the holes to be "up to next" not "through all"

This is because we do not want the holes to extend through into the head flange.

Once set, select the Position tab and pick the ITB Flange face in the graphical window.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2047.png)

Select the center points of our 12 hole positions

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2048.png)

Press the green tick to confirm the results of your operation are correct.

Now when we print these, they will be the correct size for tapping with an M6 Tap.

In the feature tree go through and hide the planes we have been using and the 'ITB Reference Geometry' sketch.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2049.png)

This will take away some of the clutter on screen.

Now create a sketch on the top plane and draw center point circles on the stud locations.

Give these equal relationships and dimension one to 9mm for clearance on the M8 studs.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2050.png)

Extrude cut → "up to next" instead of "Blind" under the Direction 1 option

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2051.png)

Confirm.

Now is the time to jazz up the look of our manifold.

Liberally fillet everything.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2052.png)

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2053.png)

This fillets will help transfer the weight and load of our ITBS from the ITB flange to the runners and manifold.

Depending on how long these runners are a brace maybe made which we will go over in the ITB Plenum lesson.

Note: "How will we screw a nut up to the M8 studs on the lower portion of the manifold?"

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2054.png)

When designing we will come across circumstances like this (particularly when working with turbos and exhaust manifolds)

We are going to cut away clearance for our nut on our manifold.

Select the top face of the Head Flange and create a sketch.
A fast way to do this is to select the face or plane you wish to sketch on, then right click the "sketch" icon to create one.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2055.png)

Create center point circles on the stud locations

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2056.png)

Give them equal relationships.

Before we give them a dimension it is best to check what clearance a nut will need.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2057.png)

We can see that to clear the rotation of our nut we need an absolute minimum of 15mm clearnace

For this reason we are going to give 0.5mm extra a side on this and dimension our circles at 16mm diameter.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2058.png)

We are now going to extrude cut upwards toward the ITB Flange

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2059.png)

At 12mm we can see we will clear the stud, however from our chart we need an additional 6.5mm (dimension 'm') 

To quickly do this we can use all Solidworks dimension dialog boxes as calculators.

simply type '+6.5' after the 12mm in D1

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2060.png)

Press tab and the preview will update in the graphical window.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2061.png)

Press the green Tick to confirm.

Add a 2mm fillet to the bottom edge of this new recess.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2062.png)

Go through and add fillets to the edges of this cutout to smooth out the appearance of our manifold.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2063.png)

Go through and continue adding fillets and chamfers to the edges to improve the aesthetics of the part.

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%2064.png)

Remember we do not want to fillet the insides of the intake port as we want this to match our cylinder head and ITB ports as closely as possible.

Print samples to dummy fit and check on the cylinder head in low cost PLA

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled.jpeg)

(Test ITB adaptor and ITB Mockup in front of Production ITB Adaptors and Trumpets made from Carbon Nylon-6, Volumetric NZ 2019)

![Untitled](L8%20-%20ITB%20Manifold%20from%203d%20Scan%20a0dd9c4e68e6420c9284429887dd1115/Untitled%201.jpeg)

Port alignment of Trumpet → ITB → Manifold → Intake port as smooth as possible
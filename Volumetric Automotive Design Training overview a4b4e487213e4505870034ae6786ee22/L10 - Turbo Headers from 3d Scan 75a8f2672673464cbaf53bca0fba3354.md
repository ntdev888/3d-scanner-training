# L10 - Turbo Headers from 3d Scan

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

Create a new part → Xtract3d → Import Mesh → "3sgte exhaust manifold t2 - aligned"

Ensure that "center on import" is turned off.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled.png)

We now have our factory 3sgte manifold with a CT → T2 adaptor on it.

The car currently has a dump pipe and plumbing all fabricated to fit.

What our design outcome for this project is to design → 3d print → Cast a bolt in replacement for the current setup.

The first thing I am going to do is 'show' the Front Plane so I can check that the mesh is aligned.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%201.png)

The first thing I am going to do is create a Reference Plane on our T2 flange face.

Go to the Xtract3d Tool bar and click 'Create Plane'

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%202.png)

The create plane Menu will appear on the left hand side.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%203.png)

What this now allows us to do is to create a plane intersecting 3 points on our mesh. 

The advantage of this tool as well is if we have a rough surface we can create dozens of points.
'Create Plane' will generate a plane of best fit through all of them.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%204.png)

If you make a mistake and click on a part of the mesh you don't, click delete last and it will remove it.

Once you have a plane that looks like it is smoothly intersecting the flange surface click create.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%205.png)

We now have our 2 reference faces to create our flanges on.

Select the front plane and create a sketch.

Draw the hole positions using 3 point circles and draw in the ports.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%206.png)

Use the skills we have learnt in the previous lessons to 3 point circle → power trim → convert to block the port hole.

Then copy and past them to the other 3 positions.

One thing that will be surprising is the cylinder furtherest from the Turbo flange (cylinder 1 on the engine) is bigger than the other 3, by quite a lot.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%207.png)

As I have said previously, some engine manufacturers will often have different port shapes across the same engine that are not uniform. 

The 3rd gen 3sgte is one of those cases. (a VW VR5 is even more shocking)

To address this, we are going to dissolve the block so that we can edit it, and move the port edge across to the left to give a better port match.

Right click the block, and go down to 'Explode block'

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%208.png)

Now move the arc across by selecting its center point, clicking and dragging to the left

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%209.png)

close the Sketch and name this "Reference Geometry Head"

Now click on our new reference 'Plane 1' and create sketch.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2010.png)

The view will be from the wrong side, press CTRL + 8 to flip the view.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2011.png)

We can now draw the T2 flange position.

In the resource folder for this lesson you will find a T2-Block, import this into the sketch on the Turbo reference plane.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2012.png)

You will immediately notice that the adaptor stud positions match the T2, but not the outlet hole.

This adaptor was causing the customer a lot of issues blowing Turbo gaskets.
We can see here that the exhaust gas would be hitting the gasket face, over time this will errode the gasket prematurely and cause it to blow.

It is reasons like this that you need to check "off the shelf" parts from aftermarket manufacturers.

Close the Sketch and name this "Reference Geometry Turbo"

We are now going to create a 3d Sketch.

This is a very useful tool for creating frames, roll cage paths, and exhaust tube paths.
The critical thing is to tie these 3d sketches to 2d sketches and planes. This stops issues with geometry becoming warped, twisted and disapearing into the infinite ether of our model.

Under the Sketch Tool part, press the arrow below the "Sketch" icon and click "3d Sketch"

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2013.png)

We will model a bit differently by keeping our model in an Isometric view, rather than looking end on to faces. 

This allows us to keep track of what we are doing in our workspace.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2014.png)

We are going to create some centre points for our 4 port locations.
To do this, we are going to create diagonal lines from the end of each arc point.

Click the line tool and select the end point of one port arc.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2015.png)

Select the diagonally opposite point of the opposite arc.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2016.png)

Convert the line to a construction line by ticking "For Construction" in the lines dialog window.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2017.png)

Repeat for the next 3 ports.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2018.png)

We are now going to create lines create construction lines perpindicular to the centre points of these lines in the -Z direction.

Like we did in the ITB Trumpet lesson, we are going to use these lines as tangency for our exhaust gas Paths into our T2 Flange.

This allows us to create nice smooth curves flowing out of the exhaust port and into the turbo.

Click the line tool and select the centre of one of the construction lines we have just created.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2019.png)

Now click anywhere on the screen, be careful to not click the end points of any other sketches.

A red 'Triad' will appear showing us the directions it wants to draw the line in.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2020.png)

At the moment it is wanted to draw the line on the plane that the port hole is drawn on.

Press the Tab Key to change the triad so we see this.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2021.png)

Click anywhere on the screen to create the line, ensure that it does not 'snap' to anything.
We are going to use relationships to set the direction of this line.

Select our newly created line, and the Front Plane.
In the Line properties Dialog box, select "Normal"

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2022.png)

We can now see that the line is pointing 90 degrees away from our flange face

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2023.png)

Repeat this process for the other 3 port holes.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2024.png)

Now we are going to do the same for the Turbo Flange centre position (Sketch is hidden in example above)

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2025.png)

Click the port centre with the line tool.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2026.png)

Click anywhere on the screen ensuring a 'snap' relationship is not created.

Below is an example of Solidworks creating a snap relationship.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2027.png)

If we create this line, when we try to create the "Normal" relationship solidworks can show an error telling us that the relationships for this line are "over defined" and turn red.

Always address this problem when it occurs as it can cause terrible headaches later when trying to create features.

Going back, we have created our line starting at the centre of our Turbo flange point and created it with no tied relationships.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2026.png)

Select our newly created line and reference 'Plane 1' and create a "Normal" relationship

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2028.png)

Looking promissing.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2029.png)

We are going to select all these 5 tangency lines and give them an equal relationship.
Tick "For Construction" and dimension one at 50mm

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2030.png)

Now we are going to create 2 point splines going from the centre of the Turbo flange to the end of the Port lines.

Click the spline tool and select the Turbo centre (Turbo Centre Tangent Line) and then click the end of the First Port Tangent Line.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2031.png)

Now Select our newly created Spline and the Port Construction line.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2032.png)

Create a Tangent Relationship between the 2

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2033.png)

Now do the same for the spline and the Port Tangency line.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2034.png)

Create a Tangent relationship

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2035.png)

Repeat the process for the other 3 ports all converging on the same Turbo Tangency construction line.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2036.png)

I have hidden the 3d scan to make it easier to see the runner paths.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2037.png)

Now we have the tangency relationships, we can adjust the curvature control points to increase the angle of attack into the turbo.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2038.png)

This runner is quite short, to adjust this we can take the spline control point on the turbo side and drag it up.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2039.png)

Now our runner path has a bit more flow after some tweaking

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2040.png)

Do not worry, when it comes time to modelling the actual runners in, we can adjust at this point as well making the path cleaner and more uniform.

Another handy tool is to convert the splines to 'Style Spline's'

Do this by selecting the spline, and clicking "Convert to Style Spline"

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2041.png)

We now have the control points and "angle of attack" of the splines that we can now manipulate.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2042.png)

Once we have an approximate path shape that we like, we can close our 3d sketch.

To do this, you need to click the arrow under sketch again and Toggle '3d Sketch' 

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2043.png)

As we did with our Intake manifold and Turbo Dump pipe in previous lessons, we are going to 'Loft Extrude' the runner path using our 3d sketched splines as centre paths.

First we need to select the 'Front Plane' and create a sketch on it.

Offset Entities the first port and set it to 3.50mm

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2044.png)

This is a good thickness for our casting material.
Cast Stainless is a little viscous (like Honey) when casting with, the smoother we design the flow of material in the cast part the less likely we are to get air pockets or voids.

We are now going to do something different to what we previously do when lofting.

We are going to convert our newly created offset geometry into a fit spline.

This helps the software with lofting a uniform and smooth shape and stops inflection and self intersecting issues you run into.

Select the geometry then go to;

Tools → Spline Tools - > Fit Spline

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2045.png)

It will give you the 'Fit Spline' Dialog box

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2046.png)

The lower the tolerance, the closer our spline will be to the original geometry that we are 'Fitting'

If we do not delete the geometry, we are able to update this spline as it will be offset referenced to our port shape.

Once completed we have a fit spline over the top of our original geometry.

As discussed earlier, we try to limit overlapping geometry as it is difficult too tell that there are entities stacked on top of each other.

We can only tell when we select the shaded area and see that this is in fact a closed spline.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2047.png)

Repeat the process for the other 3 ports.
Keep each port geometry in their own Sketch. 

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2048.png)

Once completed, we are now going to do the same for the Turbo exhaust port.

Create a sketch on reference 'Plane 1' and offset entities 3.50mm the T2 Port hole.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2049.png)

Convert to 'fit spline'

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2050.png)

Close the Sketch.

Now is a good time to go through an name the sketches to easily keep track of them through the lofting process.
We are going to repeatedly use some of the same sketches (Turbo Port and Spline path) in every process.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2051.png)

We are now ready to loft our first runner.

Select 'Port 1 Offset' and 'Turbo Port Offset' sketches.

then select Features → Loft Boss/Base 

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2052.png)

We will see that, just like our Turbo Dump Pipe we have an undesired loft result.

Click the 'Centerline Parameters' dialog box.
Once this is open, we are going to right-click in the graphical window to get to our selection options.

We are now going to use the 'Selection Manager'

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2053.png)

What this tool does, is allows us to select 'parts of a sketch' to drive attributes in a feature.

Click it and the 'SelectionManager' window will appear.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2054.png)

Now this is here we want to select the centerline that is our runner path from the 3d sketch. 
Do this by left clicking on it in the graphical window.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2055.png)

It will turn pink and a green tick will appear in the selection manager. 
Confirm that this is correct and press the Tick.

Now the port runner will conform to the centerline path

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2056.png)

Adjust your green control points until you get a smooth uniform transition

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2057.png)

Click the Green tick to confirm that you are happy with this result.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2058.png)

Now we have our first runner!

We need to do some house keeping to be able to do the other 3.

Go to the Feature Tree and expand the "Loft" we have just created.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2059.png)

Right click on 'Runner Spline Path' and 'Turbo Port Offset' and set these to visible by clicking on the 'Show' Eye

They will turn blue in the feature tree and reappear in our graphical window.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2060.png)

Select the 'Port 2 Offset' and 'Turbo Port Offset Sketches' 
Loft these.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2061.png)

If you do not get a result straight away, you may need to move the green control points around until you do.

As before, select the 'Centerline Paramaters' box → Right click graphical window → Selection Manager

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2062.png)

Select the second spline path for our runner centerline.

Confirm in the selection manager and have a look at the preview in the graphical window.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2063.png)

Mark sure 'Merge Results' is turned on.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2064.png)

We now have 2 runners!

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2065.png)

Repeat the process for the next 2 runners. Ensure that the results are as smooth as possible.

If we want to see our results free from the clutter of our construction geometry, we can press the 'Show/Hide' eye at the top of the graphical window.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2066.png)

This allows us to hide all sketches and planes without needing to go through and manually turn them on and off in the feature tree.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2067.png)

If you have reached this point and haven't saved yet, I highly suggest you do

When we go to cut the exhaust gas path through the runners, we want them to flow as nicely as possible up to our flange face.

For this reason we are going to extrude the solid pieces of the flanges first before loft cutting away the inside of our runners.

Create a sketch on reference 'plane 1' → convert entities the outside profile of our T2 Flange.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2068.png)

Extrude this 15mm thick.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2069.png)

Now go to our Front Plane and create the profile geometry of our exhaust flange.

I do this by quickly creating "Offset Entities" off my Reference Geometry.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2070.png)

Do some tweaking and changing to get your designer result.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2071.png)

Extrude this flange 15mm

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2072.png)

Confirm

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2073.png)

This is starting to look like a super slick turbo manifold.

SAVE

Create a Sketch on reference 'Plane 1', instead of converting entities this reference geometry, instead we are going to go;

Tools → Spline Tools → Fit Spline

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2074.png)

Solidworks will overlay the fit spline on-top of our port hole.

Ensure that the tolerance is as low as possible, then confirm.

Close the Sketch and name it "Turbo Port"

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2075.png)

Select the Front Plane and create a Sketch, select the first cylinder port geometry from the Reference sketch, and again;

Tools → Spline Tools → Fit Spline

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2076.png)

You have noticed that we have a tolerance of 0.03mm, be aware of what your foundries casting tolerances are and aim to have variations less that 25% of this.

In our situation, we are expecting a casting tolerance of 0.50mm, so a variation on our model of 0.03mm is very acceptable.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2077.png)

Confirm, close the sketch and name this "Port 1"

Repeat the process for the other 3 ports.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2078.png)

Now we are ready to Loft Cut our Runners.

One thing I like to do, is go through and document where my control markers are for each runner.
When it comes time to doing the loft cut, we want our 'loft cut' to be as close as possible to our 'loft boss'.

I do this by creating a Document and storing screen shots of each operation in it.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2079.png)

When it comes time to do the loft cut we are going to use the exact some process as we did for the Loft Base/Boss process.

However this time we are using the runners internal geometry instead of the external.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2080.png)

First, reference your document and move the markers to the same positions on the profile as your Loft Base process.

Select the Centerline Parameters box → Right click in the graphic window → SelectionManager

Then select the Spline path of the first runner.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2081.png)

Once confirmed you will notice you do not see any result.

However if you rotate the model around you will see the preview shows the subtraction from within the model.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2082.png)

Confirm. You have now cut your first runner path.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2083.png)

At the end of modelling this manifold we will go through and check to ensure no twisting or anomalies occur within the manifold we cannot see.

Repeat the same process for the other 3 port positions.

Remember the Turbo Port Position will be hidden within the Loft Cut feature we just created.
Expand it to be able to select it.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2084.png)

The first 3 runners have been no trouble.

However the 4th runner is failing when doing an Loft Cut.

This is because too many surfaces are finishing at the same point causing the software the create 3 sided surfaces (these are bad, CAD software can only work with 4 sided surfaces)

Note: Even if you visually see a 3 sided surface in the software, I can guarantee that if you take the raw code used to describe it, the CAD has snuck a very short straight line creating 4 corners on the shape)

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2085.png)

We are going to use a different method to creating the final runner.

We are going to model the material we wish to subtract as a solid body, then shift it a very small amount towards the head (to stop this surface intersection from happening causing errors)

Then Subtract this solid away from our model.

First select the 2 sketches 'Port 4' and 'Turbo Port' then select Loft.
Select Centerline Parameters and using the selection manager pick our Runner Spline.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2086.png)

This time we are going to turn OFF 'Merge Results'

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2087.png)

We now have a solid body inside a solid body.

Next we go to the Direct Editing tool bar and select 'Move/Copy bodies'

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2088.png)

If you cannot see this tool bar, right click anywhere over the tabs and you will have the options to Show/Hide tool bars that are available.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2089.png)

After selecting the 'Move/Copy Bodies' the feature dialog box will appear.

Expand the feature tree in the Graphical window and select our Loft body we just created.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2090.png)

Down the very bottom we have the "translate button" Select this.
Put the value in the Z direction and put in -0.30mm (we may need to increase this value at the next stage)

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2091.png)

Under the Direct Editing menu we have the "Combine" command.

Select this.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2092.png)

What we want to do with this feature is subtract the Loft we created away from our manifold.

Select Subtract and use the feature tree in the graphic window to populate the manifold body for our "Main Body" and the Loft we created for runner 4 as our "Bodies to combine"

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2093.png)

Confirm.

Note: If you get the below Rebuild error, go back to your 'Body Move' command and increase the offset.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2094.png)

This is Solidworks Showing us that it was not successful in creating this operation.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2095.png)

Success, we have modelled our runners.

Using the Section View tool, toggle to the Right Hand plane in the options window.

Then slowly Drag the Arrow circled below and check that the material does not narrow or show any visual defects in the design.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2096.png)

The term 'Water Tight' will often get thrown around for advanced Solid Models (such as this).
It means that all the surfaces seal the model creating a solid body that we can 3d print.

If the blue area of the section view disapears, flashes or changes colour while moving the section view, one of the loft commands has failed to form properly.

This is not unusual to occur on these complex models. 
If it does happen, go back the the offending operation and tweak the green control points and check. Repeat until the anomaly goes away.

Now it is time for fillets and holes.
We are going to do the holes after the fillets as when we cast the final manifold these will not be in it.
Instead we are going to post drill the hole positions so there is no issues with voiding around this area.

Select the intersecting joins of the runners and the edge where the runners meet the Turbo flange.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2097.png)

Make this the largest fillet possible. Then confirm.

Go through the Head Flange face and fillet the bolt locations to the flange body.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2098.png)

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%2099.png)

When putting the runner fillets in, make sure there is clearance between the bolt head and the fillet.

We want that bolts to be able to tighten evenly down against the face of the flange.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20100.png)

SAVE

Now it is time for our bolt holes.

Create a sketch on our front plane;

Draw centre point circles on our bolt positions → Equal Relation ship → Dimension 12mm

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20101.png)

Extrude cut → Direction: "Up to next"

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20102.png)

On our turbo flange we are going to use hole wizard and place our 4x M8 tapped holes.

Go to Feature → Hole Wizard

Tapper, ISO, M8, Up to Next

Then select our 4x Hole positions from our T2 Reference Sketch

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20103.png)

Confirm.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20104.png)

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20105.png)

We now have our T2 Turbo Manifold for a ST165 3SGTE Celica

Showing our 3d Scan we can see that it occupies the same space as the manifold that we know works.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20106.png)

At this point you want to 3d print and test fit the manifold.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled.jpeg)

Manifold test fitted to 3sgte - this design is from 2019.

Once we know everything fits. We want to return to our design.

We are going to make a Casting Configuration of our manifold that will not have the holes in it and scaled to the casting shrinkage.

First Thing, we are going to do some house Keeping.

Select the Groups of Features and Folderise them.
Select All the lofting Boss features and add these to folder.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20107.png)

Do the Same for the flanges into a folder, and the features we have used to create the runner cuts.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20108.png)

Now we are going to go to the configuration manager and create a new configuartion.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20109.png)

Right click "Turbo Headers from 3d Scan" and click "Add Configuration"

Name it Casting Pattern.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20110.png)

After confirming we now have 2 configurations.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20111.png)

This is going to be 2 different versions of the same part.

We want to easily be able to switch between the finished design and the part we wish to cast.

Creating a configuration of the part allows us to do this.

Right click the tool bar and turn "Configurations" on

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20112.png)

This allows us to easily switch between models we are working on.

Now that we are in the Casting configuration we are going to turn the holes off.

Go to the feature tree, Select the 2 features used to create our holes and right click.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20113.png)

Click Configure feature.

A pop-up menu will appear allowing us to supress the features for each configuration.

For our casting pattern we want to set our features to "supress" and apply.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20114.png)

These have now disapeared from our model and are greyed out in the feature tree.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20115.png)

Anything we create from this point onwards in the Casting configuration will not reference these features.

If we change the configuration to Default they will appear.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20116.png)

We want to go back to the casting configuration and we are now going to scale our model for casting shrinkage.

Go; Insert → Features → Scale

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20117.png)

For this scaling we want to select the model and set it to "Centroid" with Uniform Scale turned on.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20118.png)

This is where we can go quite deep down the rabbit hole.

The purpose of these tutorials is to show you the tools and methods needed to produce these components. However there is so much more to know when it comes to material shrinkage through cross section, exhaust gas flow paths, runner lengths and the list goes on.

As the parts accurate features (hole positions) are going to be post machined, we can generally apply a universal shrinkage rate across the whole part.

Note: Discuss with the foundry you are using to see how they approach casting shrinkage in the material you intend to use. If you are casting yourself, you are likely going to need to do several test pours to identify and calculate what your shrinkage rate will be.

The figures below are Broad and "TYPICAL" allowances, following these for your own design without consulting your foundry can lead to a incorrectly cast part. Consult them first before 3d printing the final part.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20119.png)

If we can expect a 2% shrinkage on our part, we want to multiply our scale by 1.02x

Confirm the scale operation.

As we are using a centroid scaling we can see when we review the Turbo flange sketch that its position has moved.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20120.png)

We can expect its position to "constrict" back into position after the casting has cooled.

Switch back to the default design and ensure the Scale Feature is supressed.

![Untitled](L10%20-%20Turbo%20Headers%20from%203d%20Scan%2075a8f2672673464cbaf53bca0fba3354/Untitled%20121.png)

Print your Manifold to be cast. 

Note: In 2019 when this project was undertaken I cast the Bolt holes in the casting. This caused issues with fitment and required post drilling.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled.jpeg)

Raw Manifold after shell material has been removed.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%201.jpeg)

Manifold fitted to the car in 2019, Car dyno'ed 280KW Atw. and has never been removed since.
It has participated in 4x drag racing events and 6 Time Attack days since.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%202.jpeg)
# L10 - F360 Turbo Headers from 3d Scan

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

First we want to go to the Data panel and upload our 3d Scan into Fusion 360 Cloud.

Import the pre-processed scan ‘3sgte exhaust manifold t2 - aligned 25p.stl’ into Fusion 360.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled.png)

Once Complete open it up.

Due to the size of this scan, it is advisable to have no other components open at the same time.

Even at 25% we can see that the scan is highly detailed.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%201.png)

If you are having problems with working with the scan at this detail, go to the Mesh menu and Reduce.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%202.png)

As we have discussed previously we need to scale our scan from CM to MM.

To do this go to Mesh → Modify → Scale.
Scale to 0.10 and ensure you pick the origin of your part file as your ‘Point’ (center of Scale)

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%203.png)

We now have our factory 3sgte manifold with a CT → T2 adaptor on it.

The car currently has a dump pipe and plumbing all fabricated to fit.

What our design outcome for this project is to design → 3d print → Cast a bolt in replacement for the current setup.

The first thing I am going to do is 'show' the XY Plane so I can check that the mesh is aligned.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%204.png)

Next we are going to create a Plane through 3 points to get the location of the Turbo flange face.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%205.png)

Click OK to create this plane.

Create a Sketch on the XY Plane and rotate the view to the Bottom so that we can see the head flange face.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%206.png)

As we have done before, using 3 point circles capture the positions of the bolt positions and port shapes.

One thing that will be surprising is the cylinder furtherest from the Turbo flange (cylinder 1 on the engine) is bigger than the other 3, by quite a lot.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%207.png)

As I have said previously, some engine manufacturers will often have different port shapes across the same engine that are not uniform. 

The 3rd gen 3sgte is one of those cases. (a VW VR5 is even more shocking)

Tweak and adjust the geometry to match the port.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%208.png)

Finish sketch and name it.

Rotate around so that we can see the Turbo mounting flange.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%209.png)

Insert DXF → Select the Turbo Flange plane we created → select T2 Flange.DXF

As with previously the DXF will come in out of position, we will reposition in our sketch using the move tool. This will allow us to rotate the DXF if required to position it nicer on our model.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2010.png)

Click OK to accept this location.

Right Click the T2 Flange Sketch and edit it.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2011.png)

Select the DXF geometry and press ‘M’

This manifold is impressively square for a casting bolted to a casting.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2012.png)

Click OK once the T2 flange is positioned over our stud positions.

---

**You will immediately notice that the adaptor stud positions match the T2, but not the outlet hole.**

**This adaptor was causing the customer a lot of issues blowing Turbo gaskets.
We can see here that the exhaust gas would be hitting the gasket face, over time this will errode the gasket prematurely and cause it to blow.**

**It is reasons like this that you need to check "off the shelf" parts from aftermarket manufacturers.**

---

We are going to create a center point of our Flange location, this is for our Splines to Match up to for our Rail Guide.

Draw a Cross with 2 line

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2013.png)

Convert these to construction lines and create a point where they intersect.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2014.png)

Finish the Sketch 

The next thing we are going to do is create a 3d sketch to draw our Rail paths.

Create a sketch on the XY plane.

Tick on 3d Sketch.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2015.png)

Create 4 lines going from the center point of each circle used to create our Slot Geometry.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2016.png)

Convert this Geometry to construction lines.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2017.png)

Create a Point at the mid point of each line.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2018.png)

Create Lines Perpendicular to the XY plane.

The line length is not critical as this is to drive the tangency of our Spline.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2019.png)

Dimension them 30mm long just to look tidy.

To make a perpindicular line from our inclined plane on the T2 flange face we need to be a bit resourceful.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2020.png)

We need to project over the 2 Construction lines we created in our T2 Flange sketch.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2021.png)

Now we need to create a line starting at the X point of these 2 lines and click anywhere away from any geometry.

This is to ensure no relationship is created as we need to add these manually.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2022.png)

Now we want to add a Equal relation ship to this line and our 30mm long lines coming from our Head flange face.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2023.png)

Then we want to add Perpendicular relation ships between our blue line and one of our X lines.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2024.png)

It may look unusual but we haven’t finished yet.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2025.png)

Repeat for process of add a perpendicular relationship to our blue line and the other X line.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2026.png)

We have now succeeded at getting our tangency lines that we need to drive our Splines.

Next Draw a 2 point spline starting at the Center of one of the Head ports and finishing at the T2 Port Center.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2027.png)

It will look like a plane 3d straight line.

Next Add a Tangent relationships between our new spline and the port tangency line.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2028.png)

Then add a Tangent relationship between our spline and the T2 Tangency line.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2029.png)

Turning our 3d scan on, we can see that our new Spline moves smoothly through the 3d Scan body.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2030.png)

Turn the Scan off, and create 3 more Splines, all tangent to our Port and T2 Lines.

Splines.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2031.png)

Splines with Tangent Relationships.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2032.png)

Finish the Sketch.

Now we are going to start stacking sketches.

We will do this as we do not want to accidently modify any of our base geometry.
We also want separated geometry so that no unusual interactions occur.

Create a Sketch on the XY plane. Project the Port shapes onto our Sketch.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2033.png)

Close the Sketch and name “Port Inner”

Repeat the process then create an offset sketch 3mm from the port inner.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2034.png)

Repeat this process for the other 3 ports

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2035.png)

To reduce issues later, convert the projected lines into construction lines.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2036.png)

Finish and name this sketch Port Outer.

Now would be a prime time to save.

Next unhide our T2 flange sketch.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2037.png)

Create a new Sketch on our T2 plane we created.

Project the Turbo port hole to our new sketch.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2038.png)

Close this sketch and name it “T2 Inner”

Create a new Sketch on the T2 Plane → Project the T2 Port into our new sketch, then create an offset sketch 3mm from it.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2039.png)

Convert the T2 Projection to construction → Finish Sketch and name T2 Outer.

Turn off all your sketches and 3d scan except Rails, T2 Outer and Port Outer.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2040.png)

Create a Loft, Select the T2 Outer and the first Port Outer.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2041.png)

Move your control points (the red line with 2 white dots at each end) around until they match up to a point that is easy to replicate. We need to ensure all ports, inner and outer align to the same place to insure uniform (smooth flow) lofting.

Next Change the guide type to center line and select the rail that goes from the port you have selected to the T2 flange.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2042.png)

When your results looks smooth click OK

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2043.png)

Go through and Show the sketches we were using.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2044.png)

Repeat.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2045.png)

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2046.png)

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2047.png)

The blue surfaces below can cause us issues later on in our process.
So selecting them we can hit the  ‘delete’ key. Fusion will reinterpolate the surface and generate a (sometimes) clean results.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2048.png)

This is a surprisingly simple but unbelievably powerful tool.

Before we cut away our our runner inners we are going to extrude our flanges.
Because we have the transition going all the way up to the flange face we will be creating these flanges without any Port holes in them.

First turn on the T2 Sketch, select the T2 region.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2049.png)

Then extrude 12mm

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2050.png)

Click OK

Save

We never created the Head Flange sketch.
Because of the method we are using to model, it does not matter at which stage we do this.
Create a Sketch on the XY plane and unhide our 3d scan.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2051.png)

Never underestimate how powerful fillets are and how fast you can draw lines of best fit.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2052.png)

Extrude our flange 12mm towards the manifold doing a join operation

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2053.png)

Modify → Fillet → Select all of our hard edges.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2054.png)

Apply a 12mm fillet to our hard edgeds.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2055.png)

Our manifold is starting to look pretty complete.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2056.png)

Next we are going to cut our Bolt holes and apply fillets to all of our joins before we Loft Cut our ports. This is to ensure the software is able to complete the operation without crashing. 

Extrude cut our Bolt holes.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2057.png)

Apply fillets to where the runners meet the T2 Flange.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2058.png)

I went with 5mm

Next Apply a Fillet from the First runner to the Head Flange.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2059.png)

Repeat the process for the other 3 Runners.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2060.png)

We are now going to apply fillets to the surface intersections of our runners.
This is to allow material to flow smoothly during the casting process, and to reduce the likely hood of cracking through our manifold through these points.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2061.png)

Apply a 5mm fillet to these.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2062.png)

Click OK to complete the operation.

Now the finale, time to Loft Cut our Runners.

Turn on our Rail, Port Inner and T2 Inner Sketches.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2063.png)

Now do a Loft operation from our T2 Inner to our first runner inner.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2064.png)

Select Guide Type Center and pick the spline that connects our T2 and Port.

Ensure the operation is set to Cut

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2065.png)

Click OK

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2066.png)

Repeat for the Next 2 runners.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2067.png)

On the 4th runner you will see that you have a failed operation.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2068.png)

This is because of these cheeky surfaces below.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2069.png)

To avoid the mathematics behind this, what is occurring is a surface is finishing too close to an existing one. This is causing the software to throw its toys as a result is mathematically impossible to produces so instead outputs a ‘failure’ with no visualisation (we are lucky that inflections/twisted surfaces do show a result allowing us to problem solve them).

To fix this, select those surfaces, and like before, click ‘delete’.
Fusion will do all the hard work and create a net result.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2070.png)

This will occur regularly when you have multiple lofts intersecting to the same location. 
There are many work arounds, and if you did the Solidwork’s Tutorial on the same part, we actually give each runner slightly different finishing geometry so they do not intersect.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2071.png)

Selecting the last runner we can see we have a completed result.

Click OK

You now have a finished 3sgte to T2 manifold.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2072.png)

Turning on the 3d Scan we can see that the new manifold occupies the same 3d volume as the existing one reducing our risk of interference.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%2073.png)

Print your Manifold to be cast. 

Note: In 2019 when this project was undertaken I cast the Bolt holes in the casting. This caused issues with fitment and required post drilling.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled.jpeg)

Raw Manifold after shell material has been removed.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%201.jpeg)

Manifold fitted to the car in 2019, Car dyno'ed 280KW Atw. and has never been removed since.
It has participated in 4x drag racing events and 6 Time Attack days since.

![Untitled](L10%20-%20F360%20Turbo%20Headers%20from%203d%20Scan%20f7d5faec26f246bd982dacc470cd375d/Untitled%202.jpeg)
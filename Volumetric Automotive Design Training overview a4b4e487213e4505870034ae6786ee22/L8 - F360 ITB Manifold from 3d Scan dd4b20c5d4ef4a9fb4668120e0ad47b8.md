# L8 - F360 ITB Manifold from 3d Scan

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

As we have done before, we are going to upload and align the 3d scan we have taken of a Mazda BP Cylinder head. This is the intake flange face only. 

This scan is heavy at 116meg, and the first thing we should do is reduce the detail so that our computer can handle the scan without crashing.

Mesh → Reduce → select our scan, apply 75% reduction and press OK

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled.png)

Remember not to disturb Fusion while the green bar in the bottom right corner is processing.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%201.png)

The scan remains with still an incredible amount of detail that we can use.

Next Scale the scan 0.10x to account for the importation of the scan to be in Centimeters.

Always be sure to select the Origin as the scale ‘Point’

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%202.png)

Click OK and Save

Copy your file in the Data window.

Now we are going to draw our intake flange face.

Create a Sketch on the XZ Plane and start to draw the intake flange features.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%203.png)

Drawing a horizontal line and a line across the tops of the intake ports I can see that the scan is out 0.6 degrees

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%204.png)

Now this might not appear much as a number, across the length of the flange this is a considerable distance of error which builds up to ~3mm

Select Move → pick the mesh body → Move the ‘Set Point’ to the component origin and rotate 0.6 degrees

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%205.png)

Wee can now see that our horizontal line is inline with the tops of our intake ports.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%206.png)

Hide our sketch.

Create a new Sketch on the XZ Plane and start to create our geometry. 

Using 3 point circles and the slot sketch tool locate the hole positions and the port internal shapes.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%207.png)

Create a new sketch on the XZ plane and project these details to it.

Hiding our 3d scan we should see the geometry below.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%208.png)

Using the offset start to create the outside profile of our flange face.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%209.png)

Offset 9mm from the inner port shape.

One thing we have to be considerate of while designing “Is what we are doing going to interfere or obstruct anything”

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2010.png)

On closer inspection we can see that we are covering up the injector hole with the flange edge.

We can either fix this now with our profile, or what we will do later is extrude cut the injector scallop out of our intake manifold.

For now we will leave this as is.

I will often turn my 3d scan on and off to check if I have missed anything.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2011.png)

As we can see, I projected the centre point of one of the stud positions, but not the edge of the stud itself.

Going back, unhiding the captured geometry sketch then projecting it into my current sketch now allows me to offset this profile.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2012.png)

Another method is to use the offset tool and select the entity in the previous sketch. Fusion will automatically project it into the current sketch entity.

Go through and draw in the outline of the flange we want to produce.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2013.png)

Again, the ability for us to use the regions within fusion mean we do not need to trim and change all this geometry to extrude the desired result.

When extruding, fill in the intake ports. 

We are going to loft cut the transition from our ITB shape to our head shape to give a nice flowing surface for the air to pass through. For this to work we need to have material to “cut away”

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2014.png)

As you may have noticed we have extruded the stud holes at the exact size of the stud.

One feature of fusion that I love, and something that should be utilised more as you become familiar with it is the ability to directly edit the model.

Instead of having to go back and forward to sketchs that drive feature/processes we can instead just modify the feature we see to get the desired outcome.

The reason this is powerful, is some features high up the design tree in parametric models will often have a lot of things referring to that. 

Modifying that can cause the entire model to fail and ‘crash’ which is massively undesirable.

Select Modify → Offset Face

 

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2015.png)

Now select the stud holes.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2016.png)

Fusion has identified that these holes are ~4mm radially (8mm in diameter)

Change this value to 4.5mm to give us 9mm holes.
You can make this 4.25 if you would like a tighter fit on your flange, but be aware if you intend to cast the holes in this flange face, this dimension maybe too tight.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2017.png)

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2018.png)

Now we are going to create an offset plate 60mm from our XZ plane.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2019.png)

Construct → Offset plane → select XZ plane, then set the distance to 60mm

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2020.png)

Select the newly created plane and insert the DXF “ITB Manifold blacktop - rev l.DXF”

The DXF has come in upside down, so we will just position and then open the sketch and edit is position after.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2021.png)

Select OK

Go into the Browser → Sketches folder and edit the newly created sketch from our DXF

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2022.png)

Using the Move tool to rotate the flange around 180 Degrees in the X and the Y axis so that it is orientated the correct way.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2023.png)

When setting the locations of the ITB positions we need to consider 2x things.

- Will we use the factory linkages?
- do we want the throttle cable at the top or bottom of our manifold

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2024.png)

I always like to use as much factory features as possible, this reduces the need to 'reinvent the wheel'

For this reason I am going to space my ITBs at the factory distances.

Using the move tool with the sketch open, create copies of the flange face 89.5mm spacing.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2025.png)

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2026.png)

I have hidden the scan and solids to make this process easier to see.

Turning on the Intake port sketch we can see their positions relative to our ITB Spacing.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2027.png)

Adjust the ITB spacing so that the average of the intake ports.

The Mazda Ports are 90.80mm apart, and the Blacktop ITBs are 89.50

So we should adjust their position so that the First and Last ITB are 2.6mm off centre from the 2 end ports

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2028.png)

I projected this information to a new sketch.

Extrude our profiles 12mm toward the head.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2029.png)

Create a sketch on the head face.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2030.png)

In it offset 2.5mm outwards our original port holes into this sketch.

This will be the wall of our runners.

You will need to project this geometry into our current sketch.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2031.png)

Repeat the process for the other 3 ports

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2032.png)

**“Why do you create new sketches? Why not edit the original geometry?”**

Preserving information is critical, especially something as rudimentary as our base geometry.
If we were to go back to this original sketch, and accidently trim, or move an entity without noticing it. We could end up doing a lot of work to our part that is now useless.

I have done it many times before, and although projects can become cluttered. Once you progress and basic house keeping skills such as naming sketches and folderising them becomes second nature it will become a hassle free process to do.

Now we are going to repeat the process for the ITB Ports.

Create a Sketch on the ITB Flange face, then project the geometry from the ports to it 

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2033.png)

Then offset 2.5mm

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2034.png)

All of our geometry is now established to create our runners.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2035.png)

We are going to use the loft tool to morph our ITB offset Port shape to our BP offset Port shape.

This is a very powerful tool that we will use more and more as we progress through these tutorials.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2036.png)

Select the Loft Command.

We want to make a Solid runner that connects the 2 flanges, then do a seperate process to subtract the inner port shape from the body.

This is because we want to transition immediately from the the back of the ITB all the way up to the cylinder head for the smoothest possible airflow path.

After starting the loft command, select the 2 regions that make up the ITB runner (the outer wall and the inner cavity)

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2037.png)

Next Select the Outer and inner regions for the Cylinder head.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2038.png)

Fusion will see that there is material “in the way” and default the operation to ‘Cut’

We want this to be ‘Join’

This is so we create a solid body of material from the ITB flange to the BP Flange.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2039.png)

Before we complete the operation we need to take note of the 4 control points.

As lofting is an “organic surfacing process” there is no dimension we can attribute to this data.

Instead we need to visually move and adjust these points to get the desired output.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2040.png)

What we want are for the 2 control points to end on each end of the straight line of the slot of the BP flange. The ITB side is good and does not need to be adjusted.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2041.png)

Be mindful that when adjusting these control points you can get an inflection (twisted surface) the results can be startling.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2042.png)

If you do not know how you reached this result, it is best to close the operation. Start again and do minor adjustments until it occurs. Then adjust back until you get the desired result.

For this instance, I crossed the “Start/End” point of the sketch. This is information we cannot see but it is stored inside the CAD software (imagine a giant spread sheet of X,Y,Z positions to describe the Geometry we see) and we have taken the control point far enough that the software things we have gone around again. Thus twisting the surface.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2043.png)

Fixed

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2044.png)

Click OK

Unhide your sketches in the Browser, and repeat the process 3 more times.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2045.png)

//Repeat the process for the next 3 runners.

I went to repeat this process for the next runner and hit a hurdle where Fusion 360 did not create the control point and created an inflected result immediately.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2046.png)

First step to east the issue was to go into the 2 sketches containing my Loft profiles and converting the inner sketch region to construction lines.

Select these lines and select the ‘Construction’ button in the Sketch Palette.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2047.png)

Repeat for the Head Side profiles.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2048.png)

Create a Sketch on the XY plane.

Tick the ‘3d Sketch’ check bock in the Sketch Pallet.

Now draw 2 straight lines from each end of the straight section of the portside profile, and connect these to the creases in our ITB side profile.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2049.png)

Finish sketch.

Now we are going to execute a loft command and repeat what we already know selecting each of the 2 profiles.

Select Loft, pick our ITB Profile.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2050.png)

Rotate around and select our Head Flange profile.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2051.png)

Select the Rails Arrow

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2052.png)

And pick our 2 lines.

Fusion will default to ‘Cut’

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2053.png)

Change this to ‘Join’

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2054.png)

Select OK and complete the operation.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2055.png)

Repeat the process for the other 2 flanges.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2056.png)

Now we are going to do the same process but for the runner surface.

For ease of control and to reduce issues I am going to create 2 new sketches to represent the interior runner profiles. 
**Note: Through the process of designing this manifold for this lesson I have identified 1 major bug and 1 minor bug in Fusion 360 which has been brought to Autodesk’s attention.** 

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2057.png)

Create a sketch on the ITB Flange face, then project the inner port shape.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2058.png)

Next we are going to create a 3d sketch and create rails that join these profiles like we did before.

We now have the below geometric data that represent our runner shape.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2059.png)

As with before we are going to select the ITB inner profile, then the Head runner profile, turn on rails and select the 2 lines that connect these profiles.

This time we are leaving the loft function on ‘Cut’ as we want to remove this volume from our 3d model. (please remember to turn the body back on in the Browser or Fusion will try and create a new body using this geometry instead)

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2060.png)

Click OK

We now have a smooth uniform transition from one profile to another.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2061.png)

Turn view back on for the 3 sketches we used to create our loft cut and repeat the process for the other 3 runners.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2062.png)

We now have a very complete looking manifold.

However there are a lot of details that we still need to complete.

Turn on the ITB Sketch that we create the ITB Flanges from.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2063.png)

Here we have the positions for the holes that we are going to use.

We are going to use the Hole function to input the hole information for our M6 mounting holes.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2064.png)

Select the hole tool and the Dialogue box will appear on the right hand side.

Select the ‘From sketch Multiple’ button.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2065.png)

The tool will start with the default settings for this tool.

If you have used it in a previous project, it will use the previous settings you had entered.
In my case these were 10mm holes, 15mm deep.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2066.png)

Go through at set:
Hole Type, Simple
Hole Tap Type, Tapped
Thread Offset, Full
Drill point, Flat

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2067.png)

Scroll down and select ISO Metric, 6mm size, and M6x1. 

Make sure it defaults to 6H (thread precision) and Right hand (direction of thread being Clockwise).

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2068.png)

Click OK

We now see we have the M6 tapped holes in our flange face.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2069.png)

Next we are going to create the cutouts for the injectors so they do not interfere with our manifold.

Select 3 Point construction Plane, and zoom in to view the first injector port.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2070.png)

Select a point on the ledge for the injector seal. 

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2071.png)

Move to the next hole and repeat 2 more times. 

We have now create a plane that is the average of these 3 points across those injector faces.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2072.png)

Select create sketch and pick our inclined plane.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2073.png)

Click look at and pick our plane we have created in the Browser window, under the construction folder.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2074.png)

Now create 3 point circles on the injector locations. Do not worry if they are oversize as we are using this geometry to create clearance on our injectors.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2075.png)

We are going to hide our Manifold body and show just the sketch we have created and the 3d scan.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2076.png)

Extrude these 4 profiles -40mm.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2077.png)

Next we are going to increase the Taper angle until we just start to intersect the 3d scan with our new bodies.

This looks to be between 19-20 degrees of taper

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2078.png)

Go back to the Browser and turn on our ITB Manifold, Fusion will change the operation automatically from ‘New Body’ to ‘Cut’

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2079.png)

Click OK to apply our injector clearance cuts.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2080.png)

Things are starting to look pretty good.

---

**This tutorial is incomplete.
We are working on a solution that is straight forward, functional and repeatable.
At present there are no work arounds to adding fillets between the runners and the flange faces in Fusion 360.**

---

Below is when I identified there was an issue with filleting.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2081.png)

When we try and apply fillets between the ITB Flange and the Outside runner surface we have a failed result.

It is because of this tiny surface here that was created during lofting.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2082.png)

Zooming right in we can see it.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2083.png)

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2084.png)

Solidworks (Which is the package I have the predominant amount of this type of work in) does not create that small surface entity, as seen in this ‘extreme’ 3d printed manifold example using the same geometry for the ITB Flanges.

![Untitled](L8%20-%20F360%20ITB%20Manifold%20from%203d%20Scan%20dd4b20c5d4ef4a9fb4668120e0ad47b8/Untitled%2085.png)

It is originating from the Sketch Offset Function.

I am working on a solution, but do not want to hold up the delivery of this entire course to do so.

Because of the way this course is delivered, we are able to update the content with revisions and they will become instantly live.

For this reason, having bought the course, you will be notified immediately when this lesson has been updated.
# L5 - F360 Drawing an Oil Relocator

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

In this tutorial we are going to product a Oil relocator for a 1uz to replace the factory unit.

The factory units on these engines are long snouts with a large fitler housing on the end.
This can be a real issue when retrofitting these motors into other vehicles with front style sway bars that you will find in most 1980/1990s Japanese cars such as Skylines, Cressida's and the little AE86.

The outcome of this part will be to machine it from 6061 Aluminium using a CNC mill.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled.png)

For the purpose of this lesson we have provided the block template for the engine side of the relocator. 

We used the method outlined in lesson 1 to capture this geometry and bring this into Fusion 360.

To accelerate this process I have provided the DXF as part of this course material.

Insert → DXF → Top Plane → L5 - “Oil Relocator-Lesson.DXF”

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%201.png)

We can see that the DXF has imported to the TOP plane.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%202.png)

Right click on our DXF Sketch in the Browser and edit it.

Check that the DXF has imported correctly by checking against the below dimensions.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%203.png)

Note that the orientation of the sketch we are looking at is at the bottom of the relocator.

This means when we extrude our shape, this will need to go downwards.

Finish sketch.

Push pull the outer profile of our shape 15mm.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%204.png)

Remember to extrude in the downwards direction.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%205.png)

Click OK to complete.

Our Sketch that we are referencing will become hidden.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%206.png)

Go to the BROWSER and select the ‘eye’ to turn it back on.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%207.png)

We are now going to rotate our view so we can see the bottom of our part and select the bottom face.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%208.png)

Under Construct we are going to use the Offset Plane tool.

As we progress through these tutorials, we will be using planes more and more for the construction of our parts.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%209.png)

Offset our plane 30.0mm from the bottom face of our Relocator.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2010.png)

Select our newly created plane and create a sketch on it and rotate our view end on to it.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2011.png)

Using the Project tool we are going to capture geometry from our reference DXF and draw from it

Select Create → Project/Include → Project

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2012.png)

Select the 2 largest circles representing the outer of our O-ring groove

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2013.png)

Click OK

Turn these into construction lines by selecting them and toggling the construction icon in the sketch dialog box.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2014.png)

These will now become dotted geometry.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2015.png)

Now draw a Construction line between the 2 circle centres

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2016.png)

We are going to use the line to drive the centre of the circles for our fitting holes.

Measuring the M16 → AN-6 fitting that I will be using I need to use a 28mm spanner to fit.

For this reason I want to give clearance of 2mm on Diameter (1mm radially) so that that the fittings clear each other as they rotate around during fitting.

to work this out, draw 2 circles with the centre point on our construction line

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2017.png)

Make these Equal in diameter and Tangent to each other and dimension at 29.0mm

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2018.png)

Move your circles out of the way by dragging on of the centre points down to the right. 

The circles should move smoothly along the construction line axis.

If they do not, create a coincident relationship between the circle centres and the line.

Next draw a Centre line at 90 Degrees to our construction line, starting at the midpoint.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2019.png)

Now select, the 2 circles and the centre line we have just created and create a symmetry relationship.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2020.png)

The circles should toggle over into place and be central about our part.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2021.png)

Add 2 lines tangent lines from each of our circles to create a profiled region.

This will be our fitting face.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2022.png)

Finish Sketch

We are getting ready to Loft from our sketch to our base.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2023.png)

The loft tool works by morphing out 2 shapes together.

This is a semi-organic process and is prone to create unusual results.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2024.png)

For this to work, we need singular enclosed regions.

We will be using the geometry we just created to reference for future features, as such we are going to leave this as is. 

To get our singular enclosed region, we are going to create another sketch on our offset plane → project to new sketch → trim 

Select our plane from under the construction folder.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2025.png)

Create Sketch

Create → Project → Select Sketch 2
Turn off projection Link

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2026.png)

Click OK

Trim

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2027.png)

If we are to include Projection Link, we are unable to trim the geometry.

But by toggling this off we can trim, but now we can also edit the geometry we have projected.

This can cause accidental and unusual results.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2028.png)

To avoid this we are going to select the geometry and select the fix constraint.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2029.png)

Select Finish Sketch.

This geometry will be disassociated with the base sketch we are using, this means that if we edit this, the model will not update.

However Fusion is a very powerful direct modeller, and the more you use its direct modelling functionality the less this will matter as you progress through learning about it.

Click Create → Loft and select the region we have just created.
For ease of use, I have hidden our construction sketch.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2030.png)

Next select the closes face of our Base.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2031.png)

Fusion will show us a preview of the results we are going to produce.

Rotating the model around we can see 2 control markers

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2032.png)

We can move these from side to side to change our outcome.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2033.png)

Modify these until you have a model that looks the gentlest in flow.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2034.png)

We are going to use this tool a lot in future lessons, so if you need, go over this tutorial again, turn features on and off and play with the control points.

We will use the Guide type, Rails and Operations in future lessons.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2035.png)

Click OK when you are happy with the results

Next we are going to add the Boss on the clean return line of our relocator. 
On a factory vehicle this is used for the oil pressure sensor, but in the application shown above it is the high pressure feed for the turbo.

As our relocator is non-symmetrical it is IMPORTANT to note which side is the clean return, we can see this from our oil pump setup. (blue arrows mark direction of oil flow to external filter housing)

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2036.png)

For our turbo oil feed we want to this to be filtered oil so we will put this fitting on the return line.

I have high lighted the face we will be drawing on and the circles that the line is running on.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2037.png)

With this face selected, create a sketch. This will place the sketch entity on this face.

Any modelling we do will start at this plane.

We need a centreline to put our feed fitting on, to find this point we are going to select the centre point of our Oil pump return line, and project this onto our sketch.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2038.png)

Create → Project → OK

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2039.png)

We can now use this point as the start of our Centre line.

Orientate the view to the left so that we are looking straight on to our sketch.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2040.png)

Draw a vertical line downward from our projected point, to the end of our model.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2041.png)

Create an 18mm circle tangent to the face edge

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2042.png)

Finish our sketch and Push/Pull up to our relocator body.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2043.png)

Switch the operation from Cut to Join

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2044.png)

Select OK

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2045.png)

We now have our upstand for our boss.

Now it is time to start doing the details and holes on our component.

Select the O-Ring Region and Push/Pull cut this 1.50mm deep into our Base.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2046.png)

We can see that we now have the groove for our O-Ring

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2047.png)

Next Subtract the 2 oil feed holes 15.00mm deep into our component base.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2048.png)

Our 2 Screw clearance holes Push/Pull through the entire component.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2049.png)

Now we are going to use the Hole tool to add our threaded holes for our fittings.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2050.png)

Select this to access the Hole Dialog box.

Then select the 2 centre points of our Offset Plane construction geometry.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2051.png)

Ensure the Multiple holes icon is selected.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2052.png)

Set the Depth to 45mm (through the entire part) with the hole type being threaded.

The -AN adaptor fittings we are using have a M16x1.5mm

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2053.png)

Do not make this Modeled, we are going to drill and tap using a CNC Mill.

Click OK

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2054.png)

Repeat the hole process and select the centre point of the Oil feed boss we created earlier.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2055.png)

The settings from the last hole operation are carried over. 

This is not a desirable outcome.

Rotate the view around so that we can see the hole passing through our Oil Return hole.
Change the hole depth so that our hole feature finishes in the centre of our M16 hole.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2056.png)

This feeder line will be using a M12x1.25mm to MALE BSP adaptor 

Go down the the thread features and change from M16x1.5 to M12x1.25

Our preview will update with the new geometry.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2057.png)

We are starting to look good.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2058.png)

We now need to produce clearance for our 2x M8 cap screw heads that we will using to fix our Relocator to the Oil pump.

Rotate to view the base of our Relocator and create a sketch on this face.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2059.png)

Click the Top on our view cube.

Create 2x 15.00mm diameter circles concentric to our 8.75mm screw holes.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2060.png)

Finish Sketch

This time we are going to use the Extrude tool.

We are going to do an offset extrude. 
This is a feature that starts and finishes away from our sketch plane.

First select our 2 profiles we have just created.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2061.png)

Under Start, we are going to change this to “Offset” and define a distance of -15mm

We can tell the offset amount being a positive or negative value based on the arrow direction shown on the model.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2062.png)

Next we are going to set a distance of -30.00mm (the distance of our offset plane)

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2063.png)

The operation will automatically change to “Cut” from “Join” as the software sees we are trying to create a feature inside an existing component body.

Click OK

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2064.png)

Now we will see our 2 Cap screw clearance pockets.

At this point I would export my model as an STL to 3d print and check fitment on our engine.

Once happy with the design, export the file as a solid model (STEP, X_T or IGES) and send to a Machine shop for quoting.

Do not chamfer the 2 counter bore holes or the oil seal groove.

You will either need to express to the machine shop through description or an engineering drawing produced from the model that these edges are to be deburred but not chamfered.

For the counterbore holes, this is to reduce machining cost.
For the oil seal groove this is to ensure that it functions correctly and does not leak oil.

Save and done.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled.jpeg)
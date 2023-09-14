# L5 - Drawing an Oil Relocator

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

We used the method outlined in lesson 1 to capture this geometry and bring this into Soldiworks.

Create a new part → sketch top plane → insert block "1uz Oil Flange Geometry"

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled.png)

Align the origin to one of the screw holes and give the block a horizontal relationship with one of the straight lines.

One thing to be cautious of and is worth doing is creating a marker to show which way is the front of the block.

We are fortunate that the mirror image of this block just means that's you need to rotate the finished part. 
However a shape that is non-symmetrical that is unable to be reveresed such as an ITB flange means we can design and produce a part that cannot be used.

Exit the sketch.

Create another sketch on the top plane → select the outer profile edges → convert entities

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%201.png)

Extrude this sketch into a solid 15mm. 
This will be the material that our bolts will use to hold the adaptor to the engine.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%202.png)

Now we are going to use the Loft tool for this component.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%203.png)

First we need to do some ground work so that we can build the geometry required for the loft to work.

First create a reference plane 30mm parrallel to the top face of our part.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%204.png)

Confirm by clicking the green Tick.

Select the top plane and create a sketch on it, to rotate Solidworks to look at the top plain to be normal to, click the arrow next to the cube in the viewport on the top of our graphical window to gain access to the view menu. From here select normal to.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%205.png)

In our top sketch we are going to construct some geometry to work out the side of shape we need to accommodate the 2x M16 → AN adaptors we are going to use.

To start with, create a construction line on the screen away from any geometry.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%206.png)

We do this as we are going to manually add relationships to it to help with visualising our outcome.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%207.png)

Add a Coincident relationship between each end point and each radii of the profile.

Your construction line should look like this.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%208.png)

Next Add a coincident relationship between the construction line and the circle centres of our port holes.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%209.png)

We should get the below result

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2010.png)

We are going to use the line to drive the center of the circles for our fitting holes.

Measuring the M16 → AN-6 fitting that I will be using I need to use a 28mm spanner to fit.

For this reason I want to give clearance of 2mm on Diameter (1mm radially) so that that the fittings clear each other as they rotate around during fitting.

to work this out, draw 2 circles with the center point on our construction line

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2011.png)

Make them Equal in diameter → tangent relationship to each other and dimension one at 30mm

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2012.png)

There are quite a few ways to work out where these need to be located. 

We can measure the center distances of the factory oil hole positions, then measure the distance from the 2 AN adaptor positions.

Then calculate the distance that the center of the 30mm holes need to be from the factory positions.

Or;

We can use relationships to visually work out where these positions are.

Create 2 circles at the center of each 30mm hole

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2013.png)

Make these equal in relationship to each other

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2014.png)

Make one of the new circles tangent relationship to the factory oil hole

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2015.png)

Do that for the other

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2016.png)

We now know where our adaptors need to be relative to the factor geometry so that they match up in location evenly.

We are going to exit this sketch and use it to reference our profile shape for our loft and for creating our hole positions for our M16 → AN adaptors.

Select our reference plane and create another sketch on it.
Convert entity our 2x 30mm circles into this.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2017.png)

Draw 2 tangent lines and power trim out the middle to be left with our desired outer profile.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2018.png)

Close this sketch.

Create a new sketch on the top face of our part , and convert entities the outer profile of this.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2019.png)

Close this sketch.

Click on the Loft Boss/Base button in the features window and select our 2 newly created sketchs

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2020.png)

You will likely get the result above.

Now this is undesired for this application as it is a twisted geometry that may intersect our oil holes.

Also it will be a pain to CNC machine (if this was a 3d printed part this would be less of an issue)

To fix this, we click and drag the green markers in the graphic window to a position we desire.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2021.png)

I clicked and dragged the lower one and snapped it to the other end of the arc it was attached to.

Confirm and you will be left with the below solid model

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2022.png)

We will be going into far greater depth with the loft and sweep tools in future lessons.

But essentially we are morphing one shape into another. 
We can add further geometry such as center lines and edge curves to create more complex shapes.
This is very handy for intake manifolds morphing from one flange type to another.

Next we are going to add the Boss on the clean return line of our relocator. 
On a factory vehicle this is used for the oil pressure sensor, but in the application shown above it is the high pressure feed for the turbo.

As our relocator is non-symmetrical it is IMPORTANT to note which side is the clean return, we can see this from our oil pump setup. (blue arrows mark direction of oil flow to external filter housing)

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled%2036.png)

For our turbo oil feed we want to this to be filtered oil so we will put this fitting on the return line.

I have high lighted the face we will be drawing on and the circles that the line is running on.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2023.png)

 Create a sketch on high lighted face and draw a center line on it, then add a concentric relationship between the line end and the center of the circle

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2024.png)

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2025.png)

Create a circle with the center on the center line we just created.

Dimension this at 18mm and tangent it to the top of our surface edge

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2026.png)

Extrude Bass/Boss this toward our adaptor, then under 'Direction' select 'Up to Next'

This will reduce the risk we create unwanted geometry extending through the adaptor and out the other side.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2027.png)

Now it is time to cut our holes and do some finishing.

I like to do all the subtractive geometry at the end of modelling where possible, this reduces the risk that material is created inside a cavity or hole that you don't want to be there.

The first thing we are going to do is create all the bottom detail for our oil seal groove, 2 screw holes and oil lines.

Start by creating a new Sketch on the bottom face → select the oil grooves → convert entities

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2028.png)

Extrude cut that into the part 1.50mm for the Oil Groove

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2029.png)

Repeat the same process for the clearance holes on the screws and extrude cut them through the part.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2030.png)

Using the all command allows you ensure that the holes you model change and update if any other part of the model is changed. 

Next are are going to do the 2 oil feed holes.

Make these 15mm deep.
This is a comfortable depth for milling these holes when it comes time to manufacturing our part.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2031.png)

Starting to look pretty good.

Next we are going to create the pockets for our M8 Capscrews that we will be using to fix this adaptor to our engine block.

We could do this by creating a sketch on the top face and extrude cutting them down.

However we are going to explore another tool that is very helpful.

Create a sketch on the bottom face → Draw 2 circles 15mm in diameter with their centers on the 2x M8 clearance holes.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2032.png)

Execute the extrude cut tool

This time we are going to use the 'From' Feature

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2033.png)

Pick 'Offset' from the drop down menu and set the distance to 15mm

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2034.png)

You may get the above result.

Simply click the 2 Arrows in the from box to change the offset direction from the sketch face.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2035.png)

Note: You can see that the icon is now depressed showing that it is active.

Under the 'Direction' box, change the option from 'Blind' to 'Through All'

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2036.png)

We now have our 2 counterbores for our cap screws.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2037.png)

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2038.png)

The next thing we need to do is put the 2x M16 Tapped holes in the top of our part.

As we wish to convey to the CNC Machine shop that these holes are tapped, we are going to use the hole wizard tool in Solidworks

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2039.png)

The following Dialogue box will appear

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2040.png)

From here we have a variety of options to describe the holes we want to produce.

The advantage to the hole wizard, is the dimensions are already worked out for you
From here by selecting a M16x1.5mm tapped hole, we don't need to know the pre drill size for this size.

Ensure the highlighted values match below;

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2041.png)

Next Select the 'Position' Tab at the top of the box for us to pick the locations for these holes.

When doing the next part, ensure that the sketch we created earlier for the top face reference geometry is visible.

If it isn't right click it and click 'Show'

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2042.png)

Click the top face of the model

It will turn blue and a ghost of the hole we wish to create will chase the mouse position

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2043.png)

Use the mouse cursor and select the centers of the 2x 30mm circles we drew earlier.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2044.png)

Once you have done this, click the green tick to 'Complete'

If you have accidently created geometry you don't want, hit the escape key, and select the points you created and delete them

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2045.png)

If you delete too much geometry or wish to add more but have escaped from the point tool, just go to the task bar at the top and select 'Point'

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2046.png)

Once completed we can see a pair of phantom edge circles. 

This is the CAD string the thread information that can be translated to the CAM package for CNC machining.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2047.png)

As you might have noticed in the 'Gear Knob' Lesson, modelling the actual thread is quite time consuming and requires a lot of base understanding of threads.
However the process only requires a pilot hole to be drilled in the part, then a standard industrial Tap run through it to create a thread form.

This saves a lot of time when designing, and computing horsepower to model.

Lets do the same for the M12x1.25mm hole that we are going to create on the side of our part.

Open Hole Wizard and set the size to M12x1.25mm

This time we are going to change the End condition to 'Blind'

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2048.png)

Set the dimensions above as a quick guide, we can come back and change these if we need to

Select the side boss face and set the point to be the center of the Boss we created earlier.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2049.png)

When we rotate our model around, we can see from the preview that our feature breaks into our Oil line cleanly 

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2050.png)

If for some reason it was not long enough, or too long and is going to break through the part we can simply go back to the 'Type' Menu and make changes to this geometry.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2051.png)

A big advantage to using the hole wizard tool is that most major CAM (Computer Aided Manufacturing software: Used for programming CNCs) carry the hole information over into the package.

So even if it is not visible, the machinist/programmer knows that the holes needs to be 12mm deep for our M12x1.25mm hole for it to break through cleanly into the M16 hole.

This is great as it is likely that this hole is created on our finished part before the M16 hole as it will be easier datum at this stage before the organic surface is created during machining. 

Add chamfers to the part, and save.

![Untitled](L5%20-%20Drawing%20an%20Oil%20Relocator%20814ee388bafb4699ac73460fa52caba5/Untitled%2052.png)

Do not chamfer the 2 counter bore holes or the oil seal groove.

You will either need to express to the machine shop through description or an engineering drawing produced from the model that these edges are to be deburred but not chamfered.

For the counterbore holes, this is to reduce machining cost.
For the oil seal groove this is to ensure that it functions correctly and does not leak oil.

Save and done.

![Untitled](L5%20-%20F360%20Drawing%20an%20Oil%20Relocator%20b4d1f363158b47a08d5ac07f882b5809/Untitled.jpeg)
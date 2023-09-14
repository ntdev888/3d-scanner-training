# L4 - Drawing an ITB Trumpet

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

This process is going to be a hybrid of 2 things we have done so far.

- Revolving a shape
- Drawing a flange

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled.png)

There is a lot of discussion on the optimal Trumpet shape, and this is an area that we can all talk about until we are blue in the face.

The purpose of this lesson is to teach you how to draw your own, and in no way is recommending this as the final desired shape.

From the downloaded resources, we are going to use the Flange Block for a 4age Silvertop (AE101) ITB inlet flange.

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled.png)

First create a sketch on the Right Plane.
Now go Tools → Blocks → Insert
Browse to the location of the Flange Block and select 'Open'

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%201.png)

Establish a relationship for the center of the block and the origin and set the construction line to be horiztonal

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%202.png)

We are going to park this geometry and reference from it for the next phase of drawing.

Create a sketch on the front plane and create a centerline passing from the origin.
Dimension this to the length you wish the trumpet to be;

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%203.png)

You maybe wondering why we are drawing it in this orientation. 
For ease of visualisation when designing, it is often best to orientate the part to help understand its application. 

With this particular trump being designed for a 4 cylinder engine, this helps me imagine it in place on the engine.

Next I create a line with the minimum distance between ports. This helps show what the maximum trumpet diameter can be before trimming. 

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%204.png)

We will also use this line to help drive our spline when it is time to create the trumpet geometry.

Next create a center line and pierce it to the edge of our port on the flange.
Add your desired taper angle to this, I will use 7 Degrees for this example. However you want it to match as closely as possible to port angle of your ITB.

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%205.png)

We are now going to use the spline tool and create a 2 point spline

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%206.png)

Create the spline

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%207.png)

Now, a spline is an organic curve tool, we can manipulate it freely, or we can define it through relationships. 
Next we are going to create a tangent relationship between the 7 Degree line and the spline.

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%208.png)

Then between the spline and the vertical line we created.

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%209.png)

This is where a bit of imagination and different schools of thought come into play.

But if we use common sense we can generate a design that looks uniform and laminer in design

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%2010.png)

We achieve this by moving the end points around until we get the desired outcome.

We can offset the design by the material thickness we wish to print.
Join the ends and revolve boss/base the design

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%2011.png)

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%2012.png)

As we discussed in the previous Lesson creating the Gear Knob, if we have multiple centerlines, we will need to select the one we wish Solidworks to use to revolve our shape.

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%2013.png)

Select Done.

Select the first sketch and extrude this 5mm

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%2014.png)

Add a 2mm fillet and we have a simple Trumpet Design that we can now 3d print in Nylon;

![Untitled](L4%20-%20Drawing%20an%20ITB%20Trumpet%201d30a5e9266c417198d8e9a4f0bd4051/Untitled%2015.png)

Save as an STL and print 2 samples in low Cost PLA to trial fit next to each other.

Don't worry thought, there will be a more advanced ITB Trumpet Design Lesson as we progress.

![Untitled](L4%20-%20F360%20Drawing%20an%20ITB%20Trumpet%2005ba85fc5774484493b5768d0578bfac/Untitled.jpeg)

Advanced 3d Printed trumpet designed by Volumetric for ITB V6 NSX Motor
(Special thanks to Cody for letting us share photos from his project)
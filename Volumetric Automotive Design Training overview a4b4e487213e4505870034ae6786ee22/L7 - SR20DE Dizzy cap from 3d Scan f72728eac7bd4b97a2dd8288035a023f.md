# L7 - SR20DE Dizzy cap from 3d Scan

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

We are going to create a 3d printable CAS Cap for the SR20DE Distributor.

It is common to go to a CAS system with coil on plug or wasted spark on performance engines.
Using an SR20DE distributor and producing your own cap is a cost effective way to do this.

This is also possible on the 4age and 2jzge engines.

Create a new Part → xtract3d → import 'SR20DE Dizzy - Aligned.stl'

Ensure that "center on import" is turned off.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled.png)

Due to the black nature of the distributor the scanner can struggle to see this.

However all the relevant information we need to create the cap is there.

When 3d scanning an object there are many things to consider.

- Will the Scanning dust damage anything on the component? (like the electronics inside a distributor)
- How much information do we need to capture to achieve the outcome of our design intent?
- What is the budget to consider when working on this project?
- If I am paying to have this item scanned, how much extra is it going to cost to capture everything?

For these reason, it is quite common to only capture a flange face, or limited amount of information so that we can do the job with the least amount possible.

Create a Sketch on the top plane, then using the perimeter circle tool draw the hole positions, location boss and any other geometry we need to consider for the cap.

For its application, we will cut the contact tower used for the spark off the distributor (highlighted in yellow)

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%201.png)

Close this sketch and name it "Reference Geometry"

When we look at the model front on we can see that the top plane is actually at the boss heights for the mounting screws, not the mating face for the cap.

Under Xtract3d we are going to use the create Entities menu to create a single point on this mounting face.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%202.png)

Click Create entity → New sketch → 3d Points

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%203.png)

Now we can click on the mesh surface and a red 3d point will appear.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%204.png)

Click create and solidworks will create a new sketch with this point in it.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%205.png)

We are now able to create a plane on this face.

Go back to Features → Reference Geometry → Plane

Select the top plane and this point. If you cannot see the Top Plane to pick it, click on the black triangle next to your part name in the graphic window to see the feature tree

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%206.png)

We can now select the Top Plane and 3d Point from the view window.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%207.png)

This will create a plane Parrallel to the Top plane coincident with the point.

We can now sketch on this plane and create our geometry for our cap.

Create a sketch and 'convert entity' the outline circle. Draw the 2x triangle bosses and power trim it all away

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%208.png)

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%209.png)

Extrude boss this shape 8mm

On our new reference plane, create another sketch, convert entity the outer diameter and extrude boss this 32mm

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2010.png)

After extruding use the section view button and slice the model through either the front or right plane.

We will use this view to see how much material we need to remove to clear all the internals of our CAS.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2011.png)

Click the green tick and the view will remain sectioned while we continue to do other operations to our Cap.

Again, select the Reference Plane 'Plane 1' and create a sketch. Convert Entity the inner diameter of our reference geometry.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2012.png)

Now extrude cut this 29mm from the plane. You may need to toggle the direction of cut use the Direction Arrows under the Title 'Direction 1'

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2013.png)

Complete the operation by clicking the green arrow.

This time we are going to create a sketch on the Top plane.
We are going to use this to project a cut downward into the distributor to remove the material to add clearance for 2x triangular bosses.

Turn off Section view by clicking the section view icon on the display bar at the top of the graphical window.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2014.png)

Now select the 2 triangular areas on top top of our part that we have already modelled holding the control key as we click each to capture them.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2015.png)

Click 'Convert Entities'

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2016.png)

If we rotate our model around we can see that the sketches are "inside" our 3d model sitting on the top plane.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2017.png)

When we execute an 'extrude cut' → 'through all' from this position in the downward direction we will know that we have removed the material necessary to clear these ledges.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2018.png)

Hiding our mesh by right clicking on it in the feature tree, and selecting the 'Eye' we will be able to rotate our model around and see this small detail we have just done.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2019.png)

The last things we need to do are our clearance holes on the screws, some finishing and a final check.

Select reference 'Plane 1', create a sketch and draw 2x center point circles on our 2 bolt holes.

Give them equal relationships and dimension 1x circle at 6.5mm

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2020.png)

Extrude cut through all through our cap. Again you may need to toggle the cut direction as we are going up through the model.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2021.png)

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2022.png)

Go around the model and check that our cap clears what we need to.

A good tool is to expand the 'Solid Bodies' menu in the feature tree.
Right click the solid we are working on (our Cap) and click 'Change Transparency'

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2023.png)

This will make our 3d model appear like glass and allow us to see any part of our mesh that could be intersecting the cap and clashing with it.

Move the model around until you are sure that nothing interferes with our Cap

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2024.png)

An area to be considerate of are these 2x Tangs on one of the mounting bosses

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2025.png)

At this point if we need to, we can go back and edit the sketch of the original boss extrude.

Click the Arrow next to the first Boss Extrude operation to see the sketch used to create it.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2026.png)

Right Click this sketch and select 'Edit Sketch'

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2027.png)

This will allow us to edit and modify this geometry to clear these bosses

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2028.png)

Because the geometry we used are converted entities from the 2x wings on our Cap this geometry will automatically be updated from the changes we have made.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2029.png)

This is why it is good practice to create Reference Geometry and convert entities from this.

But be mindful that there are some drawbacks too this as well which we will encounter in other lessons.

Go through and Fillet everything and make the Cap look attractive.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%2030.png)

I would suggest 3d printing in PLA before printing in Nylon or any other high temperature material to ensure that everything fits as expected.

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled.jpeg)

![Untitled](L7%20-%20SR20DE%20Dizzy%20cap%20from%203d%20Scan%20f72728eac7bd4b97a2dd8288035a023f/Untitled%201.jpeg)

The final application for this project was 10x CAS Caps printed in Carbon Fibre Reinforced Nylon-6 for Drift Direct. They have all been in operation since 2018

Unfortunately we do not have any pictures of the finished caps in service.
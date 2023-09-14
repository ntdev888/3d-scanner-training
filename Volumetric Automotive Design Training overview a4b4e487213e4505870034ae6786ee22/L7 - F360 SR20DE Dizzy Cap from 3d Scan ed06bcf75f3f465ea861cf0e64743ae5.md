# L7 - F360 SR20DE Dizzy Cap from 3d Scan

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

We are going to do something different to the last lesson and we are going to upload our 3d scan into the cloud.

Click Upload in the Data Menu

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled.png)

Drag and drop our 3d scan mesh onto the “drag and drop” button.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%201.png)

Wait for the mesh to upload.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%202.png)

---

### Why are we doing this?

**There is a quirk with Fusion 360. If you import a mesh into a component through the Mesh → Create → Insert Mesh, we create a ‘dumb’ body that we cannot interact with.**

**However for this component and others we need to be able to select the mesh vertices to create planes.**

**The intention of these tutorials is to show many different methods to sometimes do the same action. This is why in the previous tutorial we imported the mesh through the Insert Menu.**

---

Our mesh has been successfully imported and opened.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%203.png)

We are now going to decimate the mesh so that our computer is able to handle the 3d information. Go to the mesh menu.

Select the Reduce command.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%204.png)

The reduce menu will appear.

We want the software to re-mesh proportionally and use the Adaptive algorithm to create a uniform finish on our mesh body. Depending on how good your CAD pc is, reduce it as much as you need to be able to deal with the mesh body.

Keep in mind that the more reduction you apply the less detailed your mess body will be increasing the risk of error.

DO NOT HIT PREVIEW if you value your time. 

Click OK and allow the software to reduce the mesh.

Refrain from using the computer until the loading bar is completed.

 

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%205.png)

We now have our reduced mesh body.

---

### IMPORTANT

**Fusion 360 ‘upload mesh’ function does not allow you to select the scale of the mesh body. The default for the software is to bring it in Centimeters. This is incorrect as we did the original scan in millimeters.**

**We need to scan the mesh down to 0.10 
I have brought this to the attention of my local Autodesk agent and it is a known bug.**

---

Select Scale;

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%206.png)

Apply a 0.1x Scale to the mesh.

Ensure that you select the Origin as the scale point.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%207.png)

Click OK.

Use the move body command to rotate the mesh body around so that we can work on the top face.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%208.png)

We want to set the Pivot point to be the component origin.

Select the ‘Set Pivot’ Triad to change the location.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%209.png)

Pick the component origin then click the green tick next to ‘set pivot’

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2010.png)

Rotate the part 90 Degrees so that the distributor cap end is at the top.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2011.png)

Click OK.

---

### NOTE

**Standard Practice in Fusion would have us create a component independent from the Mesh. However we need to use the mesh to reference and drive geometry we create.** 

**This is no clear process yet to handle meshes in a tidy way.**

**For this reason we are going to ‘copy’ our Mesh in the Data Tab so that we do not modify or loose the time we have just spent establishing our 3d scan.**

---

Go into the data menu and copy the 3d Scan

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2012.png)

Rename it to SR20DE CAS CAP

Now we can freely create the cap.

I personally do not like working with a white background in my CAD environments however when a Mesh displayed is too detail you are likely to need to change the visuals so that you can distinguish the part easier.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2013.png)

The reason it is difficult to distinguish the part is due to the mesh density of our 3d scan (or the detail we have captured during scanning)

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2014.png)

Fusion is showing us all these triangle edge lines and at scale this makes the part appear dark with a shadow cast over it.

With the design process however we want as much detail captured as possible to ensure we produce the most accurate part that we can.

On the top plane create a sketch.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2015.png)

When we look at our component from the Right we can see the sketch plane intersecting our model at the height our cap will sit flush against.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2016.png)

This is a good place to start drawing our overall dimensions for our CAS Cap.

Using the **3 point circle** draw the outer shape of the Cap.

Also Capture the detail to cover the Distributor contactor

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2017.png)

We will be cutting this contactor off and removing the points rotor from the distributor when we mount our cap.

Trim up to produce an enclosed region for extruding.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2018.png)

Finish Sketch.

Push/Pull this so that the solid extends 5-7mm above the top of the rotor shaft.

At 27mm I can see that we just intersect the top of the shaft.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2019.png)

Extrude to 34mm

Checking around the model we need to make sure that none of the mesh body interferes with our solid.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2020.png)

We now want to shell out our cap so that our Distributor Electronics fit inside.

We can see when we look at the model, we have features that the cap can locate against.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2021.png)

Create a Sketch on the top XY Plane and draw a **3 point circle** around this feature.

If we fit nicely to this spigot feature, we actually interfere with the Rotor Pickup.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2022.png)

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2023.png)

As we do not have a cap available to look at, we can only assume that there is detail in the cap to clear this feature.

As it is only a Cap I am going to give clearance on this, and instead run tight clearance on the screw positions as a form of location.

 Convert our 3 Point circle to construction geometry.

Then create an offset entity 1mm from it.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2024.png)

Finish the Sketch.

Hide our mesh body, and extrude cut our cavity 31mm into our cap.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2025.png)

Click Inspect → Section Analysis 

Select the XY Plane and click OK

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2026.png)

We can now see the detail inside our cap and insure that nothing is colliding.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2027.png)

To turn off section analysis we click the ‘Eye’ in the Browser tree

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2028.png)

This is an excellent tool as we can turn it on and off whenever we wish during the design process.

Now we want to create the 2 tabs that attach our cap to our distributor.

We are going to create a 3d point plane using the vertices’ of our 3d scan to drive these points.

Select Construct → Plane through 3 points

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2029.png)

Select 2 points on one tab face.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2030.png)

Move to the other and select a single point.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2031.png)

This will give us a plane that is the best average across those 2 faces.

Good rule of thumb is that we are looking for the best “average” across objects when it comes to 3d scanning.

Create a Sketch on this plane.

Also turn on our sketch we used to cut out the cap cavity

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2032.png)

Using 3 point circles, tangent lines and projecting the geometry from the cavity sketch I created the below.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2033.png)

Next repeat the process on the other tab.

Notice to pay attention to these upstands so they do not interfere with the cap.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2034.png)

One thing I do like about fusions design process, is we do not need to cut and trim all this geometry to extrude the features we want.

Instead we can just select the regions and then push/pull them to the desired height. 

Extrude 5mm.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2035.png)

Our cap is looking relatively complete.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2036.png)

We can now goo through and liberally apply fillets and then 3d print.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled%2037.png)

Test fit.

![Untitled](L7%20-%20F360%20SR20DE%20Dizzy%20Cap%20from%203d%20Scan%20ed06bcf75f3f465ea861cf0e64743ae5/Untitled.jpeg)
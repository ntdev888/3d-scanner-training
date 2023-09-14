# L3 - F360 Drawing of a Gear Knob

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

This lesson we will be using revolve in CAD to create a gear knob for turning or 3d printing

Process

- Discuss thread pitch on shifter
- Understanding the revolve tool
- Mechanical threads in CAD
- Export for manufacturing

In this lesson we are going to cover how to draw a Gear Knob so that we can 3d print it from Carbon Fibre reinforced Nylon.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled.jpeg)

Open Fusion 360, and create a new sketch on the Front Plane.

Draw a Line from the origin upwards 30mm long, Dimension this and convert it to a Centre line.

This is going to be the axis we drive our Revolve function around.

Next draw a horizontal line to the right, vertical line downwards ending in the same plane as our centreline end and then another horizontal line to the right.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled.png)

This is the start of our threaded hole we are going to use to screw our gearknob onto our gear selector with. 

Dimension our newly created geometry as per below.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%201.png)

When we dimension from the line/point to the centre line, it will change to a diametric value.

This is because Fusion knows that we intend to revolve this geometry by adding the Centreline to our sketch.

Go through and model the shape you wish you have for your Gear Knob.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%202.png)

I find it best to roughly draw the shape you want then tweak it in with dimensions.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%203.png)

Ensure that you enclose the shape of your Gear Knob.

When doing the revolve function, if you do not region off your sketch, you will end up with a hollow body that the software will consider a collection of surfaces and not a solid body.

Finish your Sketch.

 

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%204.png)

Next select the Revolve function from the Create tool bar.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%205.png)

Because we created the Centreline in our sketch, Fusion 360 is intuitive enough to know that this is the axis we wish to revolve our sketch around and populates that information into our dialog box.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%206.png)

We do not need to adjust any of the default settings for this, so click OK to complete the revolve function.

---

**NOTE: This tutorial is based on a project I completed in Solidworks for a selection of Carbon Fibre Nylon 3d printed Gear Knobs I did as a production run. The next stage of this tutorial is 5 pages to explain in Solidworks. Fusion 360 has a fantastic thread forming tool which we will go through now eliminating the need to create our own thread forms and helical tool paths!**

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%207.png)

---

Rotate our Gear Knob around so that we have access to the underside hole we created for our thread.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%208.png)

We are going to create a dome at the bottom of our threaded hole so that we can 3d print this part without supports.

Go Fillet, and select the bottom inner edge.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%209.png)

Increase the fillet size by dragging the arrow into the part until it reaches its maximium amount. (This technically will be close to R5.35 or half the diameter of the hole we have created)

Lets inspect our fillet.
To do this we are going to take a cross section of our part.

Go to Utilities → Section Analysis

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2010.png)

The dialog box will prompt you to select a face to section the part through. These need to be planar faces or work planes.

Select the Right (YZ) Plane

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2011.png)

Select OK

A new Analysis folder will appear with our cross section in it.

To turn it off, just click the ‘eye’ next to this folder.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2012.png)

Now we can inspect our Dome and see that it is a full form.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2013.png)

Now it is time to create our thread.
We create the Dome first to stop self intersecting features that could cause anomalies in our model.

Down the track this can lead to failed prints, failed features or strange inflections (visual unwanted spikes of surfaces in our model).

Lets form our thread for 3d printing.

Click create and go down to “thread”

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2014.png)

Select the inside face of our threaded hole.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2015.png)

Change the size to 12.0mm and the Designation to the thread pitch of your selector.

For our case we are going with M12x1.5 to suite a Toyota Gearbox.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2016.png)

“Why did we make the hole 10.70?”

This allows us to manually do a helical cut thread into our part if this feature fails to resolve.

Now we tick on the Modeled option in our Thread Dialog box.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2017.png)

This saves us drawing a 3d helix → creating a perpendicular plane to it → drawing our thread form then loft cutting our thread form into the part.

Do not worry though as we will go over these skills in future lessons.

Click OK once you see the thread formed.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2018.png)

We can see that Fusion has preserved our Dome, and created our 3d form that we can now print.

Turn of your analysis and fillet the hard edges of your Gear Knob for better feel.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2019.png)

Select the edges → Fillet 

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2020.png)

We have now completed our Gear Knob.

If you want to add detail to the top of the shifter, you can do this by selecting the top face → Create Sketch → drawing what you want

Additionally if you wish to put a logo in of your Brand/Company select the top face of the Shift.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2021.png)

Then, Insert → Canvas → insert from my computer and select the image you wish to put on.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2022.png)

Scale and position to fit.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2023.png)

Click Ok

Select the Top of the Gear Knob again and create a sketch.

Go through and trace your shape using the Line and Arc tools creating enclosed areas.

Ensure there is atleast 0.6mm between regions, this is to ensure the slicing software is able to fit the print nozzle into this space. For this part I used a 0.4mm nozzle to capture the detail and Markforged Onyx material.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2024.png)

Go through and fillet off any detail that may cause failures.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2025.png)

Select the Regions you wish to cut into the face.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2026.png)

Push/Pull cut or raised Boss your logo.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2027.png)

Be sure that the depth is divisible by the layer height. I use 0.6 as it can be divided by 0.10mm, 0.15mm and 0.2mm giving me a range of print options.

Hide your Canvas to reveal the geometry you have created.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2028.png)

Now we can export our part as an STL and print.

**Material: I cannot recommend 3d printing gear knobs without extensive testing of the material before use. If a print is to fail through a layer line while driving there is a risk this can distract the driver causing them to crash.**

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2029.png)
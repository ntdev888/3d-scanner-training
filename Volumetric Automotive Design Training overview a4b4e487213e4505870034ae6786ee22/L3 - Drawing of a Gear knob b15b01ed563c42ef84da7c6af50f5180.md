# L3 - Drawing of a Gear knob

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

In this lesson we are going to cover how to draw a Gear Knob so that we can 3d print it from Carbon Fiber reinforced Nylon.

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled.jpeg)

Create a new part and create a sketch on the front plane.

Start by creating a centre line from the origin, this can either go up or down depending on your desired orientation for the finished product.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled.png)

Because we create a centerline, we have a hidden tool available to us when dimensioning.

before clicking to complete the dimension, if we move the mouse cursor to the opposite side of the centerline, we are pormpted with a diameter dimension.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%201.png)

This will be useful, as we are creating a round Gear Knob and when measuring any existing geometry with a caliper, the dimension we will record will be diametric not radial. 

Create your desired shape, this can be any dimensions you feel comfortable with.

The only critical dimension is the 10.70mm which is highlighted below.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%202.png)

This is the hole diameter required to produce our thread.

For this example we are making a Gear Knob for a Toyota W58 gearbox. This has a thread pitch of M12 x 1.25mm

The suggested drill size for an M12 x 1.25mm thread is 10.80mm, we model this at 10.70 so that when we 'cut the thread' away from the model it produces a complete thread form.

Exit the sketch and click 'Revolve Boss/Base' 

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%203.png)

 

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%204.png)

If you have more than one construction line in the model you will not get a preview of your revolved geometry. 

To fix this, click the box "Axis of Revolution" and select the center line you wish to revolve your geometry around.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%205.png)

You should get the above result.

As with the previous tutorial and all future work we are going to leave the fillets to the very end of the modelling process. 

You may feel drawn to apply this now, but it is best to leave these until the very end. 

We do this so if we modify the fillet geometry we do not have any unintended consequences with them updating geometry to other parts of the model.

Now it is time to model the thread.

Select the top of the Gear Knob, create a sketch on it, draw a circle concentric to the 10.70mm hole that is there and dimension this at 12mm.

This will be the curve that drives our thread pitch.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%206.png)

Close the sketch

Go to the tool bar; Insert → Curve → Helix/Spiral and select

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%207.png)

Select the 12mm circle we just created and you will have a dialog box on the left hand side that looks like below.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%208.png)

The dimensions in this box maybe different depending on what you did on a previous job as the amount of revolutions, start angle and pitch will be remembered.

Populate the pitch at 1.25mm, reverse direction if you are modelling downwards like myself or leave this unchecked if going up. Set the amount of revolutions to be 20.

This will mean our thread goes 25mm down into our Gear Knob. 
We do not want this to go further than the 30mm we allowed for or we will have problems with printing the final part.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%209.png)

Click the tick and complete the operation.

We are now going to create our thread shape.

This is 2d geometry that is projected along the path of our spiral we just created.

However we need to attach this geometry to the helix so that Solidworks knows how to use it.

For this we will need to create a plane that is linked to it using the Reference Geometry → Plane tool

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2010.png)

We are going to get the Reference Plane dialog box pop-up;

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2011.png)

From here we are going to pick the helix and the start point for the First and Second reference. 

Once we pick the helix, hover the mouse over the start point to be able to select this, it will appear as an orange dot. 

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2012.png)

This geometry will not be selectable until you pick the helix first.

Once selecting both it will attach the reference plane to the end of our helix perpendicular to the edge.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2013.png)

Create the thread form on the plane with a 60 degree equal triangle that is 1.25mm deep

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2014.png)

You will notice that it has been drawn away from the origin, this is because we are going to add a relationship between the tip of our thread form (triangle) and our helix.

To make it easier we are going to rotate the view slightly to see the helix in 3d easier to ensure that our form matches up in the correct place. 

Select the tip point and the helix and add the pierce relationship

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2015.png)

The form will not lock on to the helix and turn black to show it is fully defined and unable to be moved.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2016.png)

Now using the swept cut tool, we are going to project this form around our helix.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2017.png)

Select our thread form sketch for the profile, and the helix for the path and confirm

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2018.png)

We will now have our thread form we can 3d print.

Some who are familiar with thread forms will notice that this form is not 'true' of what is usually machined. However with 3d printing and the nature of Nylon as a material, I have tested many different shapes, and this is the best for a 'locking action' on our Shifter to ensure it does not unwind itself.

In a section view we can check and see our formed thread

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2019.png)

Next we want to add a 0.1mm fillet radius to the bottom of this form to help the 3d printing software with 'slicing' 

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2020.png)

We are now on to adding the fine details to the model.

This includes a recess in the top as the thread form stops abruptly. As the model is now, if we produced this part we would not be able to screw it on to the shifter.

Create a sketch on the top face of our Gear Knob, draw a 12.50mm circle and extrude cut this 2mm deep into the Shift Knob

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2021.png)

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2022.png)

Go through and add our external fillets. and finishing touches.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2023.png)

3d prints do not like sharp angles, for this reason we are going to 'Full Radius' the bottom of our hole to ensure that any load from shifting is transferred from the shaft into the Knob evenly.

Create a fillet selecting edge of the bottom of the threaded hole and increase the fillet size until it ends just below where the thread ends

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2024.png)

Make sure that it does not influence the thread as it could cause the operation to fail.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2025.png)

Save your file.

If you wish to add a logo to the top, go through an import the image into the sketch as we have done in Lesson 1 and 2 → scale it to the size of the shifter → trace it → then extrude cut into the top.

Save the file as a STL so that we can import this into our slicing software.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2026.png)

When you reach this screen, go into the options menu, and ensure that the resolution is set to 'Fine'

This reduces faceting in the finished product and can often be the reason why round objects in CAD come out faceted with hexagon like sides when printed.

![Untitled](L3%20-%20Drawing%20of%20a%20Gear%20knob%20b15b01ed563c42ef84da7c6af50f5180/Untitled%2027.png)

![Untitled](L3%20-%20F360%20Drawing%20of%20a%20Gear%20Knob%203560012e429248ee9ecb5e95816b34f5/Untitled%2029.png)
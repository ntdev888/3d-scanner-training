# L1 - 2d Drawing a flange for profile cutting

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

This lesson is to go through the process of drawing a 2d turbo flange from a pencil rubbing

- Rubbing from gasket or flange
- import into sketch in solidworks
- orientate and scale appropriately
- dimension and check against original part
- extrude
- save file

Rubbing from Gasket or Flange;

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled.png)

The most straight forward process that is accurate enough for fabrication is to take a rubbing of a flange or gasket.

This way you can purchase a gasket from a retailer for the flange you require which you will use anyway in the final application, take a rubbing of this, then organise to get it profile cut.

For 2 years I worked for a large Fabrication and Laser cutting company here in New Zealand, and this was still a process used by experienced engineers.

The most import thing is scaling. 

When we scan the rubbing into a 2d printer it will never be dimensionally accurate. However when we manipulate this in CAD we will be able to scale and check the size at this point.

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%201.png)

Gasket Rubbing

I will often take a rubbing of the gasket for dimensions, as it will give me clear defined edges. But during this process it is quite easy for the paper to move so you get ghosting which you can see in the upper left corner.

For this reason I also like to trace the gasket;

![Untitled](L1%20-%20F360%202d%20Drawing%20a%20flange%202aaf04f9aa1e4e0d9ff07fdab8b830e3/Untitled%202.png)

Traced Gasket

This will give us positional accuracy, however the dimensions of the interior and exterior profiles will be out by half the thickness of the pen or pencil we are using.

One thing to be clear, this process is only useful for the replication of profiles that are to be used for assemblies and components where 0.5mm errors are acceptable. 

Import into sketch in Solidwork's

As outlined earlier, we are only going to touch on the basics of CAD throughout this material.

There are a lot of good tutorials and exercises all over the internet that are very well written and very comprehensive.

This is not why your here though, you are here to learn the Gems, the gold, and have those 'aha' moments. 

So lets get into that.

First we need to put our rubbing as the background of a sketch in a new part. 
So create a sketch on the top plane. Before doing anything else, the we want to go to;

Tools → Sketch Tools → Sketch Picture

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled.png)

This will allow us to bring in the scan we did.

We will be prompt to select the file we would like to use. Go and find the rubbing we have scanned in and select open

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%201.png)

Now we have the sketch picture dialog box on the left hand side, and the scan on our screen.

We are going to use the scale tool which is integrated into the process.
This can be see as the horizontal construction line on our picture.

What we are going to do, is to have this line set across the largest dimension of our rubbing, then using the real gasket input the dimension that it is using our digital calipers (a ruler is also fine, but remember, the result is only as good as the tools that you use)

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%202.png)

First I drag the left hand side point to the edge of my flange rubbing

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%203.png)

Then drag the other end to the edge of our flange rubbing.
Once we have done this, Solidworks will bring up a dimensions dialog box asking us how long this line is.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%204.png)

We put our dimension in, hit the tick and the image will scale

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%205.png)

The image will often move away from the origin, so we just need to drag and reposition it.

We do this, as the output of you manufacturing file will also have the datum in this position. Although it is easy to change at a later stage, it can be annoying and cause headaches for some processes.

A tool that we will use a lot through all of this material is the perimeter circle tool.

The ease of approximating circular positions is far faster using this tool than any other method.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%206.png)

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%207.png)

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%208.png)

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%209.png)

Click around the rubbing edge to create a circle

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2010.png)

When we do a quick check, we measure 10.99mm with our calipers on the real gasket and get 11.09 in CAD.

This is reasonably good, and will not be an issue either way as they are clearance on a M10 bolt/stud.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2011.png)

In X we get a positional accuracy of +0.22mm when measured against the gasket (85.99mm when measured)

With clearance on an M10 stud even if we did not have the gasket to measure, this would be acceptable for fitment although not the best.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2012.png)

However in Y we are getting a positional accuracy of +0.02mm when compared to the gasket.

This likely means we have some distortion in our printer/scanner in the X direction which is something we need to take into consideration for future projects.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2013.png)

Establish the sketch relation ships between the holes and lets do the outside profile.

Note;

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2014.png)

During the rubbing process we can see that I slipped and have a ghost of the circle edge. 

Because we have a trace of the gasket as well, once we finish sketching our part we will compare the positions of these holes with it.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2015.png)

For the outside and inside of the gasket I draw an oversized and undersized box.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2016.png)

I then carefully bring these lines into position by zooming in on my rubbing edges and adjusting until I get a best good overall fit.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2017.png)

Boxes in position.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2018.png)

Now we fillet the inside and outside corners in separate operations. This allows us to change their dimensions independently to ensure we get radii that fit the rubbing.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2019.png)

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2020.png)

Adjusting the fillet parameter I increase/decrease the value until I get an arc of best fit.

Before confirming this, I go through and check each corner carefully. 

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2021.png)

Repeat for the outside.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2022.png)

Once complete, extrude our sketch into a flange.

At this point I would export this file as an STL and 3d print a test part to mock up.

![Untitled](L1%20-%202d%20Drawing%20a%20flange%20for%20profile%20cutting%20bec344f5f27d41bbb7363bac52453b45/Untitled%2023.png)

An example of a 3d printed flange mocked up on a BMW head before designing the rest of the intake manifold.
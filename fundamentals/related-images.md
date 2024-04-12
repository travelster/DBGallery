---
layout: default
title: Related Images (Find Similar)
permalink: /related-images
parent: Fundamentals
grand_parent: DBGallery
nav_order: 95
---
# Related Images

Select a photo and DBGallery can show related photos in a sidebar!  

To get to that sidebar, press the button shown in the sreenshot below near the top right.  An image must be selected for the sidebar to appear.

Please note: Not all DBGallery systems have this feature enabled.  Contact your DBGallery administrator, or DBGallery support, to have this turned on.  There is no additional cost. 

<p style="padding-left: 5%;"><img style="border: 1px solid black;" src="/assets/RelatedImages-Overview.jpg" /></p>
<p style="padding-left: 5%;"><strong>Figure 1:</strong> Related images button and sidebar.</p>

There are the categories of related images:

1) **Visually similar:** Uses an algorithm to show images that have similar colors and contrast. While it can be a great and find images that a normal text search doesn't find, these results can sometimes seem way off.  This is because the algorithm uses pixels level elements rather than seeking similar objects the human eye might see as the same.

2) **Similar time:** Shows images with a Date Taken within 5 minutes before and after the selected photo.

3) **Similar Objects:** Expermental: Finds photos that have an object recognition keyword that matches the selected image's first object recognition keyword. [This is an experimental early release and a future release will show those most similar to all the selected photo's keywords.]

**Where it looks for related images:** The current folder and all sub-folders.  If in a Collection, it searches the entire system.

Each category will show a maximum of 28 images.

This feature works for photo formats only.

## Doing things with the sidebar images
**Drop them somewhere:** Single images in the sidebar can be dragged to folders or collections.  This would be the same as when dragging them from the normal gallery thumbs view (except only single images can be dragged).  Dropping a related image thumb to a folder moves the image file to that folder.  Dropping a thumb to a collection adds the photo to that collection.  The screenshot video below shows an image being dragged from the sidebar.

**View them:** Photos can be opened from there by clicking the view button which appears over the photo thumb.

**TIP:** It can often be useful to go to the folder a related image belongs to.  To do this open the image, go to the Full Data panel, and click a folder name (see the red arrow below).

<p style="padding-left: 5%;"><img style="border: 1px solid black;" src="/assets/RelatedImages-SelectingAFolder.png" /></p>
<p style="padding-left: 5%;"><strong>Figure 2:</strong> Click a folder name to go to that folder.</p>


## In Action

<p style="padding-left: 5%;"><img style="border: 1px solid black;" src="/assets/RelatedImages-UsageVideo.gif" /></p>
<p style="padding-left: 5%;"><strong>Figure 3:</strong> Related Images: Pressing the related images button and dragging a resulting thumbnail.</p>


**See Also**
<ul>
<li><a href="https://docs.dbgallery.com/duplicates-detection" target="_blank">Duplicates Detection</a>
</li>
</ul>
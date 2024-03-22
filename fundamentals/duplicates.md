---
layout: default
title: Duplicates Detection
permalink: /duplicates-detection
parent: Fundamentals
grand_parent: DBGallery
nav_order: 90
---

# Duplicates Detection

DBGallery detects duplicates as they are uploaded and can also check for them across the entire collection.

## Detection during Upload
The most appropiate place to check is when they're being added to the system.&nbsp; There is a checkbox in its upload dialog which everyone should use: Detect Duplicates.&nbsp; When duplicates are detected the upload page lights up a "Resolve Duplicates" button (Figures 1), which leads to a "Resolve Duplicates" page (Figure 2 below).
<p style="padding-left: 5%;"><img style="border: 1px solid black;" src="https://cdn.dbgallery.cloud/Download.aspx?id=142886&amp;public=f3d6a47c313445c4a0c48b22763360d1&amp;854219628" /></p>
<p style="padding-left: 5%;"><strong>Figure 1:</strong> The upload dialog having detected duplicates.</p>
<p>&nbsp;</p>
<p style="padding-left: 5%;"><img style="width: 80%;" src="https://cdn.dbgallery.cloud/Download.aspx?id=142885&amp;public=8e23ead8150848e3bfaa7fe3beb93217&amp;646002302" /></p>
<p style="padding-left: 5%;"><strong>Figure 2:</strong> The resolve duplicates page shown when there are duplicates detected during upload.</p>


## Global Duplicates Detection
Unfortunately the upload process by itself isn't always sufficient. Duplicates can sneak through or exist as part of the initial set of images added to DBGallery during system setup.

For these scenarios there is a Global Duplicates Check. It is found in the Tools menu of DBGallery's main page (see Figure 3 below). It looks and operates very much the same as the upload check, with some additional options to support the extra effort to clean up a large image collection after initially populating it, or when there are a large number of duplicates for other reasons. 

<p style="padding-left: 5%;"><img style="border: 1px solid black;" src="/assets/Duplicates-ToolsMenu.png" /></p>
<p style="padding-left: 5%;"><strong>Figure 3:</strong> The Global Dupicates Check menu.</p>


There is an option to ignore a group of duplicates when in rare case they're valid or need to be kept around while it's decided what the initial creator wants to do with them.  Press "Hide from dup searches" and they will not appear in subsequent duplicates searches.  These can be viewed in the future by ticking the "Show those set as hidden from duplicates searches" checkbox in the upper right corner.


<p style="padding-left: 5%;"><img style="border: 1px solid black;" src="https://cdn.dbgallery.cloud/Download.aspx?id=142884&public=b26a9e425e6842abacae8a2afd49a7e6&1106663234" /></p>
<p style="padding-left: 5%;"><strong>Figure 4:</strong> The global duplicates check page.</p>

<hr>
<strong>Also See:</strong> Our <a href="https://dbgallery.com/avoid-duplicates">Avoiding Duplicate Images</a> blog post, which includes how to avoid the need to have duplicates in an image collection.
---
layout: default
title: Version Control
permalink: /versioning
parent: Digital Asset Management
grand_parent: DBGallery
nav_order: 30
---

# Version Control

Version control in DBGallery allows multiple versions of the same file to be stored in the system while only the latest version is shown in search results. Older versions are available when needed by going to the Versions panel when viewing an image.

**Features of version control in DBGallery:**
- Upload different file types (perhaps the draft was a jpeg file, but the latest is in photoshop format);
- Replace the current version directly from the preview window;
- In the upload dialog, if the filename already exists, an option to create a new version is available;
- Multiple versions of file show as one thumb in search results, meaning users without concern for previous versions need not see them.
- Metadata versions are visible to show a history of data changes made to an image. This makes an excellent addition to activity/audit logging because each image shows who has made what changes to data;
- See a side-by-side comparison of older versions compared to the latest, and zoom in to see the details of each;
- Restore older versions of a file, making them the latest version so show in search results;
- Download any older versions of a file;
- Clear the entire Version history and leave only the current one;
- Version control works with any file type (photos, Excel files,. 3d images, Photoshop and Illustrator images).

**Covered here:**
- Where versions are found
- Uploading a new version
- Side-by-side version review
- Downloading previous versions
- Make a previous version the latest
- Data versions

## Where versions are found

Shows below are two versions of a photo: the latest one on the left has had an annotation added.  When viewing any image, press the VERSIONS panel button just to the right of the top center to get here.

![Where versions are found](/assets/Versions-Side-by-Side.jpg){: .ml-8}

When a file has multiple versions, there is a button with the number of versions in the thumbs top right corner of image thumbs in the main gallery.  Clicking that button will automatically go to the Versions panel of image preview.
![Versions button atop thumbnails](/assets/versions-with-button.png){: .ml-8}

## Uploading a new version

There are two ways to upload a new version.  The first one being the most common.  

1) Select the New Version Upload button as shown in the top-left of the above screenshot.  The page shown below will appear, where a new version may be uploaded.  Press the green Add File button or drag and drop the new version onto that window.  Once uploaded, close the window by pressing the X in the top-right corner and the latest version just uploaded will be displayed.  To compare the newest and previous versions, use the VERSIONS panel and select any previous image version.

![Uploading a new version](/assets/Versions-UploadFromPreview.jpg){: .ml-8}

2) When on the generic upload dialog, if that same filename exists in the folder being uploaded to, the user is presented with the option to create a new version.  There may be multiple "Create a new version" buttons, as shown below.  The top one allows the option to be chosen for all files.

![Uploading a new version from the upload dialog](/assets/Versions-CreateNewVersion-UploadWindow.jpg){: .ml-8}

## Side-by-side version review
Comparing uploaded versions of photo file provides a means of doing a detailed comparision.  When in the Versions panel, click any image version to compare it with the latest.

While versioning works with any file type, the side-by-side view shown below will work only with photo and other photo-like formats such as Photoshop and Vector files (any files listed as Level 1 and Level 2 in the Photos section of <a href="https://dbgallery.com/file-formats">File Formats Supported page.)</a>

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="https://cdn.dbgallery.cloud/Download.aspx?id=92677&public=ffb7f74dcece45f3bac7cd387b8b7016&607545244" width="100%" alt="Size-by-side version comparison"/></p>

## Downloading previous versions
Any previous version may be downloaded by pressing the three dots to the right of that version.  

![Download or Restore Previous Version](/assets/Versions-DownloadOrRestorePreviousVersion.jpg){: .ml-8}

## Make a previous version the latest

Only the latest version will show in search results.  If a previous version is the one which should be available for viewing and download, choose "Restore this version" as shown in the screenshot immediately above.  A new version will be created (10 in the above screenshot example).

Sharing Note: If a new version of a shared image is uploaded, the latest version is shown.   I.e. The version shared can be replaced by adding a new version.

## Data Versions

While not true versions, all changes to an images data may also be seen from the VERSIONS panel.  Immediately below, Mr Marketing set the Expiration Date to 10/31/2021, changed the Image Status from Approved to Requires Adjustment and made a License/Expiry note.  Just before that, Jane Yu added 3 keywords, and DAdmin changed the Author from DBGallery to DBGallery Training.

Data changes are not shown here by default: De-select the top toggle button "Only show versions with a changed image".  The "Collapse/Expand details of all records" can also be convenient rather than needing to click each change to see the details.

![Data Versions](/assets/Versions-Data.jpg){: .ml-8}

Beyond simple data changes, all activities affecting a given image is shown here.  That may be an image being moved from one folder to another, it being added to a Collection, or when it was opened via a DBGallery Share link.  <a href="/activity-monitoring">Activity Monitoring</a> has more on this topic.

## Related
Our blog post: <a href="https://dbgallery.com/dam_versioning">Digital Asset Management Version Control: What Is It and Why Is It Important?</a>


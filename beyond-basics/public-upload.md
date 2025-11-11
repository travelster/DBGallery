---
layout: default
title: Public Upload
permalink: /public-uploads
parent: Beyond Basics
grand_parent: DBGallery
nav_order: 40
---

# Public Uploads

A folder can be configured to allow anyone with a created link to upload images.  Essentially, simply press the 3 dots next to a folder, choose a few options, and then sent the created link to those who will upload images.  A few key points:
- No login is required.  
- Images already existing in the folder cannot be seen by those opening the link.
- Nothing can be done within the folder by those opening the link except upload files.
- The link can be disabled or removed completely using DBGallery's Share Management page.

## Creating the Public Upload Link
There are 3 steps
1. Select the 3 dots to the right of the folder where files will be uploaded.
2. Choose configuration options.
3. Send the public upload link to those who will perform the uploads.

### 1. Select the folder
Any folder may be chosen for configuring an upload.  Typically you would start with an empty folder, although that isn't a requirement.  As in the screenshot below, folders where uploads occur may be under a parent folder, where the sub-folders are shared with specific individuals or groups, but again, that isn't neccessary.

<p><img src="/assets/public-upload-3dots.jpg" style="margin-left: 5%" alt="Public folders - select the folder" width="33%"/></p>

### 2. Choose the options
Options here include:
1. <strong>Naming the share</strong>: Naming the share is highly recommended.  This makes the link look more meaningful to those receiving the link.  As importantly, it make it more easily found in Share Management (more on that below).
2. <strong>Set an expiry date</strong>: An expiry date may be set here, or later Share Management can be used to disable or delete the link. 
3. <strong>Subscribe to upload notifications</strong>: Choosing this option will provide email notifications when uploads occur, a great way to be in the know when new files arrive. 

<figure style="text-align:center;max-width:600px;margin:2rem auto;">
  <img src="/assets/public-upload-config-named.jpg" alt="Public folders - config options" style="width:66%;height:auto;border: 2px solid black; border-radius: 10px;">
  <figcaption style="margin-top:0.75rem;font-style:italic;color:#555;">
    Here the public folder is named '2020's External Contributors'. Note how the link includes that name.  This is also the identifier to find it in Share Management.
  </figcaption>
</figure>

If the Public Folders configuration window looks similiar to the <a href="https://docs.dbgallery.com/sharing">Sharing</a> configuration window, it is because they are indeed functionaly related. Public Uploads share a folder for uploading, and is accessible by anyone with the link.  Sharing allows viewing of images by anyone with the link.  This is also why both these are combined on the Share Management page.

### 3. Share the link
Upon pressing the "Save and copy public upload link" button, the link is copied to the clipboard and is ready to provide to recipients.  That may be via email, a messaging platform such as Slack, or dropping it on social media.

## What the user sees
When a recipient clicks the link, they will see the following:

<figure style="text-align:center;max-width:600px;margin:2rem auto;">
  <img src="/assets/public-upload-user-sees.jpg" alt="Public folders - what the recipient sees" style="width:100%;height:auto;border: 2px solid black; border-radius: 10px;">
  <figcaption style="margin-top:0.75rem;font-style:italic;color:#555;">
    What the user sees before adding any images.  Either drag and drop files, or press Add files to choose.  This works the same no matter the device.
  </figcaption>
</figure>

<strong>NOTE: </strong>Existing files are never shown.  Even if clicking that link again the same user would not see the files they previously uploaded. 

Duplicates: If duplicate filenames are uploaded, they will automatically be give a new name, such as i-am-a-duplicate(2).jpg.

Logo: The logo shown will be the one set within your DBGallery.  The default will be the DBGallery logo.  See more in <a href="https://docs.dbgallery.com/white-labelling">White Labelling</a>.

<figure style="text-align:center;max-width:600px;margin:2rem auto;">
  <img src="/assets/public-upload-user-sees-after-upload.jpg" alt="Public folders - what the recipient sees after upload" style="width:100%;height:auto;border: 2px solid black; border-radius: 10px;">
  <figcaption style="margin-top:0.75rem;font-style:italic;color:#555;">
    Upon uploading, thumbs are shown.  Clicking the Show Details button near the top right would show a subset of metadata, including what was AI generated.
  </figcaption>
</figure>

If the link is opened on a mobile device it will appear somewhat differently but has the same functionality.

## Finding public uploads in Share Management
The Share Management page is an important resource for managing public upload links. This is the same Share Management page used for sharing images.  The indicator to distinguish between image shares and public upload links is the far left column: Share Type.  Hover the mouse pointer of the folder icon in that column to see exactly which folder was configured for the upload.  

Other than the Share Type column, the other columns and functionality are essentially the same.  The Assets Count will be blank for public uploads.

--SCREENSHOT--


## FAQs
<strong>Q</strong>: Can uploads be to a Collection?
<br/>
<strong>A</strong>: Collections can never have files uploaded to them directly, whether it be public uploads or internally by those logged in.  Collections hold pointers to the original file locations in a folder. Hence uploads only ever occur to a folder. 
<br/>
<br/>
<strong>Q</strong>: Can a shared folder link be protected by a password?
<br/>
<strong>A</strong>: If password protection is required, create a user within DBGallery and provide upload permissions to any specific folder for that user.
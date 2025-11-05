---
layout: default
title: Public Upload
permalink: /collections
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
Any folder may be chosen for configuring an upload.  Typically one would start with an empty folder.  As in the screenshot below, folders where uploads occur may be under a parent folder, where the sub-folders are shared with specific individuals or groups.

<p><img src="/assets/public-upload-3dots.jpg" alt="Public sharing - select the folder" width="33%"/></p>

### 2. Choose the options
Options here include:
1. <strong>Naming the share</strong>: It is recommented to name the share.  This makes the link look more meaningful to those receiving the link.  As importantly, it make it more easily found in Share Management (more below on that).
2. <strong>Set an expiry date</strong>: An expiry date may be set here, or later Share Management can be used to disable or delete the link. 
3. <strong>Subscribe to upload notifications</strong>: Choosing this option will provide you with email notifications when uploads occur, a great way to be in the know on when new files arrive. 

--SCREENSHOT--

### 3. Share the link
Upon pressing the "Save and copy public upload link" button, the link is copied to the clipboard and is ready to provide to recipients, whether that be via email, a messaging platform such as Slack, or dropping it onto a social media app.

## What the user sees
When a recipient clicks the link, they will see the following:

--SCREENSHOT--

If the link is opened on a mobile device it will appear somewhat differently but has the same functionality.

## Finding public uploads in Share Management
The Share Management page is an important resource for managing public upload links. This is the same Share Management page used for sharing images.  The indicator to distinguish between image shares and public upload links is the far left column: Share Type.  Hover the mouse pointer of the folder icon in that column to see exactly which folder was configured for the upload.  

Other than the Share Type column, the other columns and functionality is essentially the same.  The Assets Count and Open Count will be blank or have a 0 for public uploads.

--SCREENSHOT--


## FAQs
Q: Can uploads be to a Collection?
A: Collections can never have files uploaded to directly, whether it be public uploads or internally by those logged in.  Collections hold pointers to the original file location in a folder. Hence uploads only ever occur to a folder. 

Q: Can a shared folder link be protected by a password?
A: If password protection is required, create a user within DBGallery and provide upload permissions to any specific folder for that user.
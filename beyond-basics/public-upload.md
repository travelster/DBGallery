---
layout: default
title: Public Uploads
permalink: /public-uploads
parent: Beyond Basics
grand_parent: DBGallery
nav_order: 40
---

# Public Uploads

Simply send a created link to invite recipients to upload images to a specific folder.

For those that need a secure and simple method to collect digital content from external parties—such as vendors, partners, 
or suppliers — Public Uploads provide a highly convenient solution. This link acts as a secure, controlled intake channel, enforced by the strictly upload-only mandate: <strong>external users can deposit files of any type and size into a designated folder, but they are absolutely prevented from viewing, editing, or deleting any 
existing assets within the system.</strong>

Reiterating a few key points:
- No login is required.  
- Images already existing in the folder cannot be seen by those opening the link.
- Nothing can be done within the folder by those opening the link except upload files.
- The link can be disabled or removed completely using DBGallery's Share Management page.
- Only SuperAdmin roles can configure Public Uploads.


## Creating the Public Upload Link
There are 3 steps:
1. Select the 3 dots to the right of the folder where files will be uploaded.
2. Choose configuration options.
3. Send the public upload link to those who will perform the uploads.

<strong>Permissions Note: </strong>Only SuperAdmins can create Public Upload links. 

### 1. Select the folder
Any folder may be chosen for configuring an upload.  Typically you would start with an empty folder, although that isn't a requirement.  As in the screenshot below, folders where uploads occur may be under a parent folder, where the sub-folders are shared with specific individuals or groups, but again, that isn't neccessary.

<p><img src="/assets/public-upload-3dots.jpg" style="margin-left: 5%; height:auto;border: 2px solid black; border-radius: 10px;" alt="Public folders - select the folder" width="33%"/></p>

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

### 3. Invite anyone to upload images
Upon pressing the "Save and copy public upload link" button, the link is copied to the clipboard and is ready to provide to recipients, inviting the to upload digital assets.  Do so via email, Slack, or any other way you normally communication with those you are inviting to upload.

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

Logo: The logo shown will be the one set within your DBGallery, usually your own.  The default will be the DBGallery logo.  See more in <a href="https://docs.dbgallery.com/white-labelling">White Labelling</a>.

<figure style="text-align:center;max-width:600px;margin:2rem auto;">
  <img src="/assets/public-upload-user-sees-after-upload.jpg" alt="Public folders - what the recipient sees after upload" style="width:100%;height:auto;border: 2px solid black; border-radius: 10px;">
  <figcaption style="margin-top:0.75rem;font-style:italic;color:#555;">
    Upon uploading, thumbs are shown.  Clicking the Show Details button near the top right would show a subset of metadata, including what was AI generated.
  </figcaption>
</figure>

Mobile Devices: If the link is opened on a mobile device it will appear somewhat differently but has the same functionality.

## Workflow Integration
Newly uploaded images may be automatically given a workflow status of "New" or "Needs Review".  Internal staff would then manage the review queue, checking the quality and licensing status, or any use any other internal acceptance criteria, of the assets.  They would then be changed to an "Approved" or "Published" status, and in most cases, moved to a more appropriate folder within DBGallery.  See <a href="https://docs.dbgallery.com/workflow">Workflow</a> for how this is setup.

## Finding public uploads in Share Management
The <a href="https://docs.dbgallery.com/sharing#4-share-management">Share Management</a> page is an important resource for managing public upload links. This is the same Share Management page used for sharing images.  The indicator to distinguish between image shares and public upload links is the far left column: Share Type.  Hover the mouse pointer over the folder icon in that column to see exactly which folder was configured for the upload.  

Other than the Share Type column, the other columns and functionality are essentially the same.  The Assets Count will be blank for public uploads.

<figure style="text-align:center;max-width:600px;margin:2rem auto;">
  <img src="/assets/public-uploads-share-mgmt.jpg" alt="Public folders - Share Management" style="width:100%;height:auto;border: 2px solid black; border-radius: 10px;">
  <figcaption style="margin-top:0.75rem;font-style:italic;color:#555;">
    Accessed from Tools | Share Management, the Public Upload links can be identified by the folder icon in the Share Type column. Roll the mouse cursor over that icon to see the full folder name.
  </figcaption>
</figure>


<figure style="text-align:center;max-width:600px;margin:2rem auto;">
  <img src="/assets/public-uploads-sharemgmt-right-columns.jpg" alt="Public folders - Share Management operations columns" style="width:100%;height:auto;border: 2px solid black; border-radius: 10px;">
  <figcaption style="margin-top:0.75rem;font-style:italic;color:#555;">
    From here you may copy the link, suspend (disable) the link, or delete it.  When suspended or deleted, someone clicking the link will see a message indicating the link is no longer available.
  </figcaption>
</figure>

## Security
The Public Uploads feature is designed with robust security in mind, ensuring that only individuals who receive the shared link can contribute files. Access is strictly limited to uploads: no viewing of existing images in the folder, no deletions, no edits, and no other manipulations are possible, preventing unauthorized exposure or alteration of assets. Links are generated exclusively by SuperAdmins and can be configured with an expiry date, suspended, or fully revoked via the Share Management page at any time, rendering them inactive and displaying an error to any further access attempts. Without password protection (which requires full user accounts for enhanced controls), this link-based model prioritizes simplicity and containment, making it an ideal solution for secure, one-way contributions from external collaborators.


## FAQs
<strong>Q</strong>: Can uploads be to a Collection?
<br/>
<strong>A</strong>: Collections can never have files uploaded to them directly, whether it be public uploads or internally by those logged in.  Collections hold pointers to the original file locations in a folder. Hence uploads only ever occur to a folder. 
<br/>
<br/>
<strong>Q</strong>: Can a shared folder link be protected by a password?
<br/>
<strong>A</strong>: If password protection is required, create a user within DBGallery and provide upload permissions to any specific folder for that user.
<br/>
<br/>
<strong>Q</strong>: The name Public Uploads can be misleading since only those with the invitation link can upload.  What other names for this feature were considered?
<br/>
<strong>A</strong>: Guest Uploads was the main other contentor.  Others included: Invite Links, Guest Uploader, Secure Dropzone, Asset Contribution Portal, External Ingest Link, One-Way Asset Collection, and even Fast File Drop.
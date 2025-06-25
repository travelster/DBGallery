---
layout: default
title: Sharing
permalink: /sharing
parent: Fundamentals
grand_parent: DBGallery
nav_order: 40
---

# Sharing

Sharing is simple and secure, with no login required.

## Selecting Images to Share 
To share images select any number of thumbs and press the Share images button.

![Sharing: Select and Share Button](/assets/Share-Button.webp)

## Share Settings
The quickest way to share the selected images would be to press Ok to have the URL copied to the clipboard, then drop it into an email, chat message, a document, or anywhere else.

![Sharing Popup](/assets/Share-Dialog.webp)

Share links do not require a login.

Important options in the share window are:
- **Expiry Date**: The link will display an Expired message after the date and time set. This cannot be changed later.
- **Share Name**: Give the share a name rather than using the default long random set of characters.  This allows it to be found more easily later in the Share Mgmt page (see below) and, perhaps more importantly, makes for a much more meaningful URL that the recipients see.
- **Download**: When checked, those opening the URL will be able to choose among download image resolutions.  There will also be a Download All option if more than one image is shared.  Each of these options are available to the recipient under the Download menu botton in the top left corner.
- **Subscribe to a notification**: Receive an email each time the URL is opened.

Shared images are viewed directly from their location within DBGallery, not a copy placed somewhere.  If the image’s data is updated the new data will be seen when the share link is opened.  As well, if an image is deleted it will no longer show when the share link is opened. See "Changes after Sharing" below for more on how what the recipient sees can change.

**TIP: Use Share Names.** There is little reason not to, and the benefit of being able to easily identify all your shares on the Share Management page (see screenshot below) is worth the effort.  And of couse the URL receiver seems a much friendlier URL.

## Unfurling

Share links will unfurl when dropped onto most social media apps.  In the animated example to the left, Slack unfurls the link to flip through thumbs of the images being shared.

![Sharing Unfurling](/assets/Share-Unfurling.gif)

## What the Recipient Sees

When the link is clicked the following would appear.
![Sharing: What the recipient sees](/assets/ShareGallery.jpg)

Clicking on the larger image to the right in the above screenshot expands the image.  

![Sharing: What the recipient sees](/assets/Share-Result.webp)
What's a available from there:
- Zoom using the mouse wheel, or you fingers if on a touch screen.
- Move to the next or previous image.  Upon clicking the large image, the right and left arrow keys on your keyboard work to move back and forward.  One a mobile devic, or any touchscreen, swipe right and left. 
- Make comments on the image.  May not be available if a system admin turned Comments off in system preferences.
- There is a lower thumbsbar also available here.  If not shown, click the up arrow in the lower right corner area.
- Depending on the options chosen when the share was created:
    - Download options in the top left corner.
    - A slideshow button.
    - View image data in the Info tab.

Return to the gallery view by pressing Esc or clicking "Return to Gallery".

## Changes after Sharing
After an image is shared, several things can change regarding what the user will see.

- **Data Layout:** If the data layout setting is changed after sharing images, the new layout is what the user will see (not the data layout when the images were shared).  See <a href="/datalayoutsettings">Data Layout Settings</a> for more on configuring which data is shown for shared images.
- **Image Data:** Any data which has changed since the share was created will be seen by those opening the share link.
- **The image itself:** If a new version of a shared image is uploaded, the latest version is shown.   I.e. The version shared, and hence the one viewed by share link recipients, can be replaced by adding a new version.  See <a href="/versioning">Version Control</a> for how a new version may be uploaded.



## Share Management

Found under the Tools menu, the share management page provides a means to view previous shares and perform operations on them.

- Search for a share name.
- Get a copy the share URL.
- Suspend shares (similar to expire but can be turned back on).
- See the number of times the share has been opened.
- View the number of images in the share.
- Find previous shares by sorting by when the share was created, its name, expiration date, and more.

If logged in as an administrator, shares activity will be shown for all users. When logged in as an individual user, share activity for that use only will be displayed.

![Share Management](/assets/Share-Management.png)

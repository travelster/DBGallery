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

When the link is clicked the following would appear:
![Sharing: What the recipient sees](/assets/ShareGallery.jpg)

Notes on this shared gallery view:
- **Logo:** The logo shown is the one set in the main DBGallery. By default it is DBGallery's logo, but that can be easily changed.  See <a href="/white-labelling#logo-change">Logo Change</a> under White Labelling.
- **Thumbs:** The thumbs shown are in pages, with the number of thumbs shown depending on your devive screen resolution, up to approx. 18.
- **Text Shown below thumbs:** Here is the name of the share, as entered when the share was created. Below that in smaller text is the profile name of the user who created the share along with the total number of images.
- **Below the larger image on right:** the filename, the image count and current position, the Download current image and Download All images buttons.
- **Arrow Keys:** The up and down arrows are used to move to the next and previous image. 
- **Expand to an even larger image:** Click the larger image to the right to open an expanded view, covered in detail in the next section below.

**Keyboard TIP**
Use the right or down keyboard arrows to navigate to the next image.  Use left or up keyboard arrows to navigate to the previous image.

**Mobile APP Note**
The mobile version of the shared gallery view is diffent in that it shows just the list of thumbs, where the user must tap an individual thumbs to see an expanded image. From  there, the Expanded View section below describes the funcationality (although the image in the screenshow won't be exactly the same).


## An Expanded View
Clicking on the larger image to the right in the above screenshot expands the image: 

![Sharing: What the recipient sees](/assets/Share-Result.webp)
What's a available from there:
- **Zoom:** Use the mouse wheel to zoom in and out, or your fingers if on a touch screen.
- **Navigating to Next / Prev:** Move to the next or previous image.  Upon clicking the large image, the right and left arrow keys on your keyboard work to move back and forward. One a mobile device, or any touchscreen, swipe right and left. 
- **Comments:** Make comments on the image.  May not be available if a system admin turned Comments off in system preferences.
- **Thumbsbar:** There is a lower thumbsbar also available here.  If not shown, click the up arrow in the lower right corner area.
- Depending on the options chosen when the share was created:
    - **Download** options in the top left corner.
    - A **slideshow** button.
    - **View image data** in the Info tab.

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

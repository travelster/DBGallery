---
layout: default
title: Sharing
permalink: /sharing
parent: Fundamentals
grand_parent: DBGallery
nav_order: 40
---

# Sharing

Sharing is simple and secure, with no login required by those receiving the shared images.

The steps to sharing, which are each covered below, are:
- Select the images to share
- Set share options
- Post or send the newly created share URL 

## Selecting Images to Share 
To share images select any number of thumbs and press the Share images button. (To select images, use the Ctrl or Shift key along with the left mouse button as you would in Windows Explorer or Mac Finder.  There is also a Select All button in DBGallery's menu.)

![Sharing: Select and Share Button](/assets/Share-Button.webp)

## Share Settings
The quickest way to share the selected images would be to press Ok to have the URL copied to the clipboard, then drop it into an email, chat message, a document, or anywhere else. Note again that share links do not require a login.

![Sharing Popup](/assets/Share-Dialog.webp)

Alternatively, set these options in the share window:
- **Expiry Date**: The link will display an Expired message after the date and time set. This cannot be changed later.
- **Share Name**: Give the share a name rather than using the default long random set of characters.  This allows it to be found more easily later in the Share Mgmt page (see below) and, perhaps more importantly, makes for a much more meaningful URL that the recipients see. The title also shows in the share, the "Interesting Architecture Across the Globe" text in the **What the Recipient Sees** section below.
- **Download**: When checked, those opening the URL will be able to choose among download image resolutions.  There will also be a Download All option if more than one image is shared.  Each of these options are available to the recipient under the Download menu botton in the top left corner.
- **Subscribe to a notification**: Receive an email each time the URL is opened.

**TIP: Name the Share** | It's highly recommended that shares are provided a name. Why? There is little reason not to and the benefit of being able to easily identify all your shares on the Share Management page is worth the effort (see screenshot below).  Secondly, the URL the receiver sees is significantly friendlier than a long scary looking set of random characters.  This is mentioned because a year after releasing the share mgmt page and the ability to name shares, some clients still have many randomly generated share URLs instead of proper names!  Finally, the name appears as the title when a recipient opens a share URL (see What the Recipient Sees section below).

**TIP: See what the recipient sees** | In a new tab or browser window, paste the share URL to see exactly what those opening the share will see. 

## Changes after Sharing
Shared images are viewed directly from their location within DBGallery, not a copy placed somewhere. After an image is shared, several things can change regarding what the user will see.

- **Data Layout:** If the data layout setting is changed after sharing images, the new layout is what the user will see (not the data layout when the images were shared).  See <a href="/datalayoutsettings">Data Layout Settings</a> for more on configuring which data is shown for shared images.
- **Image Data:** Any data which has changed since the share was created will be seen by those opening the share link.
- **The image itself:** If a new version of a shared image is uploaded, the latest version is shown.   I.e. The version shared, and hence the one viewed by share link recipients, can be replaced by adding a new version.  See <a href="/versioning">Version Control</a> for how a new version may be uploaded.
- **Deleted images:** If an image is deleted it will no longer show when the share link is opened. 

The first two items above are relevent only when the "View Info (data details) panel" checkbox was selected in the share setting window above.

## Unfurling

Share links will unfurl when dropped onto most social media apps.  In the animated example to the left, Slack unfurls the link to flip through thumbs of the images being shared.

![Sharing Unfurling](/assets/Share-Unfurling.gif)

## What the Recipient Sees

When the link is clicked the following will appear:

![Sharing: What the recipient sees](/assets/ShareGallery.jpg)

**Theme-based:** The whitish background is shown when DBGallery's white theme is chosen in Tools / Preferences.  The above background may be Blue or Brown depending on the choice there.  **RECOMMENDATION:** Our white theme, introduced in the spring of 2025, is our recommended theme. It has a cleaner and more modern look. If your DBGallery has a your company logo, check that it is compatible with any new theme chosen, possibly using a new logo within DBGallery (See <a href="/white-labelling#logo-change">Logo Change</a>).

Notes on this shared gallery view:
- **Logo:** The logo shown is the one set in the main DBGallery. By default it is DBGallery's logo, but that can be easily changed, and may have already been on your DBGallery.  See <a href="/white-labelling#logo-change">Logo Change</a> under White Labelling.
- **Thumbs:** The thumbs shown are in pages, with the number of thumbs shown depending on your devive screen resolution, up to approx. 18.
- **Text Shown below thumbs:** Here is the name of the share, as entered when the share was created. Below that, in smaller text, is the profile name of the user who created the share, along with the total number of images.
- **Below the larger image on right:** Shown here is the filename, the image count and current position, the Download current image and Download All images buttons.
    - Download note: In this view the "Download this image" downloads the full resolution original image. To download difference resolutions/sizes, use Download in the top left corner of the Expanded View.
- **Arrow Keys:** The up and down arrows are used to move to the next and previous image. 
- **Expand to an even larger image:** Click the larger image on the right to open an expanded view, covered in detail in the next section below.

**Keyboard TIP:** | Use the right or down keyboard arrows to navigate to the next image.  Use left or up keyboard arrows to navigate to the previous image.

**Mobile APP Note:**
The mobile version of the shared gallery view is different: it shows just the list of thumbs.  From there the user must tap an individual thumb to see an expanded image. See Expanded View section below which describes the funcationality after a thumb is pressed.


## Expanded View
Clicking on the larger image to the right in the above screenshot expands the image: 

![Sharing: Expanded view with an higher resolution](/assets/Share-Result.webp)

What's a available from there:
- **Zoom:** Use the mouse wheel to zoom in and out, or your fingers if on a touch screen.
- **Navigating to Next / Prev:** Move to the next or previous image.  Upon clicking the large image, the right and left arrow keys on your keyboard work to move back and forward. One a mobile device, or any touchscreen, swipe right and left. 
- **Comments:** Make comments on the image.  May not be available if a system admin turned Comments off in system preferences.
- **Thumbsbar:** There is a lower thumbsbar also available here.  If not shown, click the up arrow in the lower right corner area.
- Depending on the options chosen when the share was created:
    - **Download** options in the top left corner.
    - A **slideshow** button.
    - **View image data** in the Info tab.

Return to the gallery view by pressing Esc or clicking "Return to Gallery" in the top-right corner (not shown in the above screenshot).


## Share Management

Found under the Tools menu, the share management page provides a means to view previous shares and perform operations on them.

- **Search:** Search for a share name. [Top-right corner]
- **Copy the URL:** Get a copy the share URL. [Button to the right of the "Status" column]
- **Suspend shares** (similar to expire but can be turned back on). [The 'eye' button the the right of Copy URL]
- **Delete the share:** You may delete a share after it has been created. This is especially useful if you've sent out a link with a mistake, or you want to later add or remove an image. You may delete the share and create a new one with the same name. Because the URL will have the same name, when the URL previously sent is clicked it will open the new share. [Button not shown in the above screenshot, but is to the right of the Suspend button]
- **Share Creator:** Column to view which user created the share.
- **Open count:** Column showing the number of times the share has been opened.
- **Shared images count:** Column to view the number of images in the share.
- **Sort:** Find previous shares by sorting by when the share was created, its name, expiration date, and more, by clicking column headers.

If logged in as an administrator, shares activity will be shown for all users. When logged in as an individual user, share activity for that use only will be displayed.

![Share Management](/assets/Share-Management.png)


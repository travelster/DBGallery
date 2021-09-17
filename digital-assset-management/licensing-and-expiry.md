---
layout: default
title: Licensing and Expiry
permalink: /licensing
parent: Digital Asset Management
grand_parent: DBGallery
---

# Licensing and Expiry (IP)

Intellectual property (IP) licensing will be important if your company utilizes licensed digital assets.  


DBGallery allows for:
- Setting the date an asset expires (typically when a license agreement expires)
- Pointing to a license agreement document
- Making license/expiry notes 

Each of these are shown within the red box:

![Licensing Fields](/assets/Licensing-FDV.png)

## Entering Expiry and License Info
From the main gallery view, find and select the image or images to edit, and press Open/Preview.  Once opened, ensure Full Data is selected (as at the top middle of the above screenshot) and enter the required information (its within the red box in the above screenshot).  

Notes on each data field:
- **Expiration Date:** Press the calendar icon to bring up a calendar.  Once chosen the date can be edited (although cannot be keyed without first chosing a date from the calendar).  I.e. Rather than scrolling the calendar to Aug 1, 2029, select Aug 1 of the current year and change it to 2029.

- **License Document URL:** Typically points to an image within DBGallery (copy the link from the URL bar when viewing the document in DBGallery), but any URL may be used.

- **License/Expiry Note:** A freeform place to store any notes related to license and expiry.

**Permissions Note:** While anyone with permission to view the image can view this data, only user roles with "Can control asset expiration" are able to edit this data.   More on this in the "Controlling who can set licensing and expiry info" section below.

## Search Results Involving Expired Assets
When an expiry date is set on an image it will not show in search results.  The exception here is for roles that are set to have the ability to see expired assets .  In general, expired assets should not be available for usage, but for system admins and those managing asset licensing and expiry, they should be available.  Hence the role permission.  

All users may search for assets while 'Expires within 2 wks', 'Expires after 2 wks', or those which have no expiration date.  Only those with permissions to control asset expiration are able to search for Expired assets.  Each of these are shown in the screenshot below.

Expiration Icon Note: All images with an expiry date will have a clock icon.  That icon can have 3 states:
- Black: Expires in more than 2 weeks.
- Yellow: Expires with 2 weeks.
- Red: Already expired.

Pause the mouse cursor over the clock icon to see the date the asset expires (as shown in the lower-right)

![Licensing Search](/assets/Licensing-Search.png)


## Controlling who can set licensing and expiry info
Only user roles with permission to control asset expiration can enter expiry and licensing information of an image, or view expired assets.  SuperAdmin roles always have this permission.  To turn this on or off for a role, choose Tools | Roles from the main menu.  Press the edit icon (it looks like a pencil) for that role, then toggle the "Can control asset expiration (and can see expired assets)" checkbox.   

![Licensing Role Permission](/assets/Licensing-RoleSetting.png)

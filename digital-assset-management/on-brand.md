---
layout: default
title: On-brand
permalink: /on-brand
parent: Digital Asset Management
grand_parent: DBGallery
---

# On-brand

There are scenarios where some users should not have access to image assets which are not deemed to be on-brand.  Examples can include out-dated images, or those in draft by the creative department.  In both cases they should not be available to some groups of users.

Merriam-webster defines <b>on-brand</b> as:

"appropriate to, typical of, consistent with, or supportive of a particular brand or public image or identity" (<a href="https://www.merriam-webster.com/dictionary/on-brand" target="_blank">https://www.merriam-webster.com/dictionary/on-brand</a>)
{: .px-6 }

## How on-brand works
When the on-brand feature is turned on (covered in the configuration section below), general users are unable to see images not flagged as on-brand (see the orange On-Brand toggle button below).  All search results for them will exclude images not on-brand.  When simply browsing around DBGallery in any way (searches, folders, collections, or data views), those images will be excluded.

The screenshot below shows where the On-Brand toggle is set: In the Full Data panel in image preview.  (Using Data Layout settings, this field may be placed elsewhere also.)

![The on-brand toggle](/assets/OnBrand-FDVToggle.jpg){: .ml-8}

Administrators will always see images regardless of being on-brand or not.  For administrators, as well as those that have the "Can see off-brand files" role attribute set (more on this in the role settings section below), they may search specifically for images which are on- or off-brand.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" width="80%" src="/assets/OnBrand-AdvSearch.jpg" alt="Advanced Search for On-brand"/></p>

If whether images are on- or off-brand is especially important, that indicator may be placed directly above thumbnails using Data Layout settings (seen here directly under each thumb):

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/OnBrand-UnderThumbs.jpg" alt="On-brand under thumbs"/></p>

## Configuring On-Brand
Start by turning it on in Tools | Preferences from the main page menu.  By default this feature is turned off, meaning no image assets have a brand attribute.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/OnBrand-TurnOn.jpg" alt="Turning on the On-brand feature"/></p>

If there are already images in your DBGallery, turning this on opens a dialog asking if existing images should be turned set as On-brand or Off-brand.  The choice to have all images set as Off-brand or On-brand is written to all asset files in the system.  NOTE: if all Off-brand is chosen here, non-administrators will no longer see any images.  That is because user roles by default cannot see Off-brand images.  Changing the setting in user roles is covered in the section immediately below.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/OnBrand-TurnOnDialog.jpg" alt="On-brand dialog"/></p>

## Setting which roles are able to see off-brand images
Administrators (those with the SuperAdmin role) can see all images, whether on or off brand.  All other users who should see off-brand images must be in a role that has the "Can see off-brand files" attribute checked.

To set the "Can see off-brand files" role, press the pencil / edit icon to the right of the role name to edit that role:

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/OnBrand-SelectRoleEdit.jpg" alt="The roles window edit button"/></p>

Once there, select one of the to brand-related checkboxes.  The first on allows the viewing of off-brand files, whereas the second option allows viewing as well as setting images as on- or off-brand.  Not that if the second is check, checking the first isn't needed as it intails both.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" width="80%" src="/assets/OnBrand-CanSeeOff-brandFiles.jpg" alt="OnBrand Role settings"/></p>

## Renaming On-brand: Calling it something else can introduce new functionally
On-brand can be renamed in Tools | Preferences:

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/OnBrand-Rename.jpg" alt="Rename On-brand text"/></p>

Clients reported that this handy field/feature had uses beyond just branding, where calling it something else can be quite useful.  This is because of the way images with this attribute turned off can be hidden from specific roles.  For example:

A rename could essentially provide new functionality:  "External Access".  In this case, if any client roles that didn't have the "Can see off-brand files" set would not be able to see those images.

Of course the rename could be something as simple changing it to OnBrand.  



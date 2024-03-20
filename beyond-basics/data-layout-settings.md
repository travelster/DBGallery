---
layout: default
title: Data Layout Settings
permalink: /datalayoutsettings
parent: Beyond Basics
grand_parent: DBGallery
nav_order: 3
---

# Data Layout Settings

Which data is viewed shown across various pages within the system can be of crucial importance.  Even when not critical, determining which data is shown, and where, can add significant convenience and value to the system and its image collection.

All DBGallery data fields can be arranged using these data layout settings, including custom fields.

Following are a couple examples of changes to data being displayed:

1) Data layout differences under thumbnails in the main Gallery View:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayout-UnderThumbs.jpg" alt="Configuring data under thumbs"/></p>

2) Different data shown to those opening shared images:
<p style="margin-left: 5%;"><img style="border: 1px solid purple;" width="100%" src="/assets/DataLayout-SharedView.jpg" alt="Configuring data in the shared view"/></p>

## Getting there
Access data layout settings from the Tools menu:
<p style="margin-left: 5%;"><img style="border: 1px solid purple;" width="100%" src="/assets/DataLayout-ToolsMenu.png" alt="Data layout setting menu"/></p>

## Which pages can have data layouts configured
Data layout settings can be customized for all those listed in the Data Layout Setting left sidebar:
<table>
<tr>
<td width="33%">
<img style="border: 1px solid purple;" src="/assets/DataLayout-LeftMenu.png" alt="Configuring data in the shared view"/>
</td>
<td>
<b>Gallery View:</b> The thumbs view on the main search page, where data shown above or below thumbs can be changed.
<br/>
<b>Shared View:</b> What those clicking a shared URL sees.
<br/>
<b>Preview Info:</b> The Info panel when previewing an image.
<br/>
<b>Full Data View:</b> The Full Data panel when previewing an image.
<br/>
<b>Dashboard:</b> The collection overview and launchpad.
<br/>
<br/>
<b>FAQ:</b> What is the difference between the <b>Your account layout settings</b> and <b>Global layout setting?</b>
<br/>
<b>A:</b> The lower part of the menu to the left, "Global layout settings", is available only to administrators and sets the default layout for all users.  
<br/>
<br/>
That default layout can be overridden by each user by changing those under "Your account layout settings".   Note that it is not possible to restrict users from changing their Gallery View data layout or their Dashboard layout, nor can they be reset to the default (i.e. users always have control over what they see there).  The other views, Shared, Preview and Full Data, cannot be controlled by individual users.
</td>
</tr>
</table>

## Configuring the Data Layouts
To configure data layout settings:
- **Add Data Fields:** Drag image data fields from the list on the left to the image card on the right.
- **Remove Data Fields:** Drag data fields from the image card back to the list to remove them.
- **Saving changes is not required.** They are automatically saved as changes are made. 
- **A page refresh is required** on any pages already open prior to data layout setting changes, on the device making the changes and any other users' devices which may have those pages open.

## Configuring Gallery View
Sample: adding a field to the data shown under thumbs in the Gallery View:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\ui-settings-gallery-view-example.gif" alt="Gallery view: Drag and drop data layout"/></p>

The Gallery View page area example:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\gallery-view-interface-screenshot.webp" alt="Gallery view: which area is affected"/></p>

The Gallery View is different from the other areas in that data **above** or **under** the thumbnails is configured seperately.  The above screenshot shows both the Data Under Thumbs and Data Over Thumbs.  Switch between them using the button under the sample image, then drag data fields from the left.

<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayout-OverAndAboveThumbs.gif" alt="Data layout settings: setting above and below data"/></p>


### Configuring Shared View
Sample: adding a field to the data shown under thumbs in the Shared View:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\ui-settings-info-example.gif" alt="Shared View: Drag and drop data layout"/></p>

A Shared View page area example:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\shared-view-interface-screenshot.webp" alt="Shared View: which area is affected"/></p>

### Configuring Preview Info
Sample: adding a field to the data shown under thumbs in the Preview View:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\ui-settings-info-example.gif" alt="Preview View: Drag and drop data layout"/></p>

A Preview Info page area example:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\info-interface-screenshot.webp" alt="Preview View: which area is affected"/></p>

### Configuring Full data view
Sample: adding a field to the data shown under thumbs in the Full Data panel:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\ui-settings-info-example.gif" alt="Full Data View: Drag and drop data layout"/></p>

A Full Data View page area example:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\full-data-interface-screenshot.webp" alt="Full Data View: which area is affected"/></p>


### Configuring The Dashboard
Configuring the Dashboard quite different from the other 'Data layout' settings.  Here the widgets on the dashboard is configured, not data fields.  

Sample: adding widgets to the dashboard:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\ui-settings-dashboard-example.gif" alt="Setting dashboard widgets"/></p>


From the Dashboard itself, whether it is shown upon login can be toggled, and the background image may be changed.  These two settings are set by and specific for each user.  The default is to not show the dashboard upon login.

<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayout-DashboardOtherSettings.jpg" alt="Dashboard settings"/></p>

NOTE: Click "How to use and where it will take effect" on any of the configuration pages for a reminder of how to drag and drop the fields and where they'll take effect.

<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayout-HowToLink.jpg" alt="Data Layout Setting help on each page"/></p>

## Restricting which data can be entered by users
While not obvious, administrators can determine which data can be entered by users, such as volunteer who only enter data for images.  This is done by:
1. Turning off Full Data View access in their role.
2. Using Data Layout Settings to determine which data is shown on the data.

In the screenshot below, a volunteer user can edit only keywords, description and 2 custom fields.  They are unable to see the Full Data panel.

<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayout-LimitedDataEntry.jpg" alt="Data Layout Setting help on each page"/></p>

### Sharing Note
If the data layout setting is changed after sharing images, the new layout is what the user will see (not the data layout when the images were shared).

## Troubleshooting
There are times when data layouts are changed by an administrator but those changes do not show for other users as intended (after a simple page refresh or that user logs in after the change).  When that occurs try the following:
1. Be sure to choose Global Layout Settings in the left menu.  They set the default for all users.  If those under "Your account layout settings" were chosen (the section above), they would set data layouts for only you.

    <p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="35%" src="/assets/DataLayout-GlobalLayoutSettings.png" alt="Data Layout Global Settings"/></p>

2. Refresh the other user's browser because sometimes it won't automatically pick up changes. If that doesn't work, use in Incognito window in Chrome (InPrivate in Edge,, Private Browsing in Safari) and login as that user again.  This will ensure the cache isn't being used.  If the new settings are shown in Incongito mode but not the normal mode then it is a cache refresh problem, where clearing the users browser cache should resolve it.

3. Users can set their own data layout setttings so it might be those you're seeing.  To set a users' data layout to the global default, press Reset to Default on their layout settings page.  This would immediately set their layouts to those which were set under Global Layout Settings.

    <p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="55%" src="/assets/DataLayout-ResetToDefault.png" alt="Data Layout Settings - Reset to Default"/></p>

4. If none of these work, please contact DBGallery support using our <a href="https://dbgallery.com/contact">Contact Form</a>.
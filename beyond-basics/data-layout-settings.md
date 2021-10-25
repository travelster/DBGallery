---
layout: default
title: Data Layout Settings
permalink: /datalayoutsettings
parent: Beyond Basics
grand_parent: DBGallery
nav_order: 1
---

# Data Layout Settings

Which metadata is viewed shown across various pages within the system can be of crucial importance.  If not crucial, determining which data is shown, and where, can add significant convenience and value to the system and its image collection. 

Following are a couple examples of changes to data being displayed.

Data layout differences under thumbnails in the main Gallery View:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayout-UnderThumbs.jpg" alt="Configuring data under thumbs"/></p>

Different data shown to those opening shared images:
<p style="margin-left: 5%;"><img style="border: 1px solid purple;" width="100%" src="/assets/DataLayout-SharedView.jpg" alt="Configuring data in the shared view"/></p>

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
<b>NOTE: Your Account <b>VS</b> Global Layout Setting</b>
The lower part of the menu to the left, "Global layout settings", is available only to administrators and sets the default layout for all users.  
<br/>
<br/>
That default layout can be overridden by each user by changing those under "Your account layout settings".   Note that it is not possible to restrict users from changing their Gallery View data layout or their Dashboard layout, nor can they be reset to the default (i.e. users always have control over what they see there).  The other views, Shared, Preview and Full Data, cannot be controlled by individual users.
</td>
</tr>
</table>

## Configuring the Data Layouts
To configure data layout settings:
- Add Data Fields: Drag image data fields from the list on the left to the image card on the right.
- Remove Data Fields: Drag data fields from the image card back to the list to remove them.
- Saving changes is not required. They are automatically saved as changes are made. 
- A page refresh is required on any pages already open before being visible.

Configuring Gallery View
Sample: adding a field to the data shown under thumbs in the Gallery View:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\ui-settings-gallery-view-example.gif" alt="Gallery view: Drag and drop data layout"/></p>

The page area being configured:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\gallery-view-interface-screenshot.webp" alt="Gallery view: which area is affected"/></p>


### Configuring Shared View
Sample: adding a field to the data shown under thumbs in the Shared View:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\ui-settings-info-example.gif" alt="Shared View: Drag and drop data layout"/></p>

The page area being configured:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\shared-view-interface-screenshot.webp" alt="Shared View: which area is affected"/></p>

### Configuring Preview Info
Sample: adding a field to the data shown under thumbs in the Preview View:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\ui-settings-info-example.gif" alt="Preview View: Drag and drop data layout"/></p>

The page area being configured:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\info-interface-screenshot.webp" alt="Preview View: which area is affected"/></p>

### Configuring Full data view
Sample: adding a field to the data shown under thumbs in the Full Data panel:
<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayouts-PlusWebCopy\ui-settings-info-example.gif" alt="Full Data View: Drag and drop data layout"/></p>

The page area being configured:
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
While not obvious, administrators can determine which data can be entered by users, such as volunteers logging in.  This is done by:
1. Turning off Full Data View access in their role.
2. Using Data Layout Settings to determine which data is shown on the data.

In the screenshot below, a volunteer user can edit only keywords, description and 2 custom fields.  They are unable to see the Full Data panel.

<p style="margin-left: 15%;"><img style="border: 1px solid purple;" width="80%" src="/assets/DataLayout-LimitedDataEntry.jpg" alt="Data Layout Setting help on each page"/></p>

### Sharing Note
After Sharing images, if the data layout setting is changed, the new layout is what the user will see (not the data layout when the images were shared).  Any data that has changed since the share was created will also be seen.

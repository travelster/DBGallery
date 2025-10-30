---
layout: default
title: White Labelling
permalink: /white-labelling
parent: Tailoring DBGallery
grand_parent: DBGallery
nav_order: 2
---

# White Labelling

## Logo Change
Change the logo in the top-right corner as well as the login page by rolling the mouse cursor over the existing logo and pressing the Change Logo button, as shown below.   To change back to the default DBGallery logo press the X button next to Change Logo.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/ChangeLogo.png" alt="White Labelling - Logo Change"/></p>

This changes both the top-right corner logo, as above, and the logo on the login page.

<p style="margin-left: 5%;"><img src="/assets/ChangeLogo-Login.png" alt="White Labelling - Login Logo Change" width="70%"/></p>

**Tip:** Use a transparent PNG for a better look, especially on the login page.  Or match the background with DBGallery bluest background.

## Browser Tab Icon
To set the icon shown in browsers' tab, select 'Upload and save' to choose either a .PNG or .ICO file.  This icon is also known as the site's favicon.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/ChangeLogo-Icon.png" alt="White Labelling - Icon Change"/></p>

## Color Theme
The DBGallery color theme can be changed to more closely match that of your organization. It is changed from DBGallery's main menu under Tools || Preferences.  

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/UI-Theme-Dropdown.jpg" alt="White Labelling - Theme color change menu"  width="50%"/></p>

The White theme is recommended as it is the cleanest and most modern.  

**Tip:** Try each of them, reverting back to the original if others don't look better.

**Notes:** The theme chosen is for all users, not just yourself.  Only system admins may change themes.

## Browser Tab Text
<p>For Enterprise subscriptions and On-premise installations, the text of the browser tab can be specified. On the web server, change the appsettings.config file to add the following:</p>
	<add key="MainHeaderText" value="My Company" />
	<add key="MainHeaderDefaultRight" value="" />

<p>
The default values are:</p>
	<add key="MainHeaderText" value="DBGallery" />
	<add key="MainHeaderDefaultRight" value="Digital Asset Management" />
<p>After changing tab text, stop and restart the IIS website.</p>

## Related
<a href="/dns-subdomain">Your own URL</a>
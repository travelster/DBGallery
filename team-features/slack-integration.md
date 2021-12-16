---
layout: default
title: Slack Integration
permalink: /slack-integration
parent: Team Features
grand_parent: DBGallery
nav_order: 50
---

# Slack Integration

DBGallery integrates with Slack to let users search across their entire asset collection directly from Slack.  Results may then be shared to channels or direct messaged to your Slack contacts.  It's very convenient for teams which use Slack regularly.  This article explains usage in detail and with examples on how you can use it. | <img src="/assets/Slack-DBGalleryIntegration.png" alt="DBGallery - Slack Integration"/>

|**NOTE:** DBGallery is currently awaiting the process of being available in the Slack App Directory.  In the mean time it may be added to Slack from DBGallery: https://cloud.dbgallery.com/slack.  This option currently available only to our Free and Small Team clients.  If you're an Enterprise on on-prem server client, please contact support for instructions on adding it to your service.

## Usage
As with other Slack apps, use / to begin a command.  All DBGallery commands begin with /dbgallery, so just typing /dbg and pressing enter is a good way to begin.  

Typing /dbgallery help will slow the available commands, primary search:

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Slack-Help.png" width="80%" alt="Slack Integration: Help"/></p>

## Search Examples
The exact same search commands available within DBGallery are available in our Slack app.  Type those search terms after "/dbgallery search" :
<ul>
	<li><b>/dbgallery search Conference</b></li>
        <ul><li>Searches all data across all images for the whole word Conference</li></ul>
    <li><b>/dbgallery search Conf*</b></li>
		<ul><li>Search for all words beginning with Conf</li></ul>
    <li><b>/dbgallery search +Conf* +Atlanta</b></li>
		<ul><li>Must have a word beginning with Conf and must include Atlanta</li></ul>
    <li><b>/dbgallery search +Conference -Europe</b></li>
		<ul><li>Must have Conference but not have Europe (looking for all non-Europe conference images)</li></ul>
    <li><b>/dbgallery search 'Marketing workflow logo'</b></li>
		<ul><li>Use single quotes to find images which have any of the words (without single quote only images with all the search terms are returned)</li></ul>
</ul>

<p></p>
Searches may be fairly complex:
<ul>
<li><b>/dbgallery search +Conference +Asia -China +"SGH-I337M"</b></li>
    <ul><li>Must include Conference and Asia, but not China and taken with a "SGH-I337M" camera model.</li></ul>
</ul>


## Working with Search Results
When search results are returned what is shown **only visible to you**.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Slack-WorkingWithResults.png" width="80%" alt="Slack Integration: Working with Results"/></p>

To share or view images from the search results there are 4 courses of action (from bottom up in the above screenshot):
1. **Save to my app**: Once pressed, and as shown in the 'Save to my app' screenshot below, go to the App section of Slack's left-side tree, and use the Share button to share to any DM (or anywhere else with Slack).
2. **Post to everyone in this channel**: Posts this image directly to the current channel.  Only available when in a Channel (not available in Direct Message chats, where a "Save to my app" is needed to share).
3. **Open this file in the browser**: Show just that one file in Preview mode in DBGallery in the default web browser.
4. **Show 54 results in DBGallery**: Show the full search result in DBGallery in the default web browser.

**Save to my app**:

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Slack-SaveToMyApp.png" width="80%" alt="Slack Integration: Save to my App"/></p>

## Working with Document Files
When looking to share or download documents from DBGallery (anything but photos, graphic formats, video and PDFs) search results will be shown without an image preview.  To share or download for viewing, use the "Save to my app" button, go to the app, and choose download or share.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Slack-WorkingWithDocumentFiles.png" width="80%" alt="Slack Integration: Working with Document Files"/></p>

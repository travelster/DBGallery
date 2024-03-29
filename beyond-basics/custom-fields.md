---
layout: default
title: Custom Data Fields
permalink: /custom-fields
parent: Beyond Basics
grand_parent: DBGallery
nav_order: 2
---

# Custom Data Fields

Custom fields extend search and data display capabilities by defining additional data fields specific to an industry or organization within DBGallery.  

They are used for data entry and their data is included in all searches.  You choose where this data is shown on various pages across DBGallery by using its Data Layout settings.  Where the data can be placed includes under or above thumbs in the main gallery view, the Info tab when viewing an image, and the data tab seen by those who images are shared to.  By default they appear only in the Full Data tab of image preview.

## Defining Custom Fields

From the Tools menu, choose Define Custom Data Fields.  From there, any number of custom fields can be added.  A sample list of fields:

<p><img src="/assets/Custom-Fields-Main.png" alt="Custom Fields Main Page" width="100%"/></p>

## Creating the first field
When first arriving on that page, it will have just an "Add Field" button.  Get started by pressing that button to have a new field appear.  No changes are made to the system until Save Changes is pressed.

<p><img src="/assets/CustomFields-AddFirstOne.png" alt="Custom Fields Adding a Field" width="100%"/></p>

## 2 Field Types
There are two types of fields, as shown to the right of the above screenshot:

**1) Text: a simple text input field.**
This is the most common type, and is a freeform field where any value can be entered.  
- The Label is the name of the field.
- The optional description is what will show in grey to provide the user inputting data a clue as to what the field is for.

An example: from the above first screenshot, a Client Name field would look like this when placed on the Preview's Info tab:

<p><img src="/assets/CustomFields-TextSample.png" alt="Custom Fields Text Field Exmample" width="100%"/></p>

Any type of data can be entered, such as dates or numbers.  But it is freeform text entry and there are not rules for the inputted format to enforce numbers, dates, etc. 

**2) List: A static dropdown list of data values.**
This type of field is especially useful when there is a static list of values that should be chosen from.  

The list will be presented to the user as a searchable dropdown list, meaning that as the user starts to type in that field it will filter the list, making it easier to chose from a large list.  This is a 'contains' search, meaning the user doesn't have to know what a value starts with, but can start by keying any character of a list value.

A simple but good example would be a list of seasons.  To try this, enter the seasons list as shown, seperated by semi-colons.  Outside this example, any number of values can be entered, hundreds or thousands.  

<p><img src="/assets/CustomFields-ListExample.png" alt="Custom Fields Text Field Example" width="100%"/></p>

A List field in action:
<p><img src="/assets/CustomFields-ListInAction.gif" alt="Custom Fields Action Example" width="100%"/></p>

**Editing values in a list** <br>
Any item change made on the custom fields definition page will not modify the values already assigned to images. To remove or edit existing list data values from images, go to the main gallery thumbs view and search for that value. Then select returned images from the search, opening them in Preview and removing or replacing that data.

**Converting a Text field to a List**                            
To convert an existing text field to a list, where all existing text values are moved to the list, simply change the Text field type to List.  This can be valuable when freeform text was entered prior to DBGallery's ability to have this static dropdown list. All unique values in the current Text field will be converted to a list!  It is also possible to do the reverse, where each List value chosen for images will be converted to text. NOTE: Pressing page refresh in the browser is required for either coversion to appear. 


## Notes
Change the ordering of custom fields displayed by dragging and dropping the square with 6 dots to the left of each field.

Field names and descriptions can be changed at anytime.  When changed, those changes are reflected throughout the system.  (The system uses generated database keys rather than the names of fields to identify them in the database, so it’s perfectly safe to change the names.)

## Showing custom fields across DBGallery pages
The next step is to place the fields on the appropriate DBGallery pages.  By default, custom fields are shown only in the Preview page's Full Data view, which is rather hidden and out of the way.  Usually these fields would, at a minimum, be added to the Preview's Info tab.  Very often they're added under the main gallery view's thumbs and in the Shared view that a client might see.   This is done fairly easily using the <a href="/datalayoutsettings" target="_blank">Data Layout Settings</a> tool.

<!-- Please see our <a href="https://docs.google.com/presentation/d/1-fM1YyNQt5tcddxngUYA_U-hSEoXKkaVklvI2fHoCSg/edit?usp=sharing" target="_blank">Custom Fields</a> slideshow tutorial for how to use them. -->

## FAQs
**Q:** Is there a limit to the number of custom fields which can be added? <br>
**A:** No.  But do keep in mind that having hundreds of custom fields can have an impact on system performance.

**Q:** When adding new custom fields, where are they displayed? <br>
**A:** By default they appear only in the Full Data tab when previewing an image.  To add them to other areas of the system, use Data Layout Settings. 

**Q:** Are custom data fields stored in the image files along with other metadata such as IPTC and EXIF information? <br>
**A:** No.  These fields are stored in the database only.  The reason for this is there is no metadata standard for custom fields.  That data could be added there but no other program or website would understand how to read it.


![Learning Grapic](/assets/undraw_Online_learning.png)

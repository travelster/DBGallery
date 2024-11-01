---
layout: default
title: Facial Recognition
permalink: /facial-recognition
parent: AI
grand_parent: DBGallery
nav_order: 20
---

# Facial Recognition

## Getting Started
Starting with facial recognition in DBGallery couldn't be easier!  Start by uploading images with faces.  Each face will first be assigned default names such as 'Unidentified Person 1' or 'Unidentified Person 63', and so on.  When there are multiple faces of the same person, there may be many images with 'Unidentified Person 63' listed.  Rename that one name to something real, like 'Johanna Jones', and all 'Unidentified Person 63' will be assigned to that name.  Then any subsequent uploads of that person will be named 'Johanna Jones'.  In the search areas of the main gallery view, that name can immediately be searched for.

That is pretty well all that is needed to use facial recognition in DBGallery. The rest of this page will cover special cases, features, along with Q&A.

**Note:** Not all DBGallery accounts have Facial Recogntion turned on.  Contact your DBGallery administrator to inquire about this, or send DBGallery support a message at support@dbgallery.  

**Step 1: Upload.**  Upon first uploading new faces, 'Unidentified Person 63' is seen in 3 photos:
<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="/assets/Unidentified Person 63 - before.png" alt="Before renaming 'Unidentified Person 63' to 'Johanna Jones'"/></p>


**Step 2: Rename.** Open one of the photos with that person in it and click that face to have the People tab automatically opened.  Then type the actual name of that person, then press Add.
<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="/assets/Unidentified Person 63 - Naming.png" alt="Renaming 'Unidentified Person 63' to 'Johanna Jones'"/></p>


**Step 3: View the updated names.** Press Close to see the result of 'Unidentified Person 63' having been renamed in all photos that face exists. **Important:** Subsequent uploads with that face in it will automatically be tagged with 'Johanna Jones'!
<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="/assets/Unidentified Person 63 - after.png" alt="After renaming 'Unidentified Person 63' to 'Johanna Jones'"/></p>

Repeat Step 1 & 2 for all the names of the 'Unidentified Person" names.  In most cases, this needs to be done only once per person.  

There may be times when the AI doesn't recognize that person in subsequent uploads, due to lighting conditions, blurry photos, or the angle of the face.  When that happens, click on the face and select that name from the existing list of names. As this is done the AI will learn to recognise the person more accurately.
<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="60%" src="/assets/Faces Dropdown List.png" alt="Faces Dropdown List"/></p>


## Viewing face names in Preview
To see the names of people when viewing a photo, roll the mouse cursor over the face to see the name:
<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="/assets/Rectangles in Preview.gif" alt="Viewing face rectangles in image preview"/></p>


## Adding the names data field to various DBGallery pages
By default, peoples names are listed only in the Full Data tab (just under the thumbnail) and the People tab in image preview. Peoples names can be added to various pages using Data Layout Setting under Tools | Data Layout Settings.  Below, the People data field is added to the info tab in the Shared view (the data which is seen by those images are shared to).  See Data Layout Settings for more on the specifics of how to place the People data field in the various pages within DBGallery.

<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="/assets/Data Settings for Facial Recognition.png" alt="Viewing face rectangles in image preview"/></p>



## Renaming a Person
Rename a person by simply selecting the new name from the names dropdown in the Person tab, or by entering a completely new name for them in the Person tab.  This will rename the person in all photos.  When entering a completely new name, press the “Add” button and it will be added to the system, with the old name deleted from the system.

## Deleting names (usually Unidentified Person or Unidentified Face)
Often there are faces that aren't relevant in a photo.  This might be due to background people irrelevant to the photo or faces in photo frames on a wall.  Select that face either by clicking on it in the photo, or finding it in the People tab of image preview.  Then click the Trash icon to remove it.  That 'Unidentified Person' tag will be removed from the list and a rectangle will no longer appear when rolling the mouse cursor of that face.  A name delete is for just that one photo.


## Q&A: 
**Q:** Does FR work for video.

**A:** No.  Not yet.  If this is important for your company, please let us know at support@dbgallery.com.  Your vote and comments would be a huge help in deciding on its priority within our dev team.

**Q:** What if two people have the same name?

**A:** Consider including the person’s first name, initial and last name.  The combination is typically unique.  Names must be unique or it will combine face names, resulting in the AI tagging both people with the same name, with search results showing both people.  If this ok for your scenario then having two people with the same name is ok.

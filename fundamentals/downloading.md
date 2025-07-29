---
layout: default
title: Downloading
permalink: /downloading
parent: Fundamentals
grand_parent: DBGallery
nav_order: 20
---

# Downloading

Here we'll cover:
- Downloading Single Files
- Downloading Multiple Files
- Downloading Image Data
- Downloading Previous Versions

## Downloading Single Files
There are two ways to download a single file.

1) The quickest way is to select a single file and press the download button.  This will download the full resolution file.  It will appear at the bottom of your browser as with other non-DBGallery downloads.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Download-Single-Gallery.jpg" alt="Download Single File - Gallery"/></p>


2) The second way is to open the image and choose the download button in the top left corner.  For common photo types, such as .jpg and .png, choose a resolution to download (as shown below).  For other file types, such as Photoshop or vector files, the original full-resolution file will download.  For Word or other document types, there will, of course, not be a resolution dropdown.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Download-Single-Preview.jpg" alt="Download Single File - Preview"/></p>

## Downloading Multiple Files
To download more than one file at a time, select any number of files at once, and press the Download button.  This is very similar to downloading a single file, except the all files will be downloaded in a single zip file.  This zip file will contain all selected files.  For common photo formats, such as .jpg and .png, the full-resolution file will be downloaded.   All other file types will have the original file downloaded.  (Selecting multiple files: Use the Shift or Ctrl/Cmd keys while clicking thumbs with the mouse.)

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Download-Multiple-Gallery.png" alt="Download Multiple Files - Gallery"/></p>

By default, when selecting multiple files, even if across multiple folders, the folder structure is not reflected in the downloaded zip file.  To have the zip file reflect DBGallery's folder structure, press the arrow next to Download and choose "Download with folders' structure".  

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Download-Multiple-PreserveStructure.png" alt="Download Multiple Files - Preserve Folder Structure"/></p>

**TIP:** You can select a number of files, then switch folders or do another search, then select more files using the Ctrl/Cmd key, adding to the total number of files selected.  Do to this, when the new set of files appear use the Shift or Ctrl/Cmd keys to select additional files.  Be careful not to select a single file during this process; if a single file is selected without one of those keys pressed, only that single file will be selected, de-selecting all the others.  While a little tricky, it can be extremely useful when required files are spread across various areas of DBGallery. 


## Downloading Image Data
Downloading data which is associated with images can sometimes be as important as the images themselves.  Whenever multiple files are downloaded, all associated data for the files is downloaded as well, in the images.csv.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Download-zip-sample.png" alt="Download Multiple Files - Zip Sample"/></p>

Images.csv would look something like the following, and will have all data associated with each file, including any custom fields.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Download-csv-sample.png" alt="Download Multiple Files - CSV Sample"/></p>

**Data without the images:** Also under the Download menu arrow is an option to "Export data-only as a CSV file".  This will download only the data from all selected files.  All data DBGallery holds for each image is downloaded as columns.  To remove unwanted columns, use a CSV editor such as Excel, and removing them after download.  

## Downloading Previous Versions
If versioning is enabled in your DBGallery, please see the Versioning section for how to download previous versions of an image.
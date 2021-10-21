---
layout: default
title: Exporting Image Data
permalink: /download-data
parent: Beyond Basics
grand_parent: DBGallery
---

# Exporting Image Data

All metadata associated with an asset is downloaded each time multiple assets are downloaded. This includes any custom fields.  Multiple files are always downloaded as a zip file, and that zip file includes an images.csv file, which contains all data for each asset.  

## Walkthough of the export process

3 steps are required.

1) Select multiple files and press Download:

![Select the files](/assets/DataExport-DownloadMultipleFiles.jpg){: .ml-8}

2) Open the zip file to find images.csv:

![Open the exported zip file](/assets/DataExport-ZipFileAndCSV.jpg){: .ml-8}

3) Open the CSV file in any spreadsheet or text editor:

![Viewing the exported CSV file](/assets/DataExport-CSVOpenedInExcel.jpg){: .ml-8}

The above three steps:

![Data Export Animation](/assets/DataExport-3Steps.gif){: .ml-8}


## Special usage note

If it is required that data for asset files is modified outside DBGallery, this CSV file may be modified manually or by 3rd party systems then re-imported into DBGallery.  See the Data Import Guide for import instructions.
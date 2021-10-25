---
layout: default
title: Exporting Data
permalink: /download-data
parent: Beyond Basics
grand_parent: DBGallery
nav_order: 11
---

# Exporting Data

All metadata associated with an asset is downloaded each time multiple assets are downloaded. This includes any custom fields.  Multiple files are always downloaded as a zip file, and that zip file includes an images.csv file, which contains all data for each asset.

## Walkthough of the export process

Three steps are required.

1) Select multiple files and press Download:

![Select the files](/assets/DataExport-DownloadMultipleFiles.jpg){: .ml-8}

2) Open the zip file to find images.csv:

![Open the exported zip file](/assets/DataExport-ZipFileAndCSV.jpg){: .ml-8}

3) Open the CSV file in any spreadsheet or text editor:

![Viewing the exported CSV file](/assets/DataExport-CSVOpenedInExcel.jpg){: .ml-8}

The above three steps:

![Data Export Animation](/assets/DataExport-3Steps.gif){: .ml-8}


## Notes

For common image file types, such as jpg, png, tiff, and Adobe Files (pdf, psd, ai, eps), metadata is also stored in the <a href="https://en.wikipedia.org/wiki/Extensible_Metadata_Platform"  target="_blank">XMP/IPTC metadata</a> area of the files themselves.

Special usage note: If it is required that data for asset files is modified outside DBGallery, this CSV file may be modified manually or by 3rd party systems then re-imported into DBGallery.  See the Data Import Guide for import instructions.
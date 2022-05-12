---
layout: default
title: Searching
permalink: /search
parent: Fundamentals
grand_parent: DBGallery
nav_order: 10
---

# Search

There are a number of search options, from easy to sophisticated binary searches. Casual users, often non-technical, who use the system infrequently, need an exceptionally simple means to find an image. That's the first scenario below. Of course there also must be sophisticated search options for advanced users or when there are hundreds of thousands of images with lots of data and a very specific image is required.

## The Basic Search
Let's start with the easiest and most often used search: a single word. Interestingly this easiest search is most often all this is required. From the Architecture collection, we search for photos in Toronto:

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Search-Basic.png" alt="Search Basics: One word search"/></p>

All data for an image is searched.  This includes common data such as keywords, subject, author, etc., but also camera, date, filename, folder name, city and more.  

Searches are for full words by default.  To search for partial words, use the * character.  E.g. If the filename is IMG_5440.JPG, find it by entering *5440.  This indicates the search is no longer for whole words only but is contains search instead.  More on this in the Binary Searches section below.


## Advanced Search Options
From there a dropdown of options can help refine a basic search.

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" width="80%" src="/assets/Search-AdvancedOptions.png" alt="Search Advanced Options"/></p>

## Binary Searches
Then there are binary operations. A + sign indicates 'must have', and a - sign indicates 'must not have'. The following searches for images that must have both Toronto and Balcony, but must not includes images with Yorkville (a trendy upscale area of Toronto):

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" width="80%" src="/assets/Search-Boolean.png" alt="Search Boolean and Binary Syntax"/></p>

**Search Syntax**

Use the * wildcard character:
<ul>
<li>*970*</li>
<li>*.png</li>
</ul>

Use double quotes for words with special characters:
- "SM-N986W"
Search this exact phrase (no quotes):
- Alps Night Skiing
Use single quotes to search any of these words (an OR search):
- 'Alps Night Skiing'
When the sort order is by Relevance, a search with or without single quotes will order the results based on images which have the most of those words. The search below will return those with all 3 words at the top, followed by those which have only 2 of those words, and so forth.
- Alps Night Skiing

For a quick look at the binary search syntax, press the i button:

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Search-Hints.png" alt="Search Hints"/></p>

**Tips**
- Searches are never case sensitive.
- All data is searched. This includes folder and file names, EXIF data, Country, Subject, custom fields, etc.

## More on our Smart Search
Sort by Relevance. Here if a search for Toronto, Balcony and Yorkville is searched for, it will return images in the order that have the most of those keywords. In this case placing those that have all 3 keywords at the top. The top image with the gold windows, is tagged with Toronto, Balcony and Yorkville. The image after that has only Toronto and Yorkville, and so forth there the bottom results have just Toronto as a tag:

<p style="margin-left: 5%;"><img style="border: 1px solid purple;" src="/assets/Search-Relevance.png" alt="Search by Relevance: Smart Search"/></p>

As touched on briefly above, use single quotes when images should contain any of the words: 'Bricks Red'. This will return images which have Bricks or Red anywhere in its data. A search for Bricks Red, without the single quotes, searches for that exact phrase. (We default to a phrase search because our clients said they preferred it that way so they didn't receive too many incorrect results when searching for Bricks Red, where any images with just Bricks would be returned.)

**See Also**
<ul>
<li>Our <a href="https://dbgallery.com/blog/introducing-a-smarter-search/" target="_blank">Smarter Search blog</a> goes into details and additional examples of the relevance/smart search.</li>
</ul>

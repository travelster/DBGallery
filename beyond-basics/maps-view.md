---
layout: default
title: Maps View
permalink: /maps-view
parent: Beyond Basics
grand_parent: DBGallery
---

# Maps View and Features
The Maps View is especially useful when images have GPS stamps included.  They'll show across maps, and perhaps even better, address data is automatically added (street, city, country). This data is then immediatly available for searching.  E.g. Add images from Iceland that have GPS timestamps and a search for Iceland will bring them up.

If image don't have GPS stamps, they can be added within DBGallery fairly easily by a Google Maps-like search for where they're taken.  This works because integrate with the Google Maps API. 

## Maps View
Any images uploaded that have GPS coordinates can be shown across a map.  Select Map View from the main menu.

![Maps View](/assets/MapsView.jpg)

## Viewing images directly from Map View
Click a marker to view the image.  To see the full image from there, click Open.  Replace the markers with thumbs by clicking the marker button in the top right corner of the map (the middle of the three buttons). 

![Maps View](/assets/Maps-Icons-and-Preview.gif)

## Map on the Main View
See where it is on a map directly from the thumbs gallery view by clicking the View Map button on the thumb (see red box below).

![Maps View Thumbs](/assets/MapsView-Thumbs.jpg){: width="65%" .ml-8}

## Setting GPS location within DBGallery
When GPS stamps don't already exist in the image, set the location when editing data.  Start typing the location as you would in Google Maps and choose from the list. Press the expand button to see the map in full screen mode to tweak the map marker location. Tweak existing locations on images that already have GPS data by dragging the marker within the small map window or pressing the expand button.

![Maps View Set Location](/assets/MapsView-SetLocation.png){: width="90%" .ml-8}

## Reverse Geocoding  
Street address is automatically added using <a href="https://en.wikipedia.org/wiki/Reverse_geocoding" target="_blank">reverse geocoding</a> anytime an image is uploaded or a new location is set in when editing data.  This info includes street name and number, city and country.

![Maps View Reverse GeoCoding](/assets/MapsView-ReverseGeocoding.png){: width="75%" .ml-8}


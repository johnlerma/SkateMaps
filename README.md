## Synopsis

This is a neighborhood map that shows you local skateboarding spots by type. In future updates, users will be able to add locations with descriptions and upload photos.

## How To

The google map includes a handy filter, so you can filter spots by skatepark, bank, handrail and stairs. When you select a location, a drawer will open up from the bottom to show you photos using the flickr API. These photos are pulled using location (.25 mile radius) and using the tags skateboarding, skateboard, skate, skateboards.

## Installation

Download the zip folder and decompress it. Start a local server on your computer. 

For mac open the Terminal, navigate to the index.html location and type:

```
python -m SimpleHTTPServer 8080
```
For windows, open the Command Line, navigate to the index.html location and type:

```
python -m http.server [8080]
```

Now open Index.html in any browser to use. 

## Technologies Used

Google Maps, Flickr, jquery, Knockout-3.2.0


## Screenshot

![screenshot](https://github.com/johnlerma/Skate-Spots/blob/master/gitimages/skatespots_mainimage.png "Screenshot")
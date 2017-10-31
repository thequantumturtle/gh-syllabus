---
week: 8
day: November 6
title: Mapping 2
tags: 
---

## Assignment Due
The deliverable is a CSV or JSON file containing places (names, coordinates, and -- optionally -- other information) of interest to you. 

Include at least 10 places, but the main concern should be some type of pedagogical or research-oriented coherence. Add and commit the file in a new folder in your class-related git repository and push to GitHub. 

### How to get Pleiades coordinates

We discussed the use of Ryan Baumann's *[Pleiades Geocollider](https://pleiades.stoa.org/news/blog/introducing-geocollider)* to collate a list of places against *Pleiades* yesterday in class, but we didn't demonstrate how to collect coordinates from the results (after you've chosen the best matches). Patrick has provided [some example Python code](https://gist.github.com/diyclassics/7374db1560ca1427a82ae81f927a502b) for retrieving a version (in [the GeoJSON format](https://tools.ietf.org/html/rfc7946)) of the *Pleiades* data for an individual place and parsing it for coordinates. **Note line 27:** the assumed input to the "get_pleiades_json()" function is a numeric *Pleiades* ID, i.e., the last bit of the *Pleiades* URI (not the whole URI). So if you're working with URIs as returned by *Pleiades Geocollider,* you'll want to use something like ```pleiades_uri.split('/')[-1]``` to get the ID to pass to Patrick's function. 

Alternatively, Ryan Horne's *[Antiquity À-la-carte](http://awmc.unc.edu/wordpress/alacarte/) application* from the Ancient World Mapping Center can be used to build a collection of places (drawn from *Pleiades* data) that can then be exported to CSV or JSON format. **NB: *AAlc* works best with the Firefox web browser.**

### Optional but recommended additional files for assignment

You may care to add, commit, and push some other files as well.

 - If you encounter difficulties or concerns during the compilation process, make appropriate notes in a text or markdown file.
 - If you used *Pleiades Geocollider* or *Antiquity À-la-carte* include any files you uploaded to or exported from the application. 

### Not an assignment!: About *OpenRefine* and *Pleiades Geocollider*

For any who were intrigued by my dismissive discussion of *OpenRefine* yesterday, here are some resources:

 - Blog post: "[Using *OpenRefine* With *Pleiades*](http://horothesia.blogspot.com/2017/10/using-openrefine-with-pleiades.html)" in *Horothesia,* October 13, 2017.
 - Video: "[An Example Workflow for Geography in an Ancient Studies Project: The Vicarello Cups](https://youtu.be/KMZZSVhQwXo)" via *YouTube.com,* October 18, 2017.

## Before Class

### Download/Install/Etc.
- Register for an account with [Carto](https://carto.com/). You can create a new account (using your email or password), or you can register using your Google or GitHub account credentials. In class, we will make maps in Carto, using the data you prepared and brought to class. We'll also experiment with [Google Fusion Tables](https://en.wikipedia.org/wiki/Google_Fusion_Tables) and with [geojson.io](http://geojson.io/#map=2/20.0/0.0), but you don't need to do any advance preparation for those aspects.

## For Class

### Reading
- Foote, K.E. and D.J. Huebner. 1995. "Error, Accuracy, and Precision," in *The Geographer’s Craft*. [Link](http://www.colorado.edu/geography/gcraft/notes/error/error_f.html)
- Gillies, S. 2010. "What's an Un-GIS?" *Pleiades*: Documents. [Link](https://pleiades.stoa.org/docs/papers-and-presentations/whats-an-un-gis)

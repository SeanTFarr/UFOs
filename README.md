<img src=static\images\banner.png>

# UFO sightings: Are we alone?

## Overview of Project

Dana, a data journalist, was given an exciting opportunity to do a report about her hometown, which is well known for UFO sightings. While working on this report, she came across a dataset of UFO encounters. She asked for my help to display UFO the data in a table on a webpage. She not only wanted to see the data, but also wanted the user to be able to filter the data to drill down to specific occurences. 

#### Resources used:
- JavaScript-data file and app.js file to build the table and run functions
- HTML to display the webpage
- Bootstrap to organize the webpage
- CSS to customize the webpage(dark form element)


## Results
The final product is a webpage that not only shows a table of known UFO sightings,
 but also provides 5 filters to aid in finding specific sightings.
 <img src=static\images\initial.png>
 The user has 5 options to filter through the data: Date, City, State, Country, and shape.
 <img src=static\images\filters.png>

 An example of use: by typing in a state and pressing enter, only the sightings within that state remain on the table:
 <img src=static\images\state.png>

 Another search option is by shape, which will display only the shape they enter:
 <img src=static\images\shape.png>


## Summary
Whereas the webpage hit the initial request, there is one drawback that stands out, the invisibility of what can be entered. Without a running list of what can be entered, the user is left trying to hunt for what options are available. A dropdown list that would display options from the field would be ideal.

Along with the need for a list of options in the filters, there are two additional recommendations for further development:
1. Implementing a larger dataset that gives all known sightings(as far back as possible) and that can be regularly updated.This will give a larger representation of the volume of sightings.
2. Modifying the "date" filter to accomodate a range of dates (i.e. a "From Date" and a "To Date"). This will allow for grouping of data in relation to time periods, not just a singular date.
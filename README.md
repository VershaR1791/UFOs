# UFOs
## Overview of Project: 

Dana is a data journalist who has decided to write about the frequent UFO sightings in her hometown McMinnville, Oregon. She uses Javascript to sift through huge amount of data and tabulate into it's location and the comments around the UFO sighting. The article alongwith the data will be shared on HTML page on which the original data can be filtered for verifying the proof.

## Results: 

The filter function on the HTML page is easy to use. The user can filter using either (as seen in the below snapshot) -
- Date of UFO sighting, 
- City, State, Country of UFO sighting and/or
- Shape of the UFO sighting

![image](https://user-images.githubusercontent.com/84694664/132962866-38398eaf-4045-4ca7-b5ea-46a178b49ce2.png)

Here is an example of filter applied to Date (**"1/1/2010"**), City (**"CA"**) and Shape (**"triangle"**) and the result obtained -
![image](https://user-images.githubusercontent.com/84694664/132962964-d6b641d6-18c2-4a62-af45-541168967d5a.png)

## Summary: 

- The HTML provides an excellent way to filter through the data but there is no trigger of an error if a wrong filter was applied.
- The country filter seems redundant since the data is only for sightings in US.
- The filter right now is Case sensitive, the user should be able to filter without decapitalizing for better user experience.
- For the filter we could provide a drop down menu for atleast the states, since that is be fixed.
- Further, the user should have an option to filter multiple states or cities.

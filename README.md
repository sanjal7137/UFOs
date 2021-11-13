# UFOs

## Overview of the Project

### Background

We created a table to organize UFO data that is stored as a JavaScript array. This table has the ability to filter data based on certain criteria and was created using JavaScript as the primary coding language. While the webpage and dynamic table are working as intended, we wanted to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, users would be able to add table filters for the city, state, country, and shape.

### Deliverables
* Deliverable 1: Filter UFO sightings on multiple criteria
* Deliverable 2: Written Analysis (README.md)

### Software / Technology Used
JavaScript, HTML, Visual Studio

## Results

The focus of the project is to build a dynamic webpage that allows users to input filter criteria such as date, city, state, country and/or shape and apply it on UFO sightings information displayed as a table. Subsequently, the table will be updated to display sightings that match the criteria. The following image shows the final web page, before applying any filters:

![image](https://github.com/amberwnaushahi/UFOs/blob/main/resources/webpage.png)

### Instructions for UFO Sightings filtering:

1- User will manually input parameters in the filter search table to filter the UFO sightings data table:

![image](https://github.com/amberwnaushahi/UFOs/blob/main/resources/filter%20search%20table.png)

2- To clear filters and refresh the webpage to view all UFO data:

  * filters can be manually cleared
  * the webpage can be refreshed by clicking on the "UFO Sightings" in the navigation bar on the top left corner of the page
 
![image](https://github.com/amberwnaushahi/UFOs/blob/main/resources/Navigation%20Bar%20-%20Top.png)

## Summary 

One main drawback of the webpage is that whilst the web page itself is dynamic, whereby the user can engage with the web page by applying filters and view data based on their defined criteria, the data is static as it resides in the data.js file. This means that the webpage is not updated with any new sightings beyond whatever information is held in data.js file. 

Several improvements can be made to the existing web page to enhance the user experience:
* Enable bootstrap to remove case sensitivity of filter criteria
* Have drop-down list for filter criteria
* Allow users to select a date range, rather than one specific date only
* Add a clear filter button to clear all filter criteria 
* Link the UFO Sightings info to a source where data is updated regularly so as to include all latest information and keep the webpage current.  

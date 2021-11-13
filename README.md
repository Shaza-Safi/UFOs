# UFOs

## Project Overview:

### Background:
Dana is a data analyst who is writing about her home town, McMinnville, Oregon, who's famous for UFO sightings and UFO enthusiasts. In this project Dana used a sample dataset of UFO sightings in the US. Her plan is to first display the javasript data as a table and add filters to the table which will be displayed in a tidy html page for public to access. The html page will present her article and the table to support her findings and easy to use filters to fine tune the results. We have to help Dana make her idea come to life!

## Challenge Deliverables:
Dana’s webpage and dynamic table are working as intended, but she’d like to add more filters to be able to dive in deeper inter her analysis by adding a filter to the City, State, Country and Shape that the sightings were encountered. 

In deliverable 1 of the challenge we have added filters to the webpage to show UFO sightings information on multiple criteria.

In deliverable 2 of the challenge we have to write a report on the UFO analysis (README.md)

## Results:
This project focuses on building a dynamic webpage that allows the user to input filter criteria. The inputs allow the user to filter on a specific date, city, state, country and shape. The user is able to filter using a single or multiple filters.

### User Instructions on how to use the search criteria filters on the UFO Sightings website:

1.	Create a custom HTML web page

2.	Using the UFO dataset provided in the form of an array of JavaScript objects, write code that appends a table to the web page and then adds new rows of data for each UFO sighting
3.	Make sure there are columns for date/time, city, state, country, shape, and comment at the very least


4.	Use a date form in the HTML document and write JavaScript code that will listen for events and search through the date/time column to find rows that match user input
5.	Using multiple input tags and/or select dropdowns, write JavaScript code so the user can to set multiple filters and search for UFO sightings using the following criteria based on the table columns:
  a.	date/time
  b.	city
  c.	state
  d.	country
  e.	shape
6.	The user can then manually input in the filter parameters which will filter the table and show only the information related to that selection.
7.	Clearing filter selections can be done by either one of the following steps:
  a.  Clear the filters manually and pressing enter
  b.  click on the "UFO Sightings" image found in the top left corner of the webpage.

Below is a visual of the final webpage

 
## Summary:

The website we have built for Dana is dynamic and rigid showing the Dana’s article on UFOs and a table demonstrating the all information related to the UFO sightings, not to mention filters allow the user to filter the data based on multiple criteria. Having said that, the data itself is static and resides only on your local machine (data.js) which leaves no room for updating data nor pull older sightings. The webpage is not updated with new UFO sightings beyond what the data.js file holds. 
There are many opportunities of improvement on this analysis that can better tackle such limitations. Below are a few opportunities for improvement.

### Improvement Opportunities: 

The data used in this analysis is a locale file (data.js) on the machine which can be pulled remotely using the following methods:
1.	Connect to UFO sightseeing websites to pull live records via API. 
2.	Conduct web scraping exercise to bring more updated and real time data.

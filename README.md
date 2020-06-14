# UFOs
## Review
- Several UFO events are saved in the data.js file and each event is an object.  In this project we are filtering the data using the values of the parameters that can be used to filter the data.  In this challenge we are using the following parameters to filter: date, city, state, country or shape. The idea is to input any of those parameters and get the results filtered in a table.

## Project
- We created a app.js file to save our code in javaScript.
- We include the five total filters in the table:
  - Date
  - City
  - State
  - Country
  - Shape
- We created a function that saves the element, value, and the id of the filter that was changed.  We added the trim() method to remove blank spaces in case are added by typo errors, and also added the toLowerCase method to force all the input values to be in lowercase since the data is saved all in lowercase letters, then we will able to filter the data if someone input the values for example for state in capital letters.
- We created an if-else statement to add filter data from input, or clear the filter if no input data exists.
- Additionally, we created a function named filterTable(); that will perform the following actions:
  - Set the filtered data to the table.
  - Loop through all of the filters and keep any data that matches the filter values.
  - Rebuild the table by calling the buildTable(); function created earlier.
- We created a function clearFilters() and add a bottom to click to clear the inputs to the Filter Search.
- Finally, using d3.selectAll(), an event was attached to the listener to pick up changes that are made to each filter.
- The index.html was build to show the FilterSearch with the five total filters, and the result table after the filter was applied. 

## HTML Image:
![The-Truth-Is-Out-There.PNG]https://github.com/DahianaMC/UFOs/blob/master/The-Truth-Is-Out-There.PNG



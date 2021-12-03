# UFO Analysis

## Project Overview - UFO Analysis
THe project allows more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, we'll add table filters for the city, state, country, and shape.

## Resources
-  Data Files: style.css, app.js, data.js, index.html

-  Software/Languages:  Javascript, CSS, D3.JS, HTML



# Challenge Summary

## UFO Analysis - Results

The webpage uses the filters to sort the data through user input.  By default, all the UFO data is sorted by date within the results table.
![Screen Shot 2021-09-05 at 1 46 45 PM](https://user-images.githubusercontent.com/691355/132141002-90251a1b-aedb-470a-bce4-d84042a7b97c.png)

By default there is placeholder text in each search box to help the user select and filter through the data.
![Screen Shot 2021-09-05 at 1 51 17 PM](https://user-images.githubusercontent.com/691355/132141102-da832e1e-55b8-443f-bf5b-e2352ec8ef1b.png)


Using the filter inputs on the left the data can be filtered through combinations of date, city, state, country and shape.  The user has the ability to choose 1 or more of the filters to sort the data.

Example 1 - One Filter Selected 
![Screen Shot 2021-09-05 at 1 53 58 PM](https://user-images.githubusercontent.com/691355/132141157-4b13777f-f687-4a7d-9b84-139825bf4956.png)


Example 2 - Multiple Filters Selected
![Screen Shot 2021-09-05 at 1 52 45 PM](https://user-images.githubusercontent.com/691355/132141139-92620e4e-ce2d-4f9a-8827-1ad9983d9687.png)

Example 3 - All Filters Selected
![Screen Shot 2021-09-05 at 1 54 54 PM](https://user-images.githubusercontent.com/691355/132141179-9c27b347-08c5-442d-998d-81717a23fa22.png)


## UFO Analysis - Summary

One drawback to the current design is a lack of a key that has the search criteria.  Adding a search key would help the user know the specifics in each parameter of the filters.  By default for a search of "shape" we have listed "circle" to help with our search.  However, looking through the data we can see that other shapes are triangle, light, unknown, formation etc.  A key header above the results table would help users find the information they're looking for faster.

For the future, adding a script that has automated calls for data on future sightings would keep the table live and up to date.  

Additionaly in regards to building a key to our data table, adding constraints on the dates our data starts and ends would be helpful to the user.  Future builds would benefit from having the user able to search within a time frame.  An example would be to search all sightings between 1/1/2010 and 1/3/2010 with the user specified filters.  


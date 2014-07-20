Swift-YelpSearch
================

### Overview
Build a Yelp search app.

### Requirements

* Search results page
  * Table rows should be dynamic height according to the content height
  * Custom cells should have the proper Auto Layout constraints
  * Search bar should be in the navigation bar (doesn't have to expand to show location like the real Yelp app does).
  * Optional: infinite scroll for restaurant results
  * Optional: Implement map view of restaurant results
* Filter page. Unfortunately, not all the filters are supported in the Yelp API.
  * The filters you should actually have are: category, sort (best match, distance, highest rated), radius (meters), deals (on/off).
  * The filters table should be organized into sections as in the mock.
  * You can use the default UISwitch for on/off states. Optional: implement a custom switch
  * Radius filter should expand as in the real Yelp app
  * Categories should show a subset of the full list with a "See All" row to expand. Category list is here: http://www.yelp.com/developers/documentation/category_list
  * Clicking on the "Search" button should dismiss the filters page and trigger the search w/ the new filter settings.
* Optional: Implement the restaurant detail page.

### Mockups

![search results](http://i.imgur.com/4m5iyt5l.png)

![filters](http://i.imgur.com/rczfg7kl.png)

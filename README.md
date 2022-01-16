# UFOs
Create a website decicated to UFO enthusiasts having data about UFO sightings for January 2010, all across the US which can be filtered based on date, city, state, country, shape. 

## Overview of the UFOs project
Dana a data journalist  is asked to write about her hometown McMinnville, Oregon. McMinnville is famous for its UFO sightings and also has an annual gathering of UFO enthusiasts. She wants to build a website with latest newsbites from the UFOlogists and a table of data to support the sightings. We help Dana to convert the data to html table which can be filtered for date, city, state, country, shape using javascript alongwith css and bootstrap 4 to present the data beautifully. 

## Resources
* Bootstrap 4, Javascript ES6, VSCode 1.63.2, CSS, HTML, Chrome Browser.

## Results
1. We have build a webpage on UFO sightings and deployed it on github pages https://sucharita1.github.io/.
![github_pages](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/github_pages.png?raw=true)

2. The new code with additonal city, state, country, shape filters which adapts to change of input can be viewed at [index.html](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/index.html) and [app.js](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/js/app.js)

* Please refer to the image below where you can see that a portion of the table containing the UFO listings is marked in green and the portion marked in red are the filter elements, each filter elements namely Date, City, State, Country, Shape has been marked in blue and placeholders showing sample values are shown in orange. Placeholder for date is '1/10/2010', placehoder for city is 'el cajon', plaeholder for state is 'ca', placeholder for country is 'us', placeholder for shape is 'light'.
![filter_components](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/filter_components.png?raw=true)

* Please refer to the image below, to filter on a single criterion like date, we enter a date like 1/4/2010 you can see that now the table shows only 8 out of 111 sightings and you can verify that the date for all the citings is 1/4/2010. Similarly we can filter on each of the date, city, state, country or shape filter individually or use them in combination.
![date_filter](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/date_filter.png?raw=true)

* Please refer to the image below to see all the filter criteria in action including date as 1/4/2010, city as whittier, state as ca, country as us, shape as light and see only 1 out of 111 sightings satisfying all the criteria.
![all_filters](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/all_filters.png?raw=true)

## Summary
#### Some drawbacks of the original website with only filters.
* The original website design did not include a clear filter button. So everytime a person enters some filter he has to reload the page himself/herself to clear the filters. This may not be something that a person remembers to do or some people may not know how to do. 
![only_filters](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/only_filters.png?raw=true)

* The original html code did not include class = "form-control" so the filters size did not adapt to the webpage size change. If the screen size decreases the input fields still say the same.
![without_form_conrol](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/without_form_control.png?raw=true)


#### Recommendations
1. Clear Filter button, when clicked by the user will reset the page again to try out new filters.
* To implement the Clear Filter Button in html:
![clear_filter_html](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/clear_filter_html.png?raw=true)

* To implement the Clear Filter logic in app.js:
![clear_filter_js](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/clear_filter_js.png?raw=true)

* The website before clicking the Clear filter button:
![before_clear](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/before_clear.png?raw=true)

* The website after clicking the Clear filter button:
![after_clear](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/after_clear.png?raw=true)



2. Number of sightings filtered against the total sightings
* To implement the number of sightings in html:
![no_of_sighting_html](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/no_of_sightings_html.png?raw=true)

* To implement the number of sightings in js:
![no_of_sighting_js](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/no_of_sightings_js.png?raw=true)

* The website before number of sightings information:
![only_filters](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/only_filters.png?raw=true)

* The website after number of sightings information:
![no_of_sighting](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/no_of_sightings.png?raw=true)

3. For the filters which are of the type input,  class = "form-control" is added to make the input boxes responsive to the change in the screen size. Here, the screen size has changed but the filter inoyts have also changed their size which was not the case before.
![input_class_form_control](https://github.com/sucharita1/UFOs/blob/17673b9e59ed3fc2ecd83b459d6ddc6aac63fb46/static/images/input_class_form_control.png?raw=true)










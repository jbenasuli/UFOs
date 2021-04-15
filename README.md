# UFOs

## Overview of Project

The purpose of this project is provide users the ability to search for and analyze the data of UFO sightings.

The array of UFO sightings data has been tabulated and added to an HTML webpage allowing users to easily view information regarding each UFO sighting. The table is dynamically constructed with filters for five of the fields giving users the ability to easily drill down their search on up to five criteria.

## Results

Upon loading the webpage, users will see all the UFO sightings data in the table. To refine the results displayed in the table, users can input values for one or more of the filter fields located to the left of the table. Below are screenshots of the webpage with examples of no filter, one filter and all five filters being used in a search.

It is important to note that a field containing light gray text does not indicate a search entry. The light gray values are placeholder values meant to serve as example inputs for users. Additionally, in order for a search input to take effect, users need to press the enter key or click outside the input box.

- No filters: all data is displayed in the table.
![no-filters-image](webpage-screenshots/ufos-all-filters.png)

- Filtered by date: only UFO sightings on 1/7/2010 are displayed in the table. Note how the text in the date field is black compared to light gray in all the other fields.
![only-date-image](webpage-screenshots/ufos-only-date-filter.png)

- Filtered by all five criteria: only UFOs sighted on 1/1/2010 in el cajon, ca, us with a triangle shape are displayed in the table.
![only-date-image](webpage-screenshots/ufos-all-filters.png)

## Summary

There is one major drawback to how the filter search capability is currently constructed. This drawback is the lack of any sort of field validation in the filter search. The lack of validation makes it very easy for users to create searches, which yield no results. This contributes to an overall poor user experience, as it forces users to either scan the entire table for valid inputs or hope any given input will not generate a blank table.

In order to address this shortcoming, the filter search input fields should be changed to dropdown menus, which contain valid values from the table. This change greatly improves user experience. Not only does it prevent users from generating empty tables, users also gain the ability to view all possible valid inputs for a given field.

To further bolster the capability of dropdown search fields, code could be added to display the number of results a given selection would display in the table when selected. This would allow users to be more judicious in selecting filters, as they would know in advance if a potential search may generate results which are either too broad or narrow.

Another enhancement to consider for further development is adding the ability to sort the table. Allowing users to sort the table by clicking on a given header improves user experience by giving users an even greater ability to view the data in a manner that best suits their needs.

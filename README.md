# Tech Jobs MVC

This project is an evolution of [Tech Jobs Console](https://github.com/theodoremoreland/TechJobsConsole) and [Tech Jobs OOP](https://github.com/theodoremoreland/TechJobsOOP), wherein each application
allows users to filter, search, and/or create job listings. This project evolves upon the design
and implementation of the aforementioned projects by transforming them into a web application
that uses the Model View Controller design pattern (hence "MVC").

*This project was a homework assignment for LaunchCode's Lc101 2021*

### Technologies
* Java
* Spring Boot
* Thymeleaf

# Images

## Home screen
<img src="presentation/1.PNG" width="900">

## After clicking "List" (in navbar or link in center of page).
<img src="presentation/2.PNG" width="900">

## After selecting "View all" from List screen. Displays every job listing.

Users can click on any of the blue values to display a list that uses the selected value as a filter.

<img src="presentation/3.PNG" width="900">

## After clicking on the location "Saint Louis".
<img src="presentation/4.PNG" width="900">

## After clicking on the core competency "Statistical Analysis".
<img src="presentation/5.PNG" width="900">

## After selecting the "Search" button from navbar (has same effect as selecting from home screen).

By default, the application will select the "All" radio button for you. If you choose something else then submit,
the app will remember your selection when rendering the updated screen.
<img src="presentation/6.PNG" width="900">

## Upon entering "data" while having "All" selected.

The application will look for the word data (while ignoring case) within each field of a job listing.
If it finds the word inside one of the fields, it will return that listing.

<img src="presentation/7.PNG" width="900">

## Prior to searching for the word "data" in the core competency / skills category.
<img src="presentation/8.PNG" width="900">

## After searching for the word "data" in the core competency / skills category.

Will return all listings with the word "data" in the core competency filed.

<img src="presentation/9.PNG" width="900">

## After searching for "new york" in the location category.
<img src="presentation/10.PNG" width="900">
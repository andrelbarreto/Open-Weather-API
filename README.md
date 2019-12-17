This is a Git Hub repository for the Northwestern University Coding Bootcamp Homework weather dashboard forecast 5 days.

Purpose
This weather webpage can be used for searching current weather and forecast conditions of U.S. cities for the following 5 days based on user input of city.

Usage
The user may enter the name of the city and click search, that will trigger AJAX calls that return specific values, like UV Index, temperature and humidity of city. The forecast will display the next 5 days beyond the current date with similar details.

User will be able to view cities searched before even if the browser is closed and reopened, as js script adds the searches to local storage and saves them. Last searched city will display at startup, otherwise it will reset to showing Miami weather. If nothing has been previously searched, Miami will also show as default.

In order to delete local storage and the list of previous cities presented in the webpage, user may click the button CLEAR, which will reset it and reload page.

The application will run in the browser and can be used for planning accordingly to weather, be it in your city or for a trip to another US location.

Setup
With GitHub account, clone or download repository using link. Planner runs in the browser and is updated dynamically with jQuery. Index file calls the following frameworks, libraries and APIs: Bootstrap 4.3.1 Font Awesome v5.8.1 jQuery 3.4.1 Moment JS 2.24.0 Open Weather Map: https://openweathermap.org/api - called using AJAX. Local style.css and script.js are filed on assets. Images used for webpage are under that directory's other folder, images.

License
GNU GENERAL PUBLIC LICENSE
Version 3, 29 June 2007
Copyright (C) 2007 Free Software Foundation, Inc. https://fsf.org/ Everyone is permitted to copy and distribute verbatim copies of this license document, but changing it is not allowed.

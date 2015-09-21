Weather App
===========

Introduction
------------

This task is about creating a small client-side application that displays weather data for several cities.


UI Requirements
---------------

The user interface should consist of two parts: 

- A horizontal list of tiles consisting of 
    - the name of the given city
    - an image related to the current weather situation (rain cloud, shining sun etc)
    - the weather data (temperature, situation, forecast)
    - a 'remove' button visible on hover to remove the tile from the list

- The tile creation form constisting of
    - An input field that takes a city name for a new tile
    - A select control to specify the refresh interval for a new tile
    - A button to create a new tile and add it to the list of tiles

All tiles need to refresh independently in their given intervals.  
The tile list should always use the maximum width possible to fit in all tiles, and all tiles should have the same width.  
If a tile is added or removed, the rest should automatically resize accordingly.  
You can set an arbitrary limit for how many tiles can be displayed at the same time, depending on your layout.

The weather data could be taken from http://openweathermap.org/current, but you can choose a different service if you prefer.

Other than the previous requirements, you are free to choose how to implement the UI. The attached wireframes are just a guideline.  
Keep it simple though. No need to build another weather.com.


Technology Requirements
-----------------------

You are free to choose the technologies and libraries you'd like, except for the following constraints:

- Do not use AngularJS
- Try to use [browserify](http://browserify.org/) to build your final client-side app bundle. This implies that all code should be written in the commonJS module format, making use of `npm` for dependency management

Please include a README.md file explaining the setup process and how to use your application.  
If we cannot easily run your submission, it will be rejected.


Evaluation Criteria
-------------------

The quality of your submission will be graded by code quality and clarity, elegance of the implementation, and functionality.
Bonus points will be given for beautiful design, but first and foremost this is a coding challenge.

We do not grade you on how long the task took you to complete, since learning new things is always part of the development process, and so is making mistakes and fixing them later.


Code Ownership
--------------

The submission is and always will stay yours.  
Not only are you free to publish it as open source, we actively encourage you to do so as part of your portfolio.  
Deliveryhero Holding GmbH will hold no exclusive rights to your submission.
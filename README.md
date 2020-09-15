# 01Homework-CodeRefactor
This is my first completed homework task for the UoB's Coding Bootcamp, refactoring existing code to make a website more accessible.

## About the project
I have been provided with an existing html and css document which I need to refactor in order to make it accessible for those with disabilities using assisitive technologies to view websites. The page provided is a single, static homepage for a digital marketing agency *(see screenshot below)*.

![alt text](https://github.com/HannahSones/01Homework-CodeRefactor/blob/master/Horiseon%20webpage%20complete.png)

### Built using
* HTML
* CSS

-------

## Changes made
Here is a list of the changes I made to the code to make it more accessible inline with the acceptance criteria listed:
* Ensured I used semantic html elements so that it is easier for both people and machines to read and understand the content. This included swapping out the existing div tags for more descriptive options such as header, footer, nav and section
* Added comments into the HTML to separate sections to ensure an easy to read and logical structure
* Added image alt attributes so that:
   * screen readers can understand what the image depicts
   * alt tags appear when the image fails to load so the user still has context
   * better descriptions are provided for search engines to improve ranking in SERP's
* Updated the website title to be more descriptive
* Checked the heading attributes fall in sequential order. All but the footer did which contained a h2 element. I updated this to be h4 but kept the sizing using stylign in the css

* Added comments into the css file to clearly separate the styling for each section
* Consolidated the CSS to make it easier to read and edit

-----

## Link to deployed application

https://hannahsones.github.io/01Homework-CodeRefactor/

-------------
© Hannah Sones. All rights reserved.

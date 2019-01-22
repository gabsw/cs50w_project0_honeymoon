# THE HONEYMOON PLANNER

The goal of this project is to create a group of webpages that simulate a honeymoon planning website.

## Design
The implementation has followed the contents taught in the [**CS50W course**](https://courses.edx.org/courses/course-v1:HarvardX+CS50W+Web/course/), through lessons 0 and 1. My main objective was to get acquainted with the fundamental tools and user interface techniques for web design.

The structure of the fronted consists of following HTML files:

* Index: contains the traditional home page.
* Adventure: contains information about potential trips focused on adventure.
* Culture: contains information about potential trips focused on culture.
* Relaxation: contains information about potential trips focused on relaxation.
* Resources: contains links to different online resources that are important tools for traveling planning.

The use of a navigation bar will allow all the pages to be intuitively connected to each other at all times.

The styling of the HTML files was accomplished through 4 different CSS files:

* General (````general.css````): applied to all HTML files.  

* Trips (````trips.css````): applied to ````adventure.html````, ````culture.html```` and ````relaxation.html````.

* Index (````index.css````): exclusively applied to ````index.html````.

* Resources (````resources.css````): exclusively applied to ````resources.html````.

````trips.css```` and ````resources.css```` were the result of the compilation of the ````.scss```` files of the same name, showcasing the SCSS properties that they feature. The original files can be checked in the ````Compilation\scss```` folder.

## Key Features

* Navigation Bar
* Responsive Design
* Tables
* Bootstrap's Grid Model
* Media queries
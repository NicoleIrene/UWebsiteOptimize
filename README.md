### Website Performance Optimization portfolio project

The object of this assignment was to remove all jank from the project by optimizing the page so that a page speed of 90+ is achieved on [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/).

## Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html

* Clone the github repo from Udacity [here](https://github.com/udacity/frontend-nanodegree-mobile-portfolio).

* Download the necessary tools to get started and visit the [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) page to measure your initial score.

* Follow the instructions given for optimization by compressing images, enabling render blocking CSS and JS and minifying and inlining necessary code.   


#### Part 2: Optimize Frames per Second in pizza.html

To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. You will find instructive comments in main.js. 

* document.querySelector changed to faster web API getElementById or getElementByClassName

* Moved array length inside variable and changed pizzaDiv to running outside loop for efficiency

* Reduced the number of background pizzas needed to fill the browser window 


# Work-Day-Scheduler

A simple calendar application that allows a user to save events for each hour of the day. 

## Description

Using Javascript and JQuery and the skills from class, I used arrays, If functions and loops, and the Moment.js APIs to create a daily workday scheduler. The first step was to learn moment.js functions in order to both generate the current day and output it in the header, and to generate the current hour. My second step was to analyse the CSS provided code to determine what classes were required to change the colour scheme based on the time during the day. Using JQuery I created a function that added the class to the row based on whether or not the corresponding time was in the past/ present or future, by comparing it to the current hour. Finally, I assigned a variable to an array that collected all the information typed into a text field when the corresponding save button was clickes. This array then pushed the data to the local storage. Whenever the page is opened, I created a function that would check for any existing local storage, and transfer it back to the array and into the corresponding text boxes, ensuring that all saved data would remain on screen.


## Deployment 

The deployed website can be found here: https://cmahoney12.github.io/Work-Day-Scheduler/  
The repository can be found: https://github.com/CMahoney12/Work-Day-Scheduler


## Authors

Chelsie Mahoney  
chelsiesindar@gmail.com  



## Acknowledgments

* Univeristy of Utah coding bootcamp, Jonathan Bejarano
* w3schools (https://www.w3schools.com/)  
* github docs (https://docs.github.com/en)  
* getbootstrap.com (https://getbootstrap.com/)  
* jquery tester (https://codepen.io/akerr95/pen/ZGyZmv)  
* js hint (https://jshint.com/)  
* color palette (https://coolors.co/palettes/popular)  
* readme template (https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
* redbull (gas station/humor)
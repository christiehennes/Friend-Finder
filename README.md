# Friend Finder

[Deployed Project Link](https://friend-finder-ch.herokuapp.com/)

## Instructions
 
 * There are a couple friends pre-loaded into the app
 * Fill out your information and based on your answers, you will be paired with the best match 
 * You can view the raw JSON friend objects using the link on the homepage 


 ## Project Design

 * There are a number of route files as well as object files that are used in our main survey.html and server.js files 
 * There are two different data routes: get and post to get all friends and create a new friend 
 * The app will grab all the data from the form, perform validation to make sure fields are not empty and it's a good photo url, then process the entry
 * All friends are pulled and compared against the most recent entry. The absolute value of the difference in friend scores determines the overall score. 
 * From there, the friend with the lowest score will be the most compatible friend and will be displayed in a modal

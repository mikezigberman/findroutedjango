## Route 
Search site by given parameters.  
## Assignment: 
Search for a route to move from one point to another. The task is divided into 3 parts - settlements, trains, routes. 
## Settlements. 
Implement adding, editing, deleting a settlement, and a page view of all available settlements. The settlement only has a name 
## Trains. 
Add, edit, delete trains and also page-by-page view of all available trains. The train has a unique code (name), start of the route, end of the route and travel time in units. There can be multiple trains from one point to another, but they must have different journey times. 
## Routes. 
The user chooses the start and end point of the route, and specifies the maximum travel time. You can also add as many via cities as you like, and have the possibility to choose the routes that suit your requirements. Routes suitable for the conditions are loaded. Each route must have a button next to it, allowing the user to save the route and give it a name. When searching for routes, pay attention to the direction in which the train is travelling. 
## Output.
The display of routes is sorted by shortest travel time. That is, the route with the shortest travel time is displayed first. The description of the route must show where the route is leading from and to, the journey time, and a list of all trains on the route with train numbers, where to and the journey time.   If no route is found, output message - "There is no route that matches search conditions" If set travel time is less than min time, then the message "Travel time is longer than you selected. Change the time. 
## Saved routes. 
There needs to be a separate page with a route view. The route can only be saved, viewed and deleted. A saved route cannot be edited. 
## Tests. 
Must cover 40% of the code. 
## Site access. 
Only registered users should have access to add/edit Trains/Cities as well as delete any entries.

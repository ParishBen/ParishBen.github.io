---
layout: post
title:      "Sinatra Project - 'Plant Diary Digest'"
date:       2020-08-22 13:54:54 -0400
permalink:  sinatra_project_-_plant_diary_digest
---

   This project was certainly full of many twists, turns, & 404's but hey the controllers were sent back to the right path in the end.  This project tasks me with setting up a MVC framework using ActiveRecord relations and Sqlite3 database persisting the data of the web application. The project should hold a has_many & belongs_to Model relationship, follow RESTful routes, & a user having full CRUD for only their objects. 
   To put this into action I came up with the idea for a web application to hold a user's houseplants. This put the user having many plants "to life". Then I extended this further so that plants can have many logs of how they are doing and when they were watered.  This brought into the picture a user having many logs through plants relationship.  Lastly, I thought for UI sake there should be a home page where the user can see how other users' plants are doing, what they're doing for their plants, & a tips section. This 'Home Feed' page would allow a user to click on the user that posted that log or tip & see that user's account page.  Four models, five controllers, and twenty-five views later I had the relationships all working synchronously! That was a huge moment of pride there. I found the helpers methods determining whether a user was logged in and whether a logged in user was the current user of a view was IMMENSELY helpful (a nod to its very telling name).  I found myself plugging those helpers into almost all the requests to provide security of what data was presented to the page.
		I am certainly happy with the "finished project", however I know there are many avenues to further build onto this and am eager to continue learning those future tools that could make this a much more dynamic application. 


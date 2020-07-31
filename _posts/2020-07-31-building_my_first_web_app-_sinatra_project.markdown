---
layout: post
title:      "Building my first web app- Sinatra project"
date:       2020-07-31 15:16:00 +0000
permalink:  building_my_first_web_app-_sinatra_project
---

The Sinatra section and project is an exciting part of the curriculum because it's when you really start putting together Ruby, HTML, CSS, Active Record, etc. to see yourself building out actual web pages and web applications. When you are actually seeing the code you write come to life and getting to play with it and it's functionality on the local server in your browser, it really brings things full circle and gives one the feeling of "I'm actually learning to build web apps!". My project or web app is called "The Concert Portfolio App". A user will be able to create an account to keep a portfolio of the concerts/live events they have attended where they can log and refer to the info of these events! I will be using this as an example through this blog post.


Using Sinatra to build a web app follows certain conventions which are pretty straight forward guidelines. Starting off is utilizing Active Record to create a database with tables for your Ruby objects. For example, my project has a 'Users' table and a 'Tickets' table. A user 'has-many' tickets and a ticket 'belongs-to' a user, which is their table relations. From there you start creating controller routes which is what will let a user properly navigate to the corresponding HTML forms which is what will dislpay actual web pages of text and links to navigate to different pages of the app. Probably the biggest part and most important part of this section. It is here where one really has to bring in their knowledge of Ruby, like variables and the scope of those variables, iteration and other techniques. 


The first goal for me from this point was making the functionality for a user to sign in, log in and log out. A users data for those things need to be properly stored into a databse in order for a user to be able to do ANYTHING in the app from there (hence why setting up the database should always be the first step). Once data is being persisted to the database properly, I moved on to implementing full CRUD convention. CRUD stands for "Create, Read, Update, Delete". So for the example of my project, a user needed to be able to create, read, update and delete a "ticket". You would be surprised how many times a day you use something that was created with and follows these rules! Whenever you make a new post on Facebook, Twitter, etc. full CRUD is being used! How cool?!


I found that I was far less intimidated starting this project then I was on the first project which was the Ruby CLI datagem. Having a better idea on how to start and get things rolling was a big take away from the first one. I also think that working in the local browser to visibly see things step by step as I created them makes a big difference as well. At this point in the schools cirriculum, you truly start to see how the subjects you move onto build on the prior ones. Learning to code is daunting at times for sure but I think the road is filled with gratifying accomplishments and hurdles worth jumping over. 

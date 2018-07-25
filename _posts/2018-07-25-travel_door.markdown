---
layout: post
title:      "Travel Door"
date:       2018-07-25 14:49:27 +0000
permalink:  travel_door
---



Rails project has been a bit more complicated for me then I expected. This was because a lot was going on in my life when I started the project and I had to put it on hold for a bit, since I had to take a month off. When I was able to go back to it, I reviewed the rails unit again to make sure my memory was up to par.

My project app is a travel website, that allows the user to keep track of where they want to travel and where they travelled to, sort of like a bucket list travel site. Its focus is mainly broad, for instance continent, countries, and cities. I do eventually want to simplify it more to be focused on a specific area. I created my own wireframe before getting started on the project.

After downloading rails and creating my models, tables and associations, my focus turned to sign in/ sign up. I used  the devise gem because it is a flexible authentication solution for Rails. It made the sign in/sign up authentication process much easier. Difficulties arose when I wanted to sign in through third party website. Omniauth and devise have a specific way of working together especially since devise has a lot of moving parts, things can get complicated pretty quick. For me this was a good way to get a deeper dive on devise.

I downloaded the omniauth facebook gem. Trying to make facebook work with devise was a bit difficult especially since a few months back a lot of changes were made to the facebook developer site. I kept getting errors when my app tried to connect. So, I opted for working with google-oauth as my third party login. It worked out perfectly, and user is now able to sign in easily through their google account.

In my previous project I didn't play around much with css, but this time around I wanted to use CSS to spice up my application, which was a plus, because CSS is fun and there's so many things one can do with it.  

This project was definitely a great learning experience for me, it taught me a lot about patience and debugging. I went through many minor issues here and there trying to work with current user. Even though I had Devise in place, current user issues kept arising. However, this allowed me to extensively work with pry and console, which allowed me to understand even the simplest aspect of my code. 

Now that I've reached this point, even though project requirements are completed, what I want out of the website isn't. In Sinatra we had to type out all codes and all requirements, exactly what we want the app to do detailed. With rails things are simplified and there are many shortcuts. I want to continue working on this website and eventually head it towards an educational route. 

I'm excited for the next unit! Code school has truly been a rollercoaster journey for me, and I'm drinking in every bit of it while going through life's hurdles. Can't wait to see what jQuery holds!

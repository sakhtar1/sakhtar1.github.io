---
layout: post
title:      "Rails/ jQuery Travels"
date:       2018-12-12 16:52:42 +0000
permalink:  rails_jquery_travels
---


Jumping into this project was an exciting experience for me. Rails allowed me to delve into my project come up with an idea and bring it to life.

With Javascript I was able to grow my project, with different branches reaching to places I never pondered upon while working on Rails. 

In this project I expanded my rails travel project, by including the Bucket List aspect of the travel app. 

The requirements for this app: 

*1. Must render at least one index page via JavaScript and an Active Model Serialization JSON Backend.*

I had a choice between Bucket or Country travelled to list to include a *"See more..."* section. I chose Countries travelled to, because users jot down verfied information on where they've travelled to. 
Therefore, Countries Index page has a *“See More”* link that expands a section under each country to the cities they've travelled to without redirecting them to the individual country show page. 

*2. Must render at least one show page via JavaScript and an Active Model Serialization JSON Backend. *

Since I updated the Countries Index page with a *"See more..." *section. I wanted to implement jQuery into my Buckets section. 

Within the Buckets show page, I wanted to be able to navigate between all Bucket List Country pages with a *"Next Country"* button and *"Previous Country"* button without redirecting the user to another individual Bucket Country page. 

*3. Must reveal at least one `has-many` relationship through JSON that is then rendered to the page.*

The has_many relationships include Country having many users through visits and User having many countries through visits. 

*4.  Must use your Rails application and Javascript to render a form for creating a resource that submits dynamically. *

On the Buckets Index page, when a user adds anew country, the country would be serialized, submitted via an AJAX POST request, with the response being the new object in JSON and then appending that new country to the DOM. 

Therefore, within the Bucket Index page, you can create a new country and it will appear on the same page by exposing the new data in a hidden div, with no refresh.

*5.  At least one of the JS Model Objects must have a method on the prototype.*

This  means that the JSON responses must be turned into JavaScript objects first before the updated data was rendered to the page. So for example I click on a specific Country  (in JSON), and then take the info I needed to create a JavaScript Country object. Then I’d take that object and use it in the rendering of the information. Also, I’d have to add a method to the prototype, which was renderDiv(). This was added to my Bucket form on the Bucket List section

I dealt with many issues throughout my project which was expected. Going from rails to javascript debugging was also different, it was interesting to use both console and terminal to work through my debugging issues. Having a one on one with my tech coach walking through my issues was very insightful, it allowed me to be more open to adding more post requests via ajax. I thoroughly enjoyed working on this project not only because of the level it took my code but also because I learned a lot working on it.







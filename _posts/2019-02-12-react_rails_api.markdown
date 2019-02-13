---
layout: post
title:      "Mental Health"
date:       2019-02-12 09:42:16 -0500
permalink:  react_rails_api
---

My REACT/REDUX project focused on mental health. Having friends and family members who have struggled with depression, I decided to utilize the skills I've learnt in react and use it to create a Mental Health App. The app focused on articles users can read to learn about their mental health, and places they can go to for help.

First, I created a wireframe of my pages, functionalities, and routes I wanted to implement. Essentialy, I thought creating a one pager with all information slowly appearing as user scrolls down would be interesting. However,  I realized I didn't want all my functionalities on one page especially since users will be reading individual articles and rating them.

I created my app through `creat-react-app` and started creating my articles sections, and developing my environment when I realized I needed rails api for my backend. So I created my rails api app, `$ rails new my_api --api` then moved my clients section inside of my rails api folder to be able to use my front-end and backend simultaneously through procfile and rakefile by typing `rake start` on my terminal. 


To differentiate between the two, I knew container components had `connect` from `react-redux`. And components were compartmentalized. The more you can break them down, usually means the more dynamic you can make them. 

I created my static pages, such as login and signup (I plan to implement them fully after I complete this project though I have them set up). Then I created my article pages, new, edit, delete etc. I went back to my rails API and set up my environment. I updated my database, models, controllers, serializers, `rake db:migrate` and `rake db:seed`  my tables and data. Once the tables and seed file migrated the api data was displayed on `localhost:3001/api/articles`. And I was able to see my client site data from rails api displayed on `localhost:3000` via JS/HTML/CSS. This helped verify if my fetch/get/post requests were working. 

I ensured my article reducers specified how my application's article state changed in response to actions sent to the store and made sure the actions information were sent from my app to the store.

Going into this project I was ready to tackle the final round! The end that has a limitless beginning of course...I'm excited to continue working on this app and make it into something real and live on the World Wide Web : )




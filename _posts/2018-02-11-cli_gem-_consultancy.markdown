---
layout: post
title:      "CLI Gem- Consultancy"
date:       2018-02-11 14:39:34 +0000
permalink:  cli_gem-_consultancy
---


Figuring out what I wanted to work on for my first huge project was a struggle. I wanted to do something exciting and meaningful to me. At first I thought why not try some tea websites, scrape various types of tea and their best prices but then I realized coming from an advertisement background that not everyone knows exactly what type of services ad consultancies offer. Therefore I decided to scrape an ad consultancy website. Using the gem, users will point out what types of services they need, and the gem will take in the user information and displaythe types of consultancy they need to meet their demands.

Before I started coding, I watched the first video by Avi the walkthrough of building a CLI gem. It was very beneficial, through it I set up my environment and got a gist of how things were set up. I found it quite helpful since I was able to automatically build my own cli gem, with versions/gemfile/gemspecs all laid out for me. Then I had to build out the environment and tweak the console so the work flow worked well together without too many scripts mixing. 

I knew what I wanted to do and how I wanted to scrape my data. There were many challenges ahead. To name a few:  (1) How to set up my objects so they interacted with each other without any conflicts (2) How to scrape the data I wanted (3) How to output the data the way I had it displayed in my head. Watching Avi's videos I set up my script in a straight forward way so I wouldn't have too many lines of code that would overwhelm me. For instance, I used the initialize method, used attr_accessor for the data I wanted to scrape, @@all to store my data etc. I wanted to next tackle scraping, however I realized once I took a break and went back into my script, I couldn't get access to nokogiri or pry. I was stuck on this for a bit, going over Avi's video, trying to see how I could fix this, then I realized that I had to bundle install every time I went back into my script. I'm not really sure if anyone else went through this issue but it had me on hold for a bit. 

Once this was set, I started scraping.  I scraped on my main class script, I wanted all my data to be laid out in one script before I organized it and had my objects interact. Scraping was a bit difficult as the website I was scraping had data hidden in unique ways, but this was a challenge I enjoyed. I liked using pry to figure out where exactly was the data I wanted hidden and how I could grasp it with the right code. The next challenge was  to go into different pages within the website to grasp specific content. I wanted to know if there was an easier way to do this without going to the specific pages of the website. I went to the CLI gem project study group and asked my question as I noticed the instructor also did the same when she was doing her project. But we couldn't go into the specifics of it since many people had questions. 

I then scheduled a one on one with Kevin. While waiting for session,  I decided to keep trying. I soon realized, I was making it difficult for myself to scrape every page. All I needed to do was, take the url from my previous method and have it as an argument for my content scraping method. So now I was able to scrape all my content and organize it. I had my CLI organized, and now I was ready to test it out. However, every time I tried testing it, I came upon this error: SarwarConsults::Service:Class nomethoderror. I couldn't run my script at all! When I had my one on one I realized this error was a class error method and I had to make my methods into class methods. They were instance methods. Sometimes when we're coding we get so caught up into it, we don't realize the small mistakes. Once I fixed this issue, my script was working! 

As my first major project, this really was a rollercoaster, at times I wanted to give up, because I felt like I was moving 3 steps forward then 5 steps backward. I not only had issues with my script but my github was giving me issues too through my terminal. However, once I was able to get through these obstacles and understand where my errors were, I felt more confident in my abilities to code. Ultimately I enjoyed it, even though at times I struggled, I was able to create a gem of my own with my own code and structure it in a way that was straight forward and easy to read. 








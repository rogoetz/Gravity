---
layout: post
title:  "data collection"
date:   2017-07-25 
author: "Rosa Goetz"
---

# Data Collection 

Good afternoon, all. I'm here to report on another assignment that I had--write a script that could collect data that was input into it, and another script to then put that into something resembling a database. It felt very INLS, understandably--librarians happen to be lowkey (or not) obsessed with collecting information about things. 

I decided to ask some questions about favorite books, mostly because I couldn't think of anything else. My survey went like this. 

* What is your favorite book? 
* Who is the author? 
* How old were you when you first read it? 
* Have you reread it? 
* Do you own it? 

Simple, yes, but fun. Our professor emphasized that the goal wasn't to administer a great survey, or to collect excellent data, but to really go deeper into script-writing and dabble with some SQL and database stuff. Instead of go around and ask other students to fill out my survey, or just put a bunch of stuff in, I decided to go A and B the C of D, by going on Twitter and asking all of the bookish people who follow me what their favorite book was. 

Librarians and booklovers do not like this question. Some of the answers I got back were 'this is cruel' and 'how can you do this to me'. I'm not joking. 

Nevertheless, I got five answers back from people (two cheated and gave me series) and then input my own, for a total of six. 

Writing the script for the data collection was easy. We had done that in class before, and aside from a few small, largely self-induced snags (I was DETERMINED to find a way to generate a random number ID that was different from the one our professor gave us), things proceeded smoothly. And, I did manage to find a unique way to do this, thanks to StackOverflow. 

Where things got difficult was when I started writing the script that involved MYSQL. I wasn't in class on the day when we really went in-depth on what MYSQL was and how to use it, and I was fairly lost. In fact, what I essentially did was identified the main areas of my professors code and built on those. My script was bare-bones, absoltuely no frills or gimmicks, even though those are what make coding fun. And what was also annoying, I'm not convinced right now that it works. It did the first time I tested it, but I haven't been able to generate a database since that seems to have all of the inputs from my first script. Although, that being said, I don't really know what I'm looking at or for, so I could be wrong and it could work. 

This is somewhat irksome to me, because I spent a lot of my time working at Davis working on databases--specifically, the library catalog. But, even though I work with them on a practical level, I'm not sure I understand how to create and interact with them on a more conceptual level. I hate that I missed that section of the class, but those are skills that I can hopefully work on by myself later on. 

If you want to see for yourself everything that I did, please check out my github repository data-collection-, which has all of the work
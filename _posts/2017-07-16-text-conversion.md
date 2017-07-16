---
layout: post
title:  "text conversion"
date:   2017-07-16 
author: "Rosa Goetz"
---

# Text Conversion 

Hello all, 

This is assignment 2 (3?) of my coding and information tools class--in addition to building a script, we've been asked to make a blog post detailing how we did this, what we did, and the products. 

I realized sometime in the middle of our last coding class that it has been years--five, to be specific--since I had a class that did not deal with the humanities, languages or social sciences. 
It's a bit embarassing. The last class I had that fell outside any of those was in high school, and for most of those classes I relied more on 
mathmatically-minded friends instead of actually taking the time to learn for myself. In consequence, I've been fairly lazy in this class, and 
haven't been taking the time to actually understand what's going on (at least, when it doesn't immediately make sense to me. I've been lucky in that pieces
of our work actually do click). 

Not that I'm complaining about the graciousness of friends. I have a friend who does this sort of thing (websites and coding) for a living, and who has 
offered to try and help if I ever need it. But, so far, I haven't. Part of this is because of the collaborative nature of the class--when I was stuck 
on part of the script I made, I overheard someone talking about a solution, asked them about it, and then implemented it. And most of this is such small work 
I'd be almost embarrassed if I had to go to my friend for help (although he's very supportive of my learning to code). 

Ok, on to the actual assignment parameters, which were posted on the [class website](https://inls161.johndmart.in/assignments/2017/07/16/assignment-3-text-conversion/)

As you can read, we had to find a piece of original, preferably structured writing, write a script to convert it from Markdown into a variety of formats, and then write up the results. 

For the writing I chose a rather silly thing I wrote back in high school, ['101 things about me'](101-things-about-me.md). I cleaned it up a bit, to make it slightly less embarassing
to put up in the great wide world. That being said, I can't decide whether it's less or more embarassing that the thing focuses primarily on food. But it is a structured list, so 
it fits the requirements. And it's better than poetry--not that this is saying much. 

Writing the script was easier than I thought, largely because my professor had already put up a very neat template that had comments detailing what he wanted. 
He also worked through variables in class, even though I wasn't paying attention the first time around, and it took me a bit to figure out how they worked--this is still 
something I'm shaky on. I hit a bit of a snag with how ugly it was to have [docname].md.html when I was working on things, but this is where collaboration with classmates
helped out. I also had a bit of a difficult time figuring out how to get it into a PDF, but it was mostly a matter of figuring out what program I needed. 
After that, it was smooth sailing--I even got a bit fancy and added some echo lines and a list of the documents. 

[Here is my completed script:](https://github.com/rogoetz/rogoetz-convert-documents/blob/master/rogoetz-convert-docs.sh)

[Here is how it looked when it ran:](https://codeanywhere.com/api/ca6/file/open/?token=b6339ad0cb47a516ebc86f31f6024d1879c73eef54e8ca0b&connectionId=1237759&path=rogoetz-convert-documents/Screen%20Shot%202017-07-16%20at%2011.04.38%20AM.png&encoding=UTF-8&id=adaae16c42118dcec30ba872ec2a329b&)

It did indeed produce all of the requisite files: 
[HTML](101-things-about-me.html)
[ODT](101-things-about-me.odt)
[DOCX](101-things-about-me.docx)
[PDF](101-things-about-me.pdf)
and even [EPUB](101-things-about-me.epub)

I did laugh, because the file was originally a docx, and it was converted back to a docx from Markdown with a very large and fancy header on it. But it otherwise 
worked beautifully, so huzzah. 

In case any of the above links don't work, here is my [Github Repository](https://github.com/rogoetz/rogoetz-convert-documents). Everything should be in there, 
if you would like to take a closer look. Please don't judge me for the extensive list of food preferences and other confessions. 



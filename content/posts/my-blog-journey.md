---
title: "My Blog Journey"
date: 2019-04-09T10:34:17-04:00
draft: false
description : "Here I go through the evolution of my personal blog post alongside teck stacks I utilized to finally end up here."
slug : "my-blog-journey"
tags : ["personal", "blog", "other"]
---


2 Years ago I decided to start a personal blog to write about tech subjects (mostly salesforce related), In this post, I will take you through the journey that lead to what my blog is today.

## The Beggining

2 Years ago, I wanted to begin blogging about Salesforce subjects. I had recently discovered [Heroku](https://www.heroku.com) and was already familiar with [Django](https://www.djangoproject.com/). So for me it was a no brainer, Start a blog, use Django, Heroku and Voila... Create content!

After setting my repository, I then had a fully fegged site, a database, was using a CMS built on top of Django [Wagtail](https://wagtail.io/) and I proceeded with creating my first blog site - I was basically checking out multiple IDE's and giving my 2 cents on each alongside the Pro's and Con's, however, I quickly realized that this was time consuming. Everytime I Wanted to add, create, edit content, I had to log in to the platform I had setup as an admin, edit as a draft, then publish. Another issue I ran into was storing Images, everytime I did changes to my page models, this would wipe my DB and I would lose my images... 

After that first blog post I wrote, I simply stopped writting... additionally, other projects I was working on the side were taking most of my spare time as well as my participation on [Stackexchange](https://salesforce.stackexchange.com/questions).

##  1 Year Later

I was aware that I had a blog site that was there, and I really wanted to add content, write on Aura lightning components, my personal experiences with the framework, etc etc...
But, some other things took precedence, I also started doing Speaker session at some Community Events and thought that I should probably re-work on my blog with some other framework.

Where I work, A colleague had told me about [Jekyll](https://jekyllrb.com/) and I read about [Github Pages](https://pages.github.com/), so I started thinking of changing approaches and redesigning my blog, but again, lack of time meant nothing would happen for another year...

---

##  2 Years Later

> Ok, enough is enough!

This had to be done, 😅 .  

I had started experimenting with [GO](https://golang.org/)

and wanted to do something in [markdown](https://en.wikipedia.org/wiki/Markdown). Markdown gave me the flexibility of using a markup language to avoid any sort of GUI and quickly write whatever came to my mind and using [GIT](https://github.com), simply push whatever I did locally to a repository and whenI would be satisfied with what I saw, deploy to another repository which would actually host my search page.

As a Framework, I chose [Hugo](https://gohugo.io/), which is built on top of Golang. It is a static site generator which has been around since 2013. Setting myself up took literally 20-30 minutes + getting familiar with the templating and static generator functionality. Then I had to get familiar with hosting my site on Github, so that took me another 15 minutes.

I have to say, I am very satisfied with the result, and would definitely recommend this approach for building a static site.

One of the disadvantages I saw with Heroku was the build time && the fact that the free tier puts the machine to sleep after 30 minutes of activity, but overall it is not a downer for more complex projects and testing. Heroku itself has a greater learning curve, but in the long run is definitely useful.

![Gopher](https://raw.githubusercontent.com/golang-samples/gopher-vector/master/gopher.png)
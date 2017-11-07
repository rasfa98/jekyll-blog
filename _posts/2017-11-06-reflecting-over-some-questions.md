---
layout: post
title:  "Reflecting Over Some Questions"
date:   2017-11-06 03:04:09 +01
categories: posts
---

## What do you think of pre-compiling your CSS?
### Compare to regular CSS
### Which techniques did you use?
### Pros and cons?

## What do you think of static site generators?
### What type of projects are they suitable for?

### What is robots.txt and how have you configured it for your site?
The file robots.txt is used to give instructions to web robots/spiders/crawlers and it tells them what to view and where on the site they are allowed. I have configured my robots.txt so the robots don't have access to useless folders and files such as _sass, _includes, 404.html, Gemfile.lock and so on. I did this because search robots used by google and others only needs access to the files containing the information.   

### What is humans.txt and how have you configured it for your site?
It's a file containing information about the team that have worked on the site. It also shows information about the IDE used for developing the site together with the different standards (HTML5, CSS3) and components (Jekyll, Sass). The file also contains the date when the site was last updated.

### How did you implement comments to blog posts?
When implementing comments to my blog posts I used a service called *Disqus*. It makes it possible for the users to comment on every blog post, since I'm using jekyll which allows me to add the *Disqus* service to every post.html file.

### What is Open Graph and how do you make use of it?
Open Graph is a service that is used to edit the information when the website is being publish on social media such as Facebook or Twitter. I have added information for the title, description, image, and the website url and type. If I then decide to share it a image with descriptive information will be displayed.


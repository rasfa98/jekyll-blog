---
layout: post
title:  "Reflecting Over Some Questions"
date:   2017-11-13 03:04:09 +01
categories: posts
---

### What do you think of pre-compiling your CSS?
I thinks it's an easy and efficient way to style your websites. It also adds new features so that you for example don't have to repeat yourself as much and so that you can keep your CSS in seperate files. 

### Compare to regular CSS?
As I mentioned I really like the fact that you don't have to repeat yourself when writing CSS using a pre-processor. I think it's more difficult in the beginning to write CSS in a different way but I think it's something you get used to. I like to write CSS using a pre-processor more than I like writing regular CSS and you can produce websites much faster. 

### Which techniques did you use?
I used a pre-compiler called Sass which is one of many. I used functions such as variables, inheritance, mixins, partials, imports, nesting and operators. By using variables and operators together with mixins the regular CSS worked like a new language. When I then combined it with inheritance and nesting I could re-use different pieces of code for example border-radius for all the different browsers. Partials then made it possible to seperate my Sass code into modules. 

### Pros and cons?
The pros of using a pre-compiler (Sass) is that you don't have to repeat yourself and the development of the site is much easier than before. You can also use a command that allows you to compress the file that is generated which reduces the file size. 

The cons are that you can't edit a Sass file if you don't have all the different programs that's required. It's also a "language" that's not as common as regular CSS and because you can use different pre-compilers everybody maybe doesn't use the same. This creates a problem when discussing with other people. 

### What do you think of static site generators?
I think it's a fast and easy way to create simple websites and it makes the process from idea to product much faster. I also thinks it's nice that I only have to edit the navigation or header from one file instead of editing it at five places. 

### What type of projects are they suitable for?
They are suitable for projects where you need a simple blog or website that don't require any advanced functionality such as admin pages. 

### What is robots.txt and how have you configured it for your site?
The file robots.txt is used to give instructions to web robots/spiders/crawlers and it tells them what to view and where on the site they are allowed. I have configured my robots.txt so the robots don't have access to useless folders and files such as _sass, _includes, 404.html and so on. I did this because search robots used by google and others only needs access to the files containing the important information.   

### What is humans.txt and how have you configured it for your site?
The file contains information about the development of the site. The file contains information about the team that have worked on the site. It also shows information about the IDE used for developing the site together with the different standards (HTML5, CSS3) and components (Jekyll, Sass). The file also contains the date when the site was last updated.

### How did you implement comments to blog posts?
When implementing comments to my blog posts I used a service called *Disqus*. It makes it possible for the users to comment on every blog post and since I'm using jekyll I can add it to every post by editing post.html.

### What is Open Graph and how do you make use of it?
Open Graph is a service that is used to edit the information when the website is being publish on social media such as Facebook or Twitter. I have added information for the title, description, image, and the website url and type. If I then decide to share it a image together with descriptive information will be displayed.

---
layout: post
title:  "Reflecting Over Some Questions"
date:   2017-11-13 03:04:09 +01
categories: posts
---

### What do you think of pre-compiling your CSS?
I thinks it's an easy and efficient way to style your websites. It also adds new features so that you for example don't have to repeat yourself as much, and it allows you to keep your CSS in seperated files which is very good.

### Compare to regular CSS?
As I mentioned I really like the fact that you don't have to repeat yourself when writing CSS using a pre-processor. In the begining I thought it was much more difficult to use Sass than regular CSS but when I learnd more and more it quicky became easier to style a website. Now I prefer Sass over regular CSS and it's something that I will use much more in the future.

### Which techniques did you use?
I used a pre-compiler called Sass which is one of many. I used functions such as variables, inheritance, mixins, partials, imports, nesting and operators. By using variables and operators together with mixins the CSS worked like a new language. When I then combined it with inheritance and nesting I could re-use different pieces of code for example border-radius for all the different browsers. Partials then made it possible to seperate my Sass code into modules. 

### Pros and cons?
The pros of using a pre-compiler (Sass) is that you don't have to repeat yourself and the styling of the site is much easier than before. You can also use a command that allows you to compress the CSS-file that is generated which reduces the file size. 

The cons are that you can't edit a Sass file if you don't have all the different programs that's required. It's also a "language" that's not as common as regular CSS and because you can use different pre-compilers everybody maybe doesn't use the same. This creates a problem when discussing with other people. 

### What do you think of static site generators?
I think it's a fast and easy way to create simple websites and it makes the process from idea to product much faster. I also thinks it's nice that I only have to edit the navigation or header from one file instead of editing it at five places. I felt the same when working with Jekyll as when working with Sass, in the beginning it was difficult but now when I've learned it I really understand that i'ts a powerful tool for creating static websites. And the fact that you can download themes if you don't want to create your own is very nice and if you just want to edit a existing theme you can do that as well.   

### What type of projects are they suitable for?
They are suitable for projects where you need a simple blog or website that don't require any advanced functionality such as admin pages. You can use it for creating a simple blog, a portfolio website or anything you want really, as long as you don't want advanced functionality as mentioned before. If you just want to get a site up and running Jekyll is a great option. 

### What is robots.txt and how have you configured it for your site?
The file robots.txt is used to give instructions to web robots/spiders/crawlers and it tells them what to view and where on the site they are allowed. I have configured my robots.txt so the robots don't have access to useless folders and files such as _sass,_includes, 404.html and so on. I did this because search robots used by google and others only needs access to the files containing the information that will be read and I thought that configuring my robots.txt this way I might speed up the process. I also don't have anything important on my site and I have not added my email-address so I didn't feel the need of blocking all robots on my site. It's also important to know that you can't hide files or information from bad robots or hackers since they can just find your robots.txt file very quickly and then locate the "hidden" files.

### What is humans.txt and how have you configured it for your site?
The file contains information about the development of the site and information about the team that have worked on the site. My file contains information about the IDE/programs used for developing the site together with the different standards (HTML5, CSS3) and components (Jekyll, Sass). The file also has the date when the site was last updated. I have also written my twitter username and my location. I didn't include my email-address since I don't want any spam mails and such. I've also added my name.

### How did you implement comments to blog posts?
When implementing comments to my blog posts I used a service called *Disqus*. It makes it possible for the users to comment on every blog post. Since I used Jekyll there already was a file where I could place my Disqus code. This was then added to every blog post by including it to the post.html file. I had to delete an if-statement in the post.html that controlled when Disqus should be shown, but after that it worked without any problems.

### What is Open Graph and how do you make use of it?
Open Graph is a protocol that allows you to edit the preview of the site when it is being shared on Facebook, Twitter etc. You can specify all sorts of thing like image, title, url, type, description, and much more. You can "install" Open Graph to your site by editing the meta data in your head section/file. I have used title, url, type, image and description. For the image I've used the keyboard that is shown on the startpage and to preview my Open Graph data I've used a plugin for Google Chrome.
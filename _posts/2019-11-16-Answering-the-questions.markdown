---
layout: post
title:  "Answering the questions"
date:   2019-11-17 10:49:33 -0600

---

*  What do you think of pre-compiling your CSS?

I Think it is an interesting way of breaking down the CSS to target different settings. 
It does however add more complexity to something that really doesn´t need it.

*  Compare to regular CSS

I prefer the regular CSS because you have everything in one spot and you do not have to look through different files to find what you are looking for. In my personal opinion it is more work and more complexity.

*  Which techniques did you use?

On this site i have mostly changed colors, the display trait of the header links so it is horizontal.
I tried to focus on the implementation of the required things first before i started altering the layout.
However i failed with above mentioned requirements in large parts so i didn´t have time to do the layout.

*  Pros and cons?

It is an entirely different way of doing things, CSS is pretty straight forward while precompiling adds a
different level of complexity and thus another learning curve. Once you finally learn it and how it completely works i am guessing it will work in your favour in terms of speed

*  What do you think of static site generators?

I do not like it at all. It generates a site where you have NO idea where to change things in.

*  What type of projects are they suitable for?

A blog where you do not want to change much and just work with the template you are getting and add information.

*  What is robots.txt and how have you configure it for your site?

robots.txt is a file that robots searching the web first land on when accessing your site and checks for 
permissions. 
I configured my robot to allow Google but disallow the rest.

*  What is humans.txt and how have you configure it for your site?

humans.txt is a file that contains more or less the "credits" section of the site, with the developers, the people previously named individuals want to thank and a description of what languages and software that was used in the site.

I added it to the site, added some information in the file, but i have no idea how to implement it or the button/link at the current time.

*  How did you implements comments to blog posts?

In my case i added "comments: true" and "# other options" to the Front Matter of the blog posts.
According to documentation this will include a comments section and with my chosen options from the disqus website.

*  What is Open Graph and how do you make use of it?

I have no idea what this does and even less idea on how to implement it on this static site generated site.
I´ve read the documentation and i know roughly how to add it to a normal page, but with the SCSS and boilerplate site it is lost to me.
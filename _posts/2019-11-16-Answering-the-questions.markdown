---
layout: post
title:  "Answering the questions"
type: Blog-post
date:   2019-11-17 10:49:33 -0600

---

1.1  What do you think of pre-compiling your CSS?

I Think it is an interesting way of breaking down the CSS to target different settings and subsettings. 
It does however add more complexity to something that really doesn´t need it in terms of nesting.

1.2  Compare to regular CSS

I prefer the regular CSS because it is sectioned up into individual elements, it is very clear where to look and for what. In my personal opinion it is more work to learn the scss or sass and more complexity due to nestled categories.
However, that being said, it is nice to be able to declare variables and use relative statements towards those variables.

1.3  Which techniques did you use?

Working with the minima template i mostly used and changed the presets, switched the set pixels to percentage on few spots because frankly it looked horrible on my 1440p screens with a hard set to 800px width.
I however ended up importing most of the files to my own repo to change small things with the template.
The techniques used in the template and so also used in this project is:


* Variables, most variables are declared in minima.scss files and referred to throughout Layout.scss and base.scss
* Nesting, There is some nesting involved in the template files, however i have not used it in any of my additions or changes.
* Modules, minima.scss stands as the main file and imports the three sub files.
* Mixins, There are manipulations of variables in the scss sub-files where for example, font size is increased or decreased in comparison to the original.


1.4  Pros and cons?

It is an entirely different way of doing things, CSS is pretty straight forward while precompiling adds a
different level of complexity and thus another learning curve. Once you finally learn it and how it works i am guessing it will work in your favour in terms of speed.
Making it more like an actual programming language can also aid people coming from a more traditional programming language.

For me personally i´d say that i am not quite at the point where i know it well enough to be able to gain anything from using SCSS instead of CSS.

2.1  What do you think of static site generators?

I do not like it at all. It generates a site where you have NO idea where to change things in.
And the templates are rather often quite hard to understand. What goes where, where can i change what and so on.
In that perspective, i´d probably much rather create an entirely new site, and then import all the settings into one of these static site generators.
Which is probably what i should have done in the first place instead of messing about with one of the template themes.

2.2  What type of projects are they suitable for?

A blog where you do not want to change much and just work with the template you are getting and add information.
I guess it can also serve as a decent platform for testing small javascript features.

3.1 What is robots.txt and how have you configure it for your site?

robots.txt is a file that robots searching the web first land on when accessing your site and checks for 
permissions. 
I configured my robot to allow Google but disallow the rest.

4.1 What is humans.txt and how have you configure it for your site?

humans.txt is a file that contains more or less the "credits" section of the site, with the developers, the people previously named individuals want to thank and a description of what languages and software that was used in the site.

I configured it using a tutorial i found online that automatically changes the timestamp for changes on it, except for that i added the basic information for the site and added a link to it in the footer with their provided gif.

5.1 How did you implements comments to blog posts?

In my case i added "comments: true" and "# other options" to the Front Matter of the blog posts.
According to documentation this will include a comments section and with my chosen options from the disqus website.
I also added the disqus_comments.html template code and added my site specific identifier parameters.

There are some issues arrising from the standard template when using disqus, but it seems to be working allright.
They seem to be connected to GET calls from the embed.js which i do not have access to.

6.1 What is Open Graph and how do you make use of it?

Open Graph is a thumbnail addition to show a very short summary of what the site is about when you post a link in for example Twitter and facebook.
I added the standard inputs for jekyll in head.html and then created the parameters required in _config.yml
---
title: Tasky Manager Project
date: 2020-06-07 11:58:47 +02:00
modified: 
tags: [chrome, extension, chrome extensions, productivity tools, productivity chrome extensions]
description: Post about the productivity chrome extension that I've made as a part of my porfolio.
image: "/Tasky-Manager-Project/shell_evolution.png"
---

<a href="(place here url chrome store)" target="_blank" rel="noopener">Tasky Manager</a>  is my next Github project that I'm working on. The purpose of this extension is to help people to remind when they should perform a specific task on a website. You can check my project on  the below Github repository 👇.

- <a href="https://github.com/p3javier/tasky-extension" target="_blank" rel="noopener">Tasky Manager repository</a>

You aren't going to see so many commits on this repository because I did "offline" almost all of the job needed. Although it still needs to clean the code code (currently is a mess), and provide a well documentation in order to make it able for being used and extended by others.

Also I've deleted almost all of the unnecessary node modules before publish this post because previously the node_modules folders was so heavy.

####How this extension was made

Basically for this extension I've used 3 libraries and the rest just was pure **HTML + CSS + JS.**

The libraires used were:

- Materialize for CSS styles.
- jQuery just to make it easier setup Materialize.
- And Moment.js to humanize the remaining time till the deadline of a task.

Additionally I've followed the <a href='https://github.com/airbnb/javascript' target='_blank'>AirBnB guide style</a> with <a href='https://eslint.org/' target='_blank'>ESLint.</a>

####How to use

I think that this is a really easy to use extension yet useful too.

Basically you create tasks to perform in a webpage with this extension, add a deadline, a reminder before the deadline and a description of the task. And that's it, you have you're task created.
<figure>
<img src="/Tasky-Manager-Project/2020-06-07.png" alt="Task creation">
<figcaption>Fig 1. Tasky extension.</figcaption>
</figure>

In addition, this extension includes noisy notifications and a color code to make ir more visual.


<figure>
<img src="/Tasky-Manager-Project/2020-06-07 (1).png" alt="task list">
<figcaption>Fig 3. Task list.</figcaption>
</figure>

####License

This extension has been published under the **GNU Affero General Public License v3.0**.

####Thank you

Thank you for keep reading until here, I hope you enjoy the extension as much as I enjoyed developing it. 😊


##### Resources

- [Evolution shells in Linux](http://developer.ibm.com/tutorials/l-linux-shells/)
- [Kernel Defintion](http://www.linfo.org/kernel.html)
- [The Shell](http://www.cis.rit.edu/class/simg211/unixintro/Shell.html)

---
title: My New MERN stack e-commerce project 🛒
date: 2020-11-09 09:45:47 +02:00
modified: 2019-08-29 09:24:47 +07:00
tags:
  [
    blog,
    netlify,
    jekyll,
    github,
    MERN,
    React,
    e-commerce,
    React,
    Node.js,
    MongoDB,
    Mongoose,
    Auth0,
    Express,
    CSS,
    html,
    Javascript,
    AWS,
    EC2,
    S3,
    Amazon Route 53,
  ]
description: This is a post about an e-commerce software that I've just created for a company in the health sector.
---

The purpose of this post is not just show off the e-commerce platform (my first serious project by the way). But also to provide useful information to newbies developers to avoid common hardships that I've faced too in the development of this project

<hr>

The code is openly available on Github for educational purposes only. That means that you can use it to learn how to solve a problem that you are facing in your project for example, but not just clone the repo change the logo and use for your company...

<hr>

#### Let's do this

Before start I'm assuming that you have Git installed on your device ass well as a Github account.

#### Prerequisites

Requirements to make it run smoothly on localhost.

- [Mongo Atlas](https://www.mongodb.com/cloud/atlas) account.
- [Auth0](https://auth0.com/) account.
- [NodeJS](https://nodejs.org/en/download/)

- [Bundler](https://bundler.io)

##### Highly recommended

-[VSCode](https://code.visualstudio.com/Download) text editor. -[ES Lint](https://eslint.org/) -[Postman](https://www.postman.com/) account. This will be used to test our API. -[Mongo DB Compass](https://www.mongodb.com/products/compass) the best way to easily visualize your database.

#### Installation

First, you need to clone the Github repo. If you have installed Git on your computer, open a new terminal and type the next:

```bash
$ git clone https://github.com/p3javier/extremum-ecommerce-public.git
```

Now, you have the repo, but since we are using Node and React we need a folder called `node_modules` which contains all of the libraries needed to run the web. Type the next in your terminal:

```bash
$ npm install
```

#### Adding remote repository

Before we adding remote repository, you must have [github](https://github.com/new) repository, if already have repository, just add github remote address to your local folder, with the following commands

```bash
$ git init # initializing project folder
$ git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git # change UPPERCASE with your own!
$ git add -A && git commit -m "Initialize" && git push -u origin master # push code to github
```

Now check your github repository, make sure the files is uploaded correctly.

#### Deploying to netlify

Go [netlify](https://netlify.com) dashboard, and following this step.

1. click `new site from git`, then choose `Github`.
2. then choose your repository where is the jekyll sources uploaded.
3. netlify smart enough to configuring, we just need's are hosting's are hosting's are hosting's are hosting to click `Deploy site button`.

Wait for moment, and voila..! your site's are hosting and using `.netlify.com` tld, if your website wants to look professional, just buy a domain from your favorite domain store. or if you the first time, I advice using namecheap.com*(isn't sponsor)* \*based on my experienced it provides good service and have various TLDs.

So, what you waiting for, just create your own website for free.

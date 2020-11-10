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

#### Setting environment variables

Before we can run the scripts needed to test it in local we need to create a `.env` file. This file is used to avoid the use of sensitive information, such as API keys, directly in our code that later we are going to push to a repo.

So go to `/server/` folder and create a new file with the name of `.env`.

Inside this file copy and paste the next:

```text

CONNECTION_STRING=
SESSION_SECRET=

REACT_APP_AUTH0_CLIENT_ID=
REACT_APP_AUTH0_DOMAIN=
REACT_APP_AUTH0_CLIENT_SECRET=
```

Now, save the file. By this moment this doesn't have the needed yet. This will be covered in the next chapter.

#### Next Chapter

In the next chapter of this tutorial I will guide you through the process of creating a free cloud databe on Mongo Atlas as well as how to configure Auth0 for a SPA.

See you soon!

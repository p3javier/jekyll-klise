---
layout: post
title: My first Github project
date: 2020-05-12 18:30 +0200
modified: 2020-03-07 16:49:47 +07:00
description: Explanation about why I've started this site and how I've reached this point.
tag:
  - me
  - git
  - software
  - presentation
  - portfolio
  - coding
image: /cara-memperbarui-fork-repository/repo.png
---

Hello dear reader, if you are here is because you are interested in my person. Here you'll find a little about who I am and why I've created this website. Welcome.



### How I've entered into this world 💻

I think that the roots of my current love to code are years before I learn my first programming language*, at the university. From my childhood I've been always curious about science and technology (apart from of course the things that every child like). 

Unluckily, I come form a **humble family**. I grew up in a working class neighborhood in **Córdoba (Spain)**. Back to these days my parents didn't have money to buy me a computer, not to mention an Internet connection that was very expensive at that time (early 2000s).

The next step in my love story with the technology came on **2010** when, finally, my parents had money to install Internet on my home. Yes, you've read correctly, **until 2010 I didn't have a personal Internet connection**. This was the beginning of a new era in my story.

### Internet, the beginning of a *new era* 🌐

It's May 2010 and the a *new era* begins for me, It was the era of **Internet**.

Honestly back to those days I didn't use to take the same advantage of Internet as nowadays, where even I depend economically of it. All of what I used on Internet was the usually every teenager:
1. Play online video games.
1. Play music.
1. Watch films.
1. Also watch other kind of films...

But quickly my passion for the technology brought me to other kind of more interesting things on Internet. YouTube, Wikipedia and many more sites were loaded with tons of precious content just there, free, for me.

\* _It was Python 2.X._

### Before Code */Anno ex codice* ⌨️

Tambahkan remote alamat repository yang aslinya disini tak beri nama `upstream`., ganti `ORIGINAL_OWNER` dan `ORIGINAL_REPO` dengan alamat repo aslimu.

```bash
$ git add remote upstream git@github.com:ORIGINAL_OWNER/ORIGINAL_REPO.git
$ git remote -v
> origin    git@github.com:piharpi/www.git (fetch) # forked repo
> origin    git@github.com:piharpi/www.git (push) # forked repo
> upstream    git@github.com:ORIGINAL_OWNER/ORIGINAL_REPO.git (fetch) # upstream repo / original repo
> upstream    git@github.com:ORIGINAL_OWNER/ORIGINAL_REPO.git (push) # upstream repo / original repov
```

Checkout ke local branch `master`.

```bash
$ git checkout master
> Switched to branch 'master'
```

Jika sudah, Merge local repo dengan remote `upstream/master`.

```bash
$ git merge upstream/master
```

Terakhir push local repo ke remote `origin`.

```bash
$ git add -A
$ git commit -m "updating origin repo" && git push -u origin master
```

Selamat mencoba cara ribet ini, semoga bisa dipahami, saya sendiri lebih senang melalui terminal, klo ada yang ribet kenapa cari yang mudah.

##### Resources

- [Syncing a fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork)
- [Update your fork directly on Github](https://rick.cogley.info/post/update-your-forked-repository-directly-on-github/#top)

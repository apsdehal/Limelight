#Limelight

Limelight is a light toned, describing theme for Jekyll.

#Screenshots

Welcome Page

![Screenshot of Welcome Page](http://i.imgur.com/HK6Jj1O.png)

Sample Post page

![Screenshot of Post](http://i.imgur.com/kEkcJYy.png)

Mobile layouts

![Screenshot of Mobile Home](http://i.imgur.com/mpQAj6j.png) ![Screenshot of Post](http://i.imgur.com/IZ5a80M.png)

#Features
- Responsive design
- Customizable
- About me and blog page

#Usage

##Installation

- Start by cloning the github repo using `git clone`
- You must have jekyll installed to run this, use `gem install jekyll` for installing it
- Use `jekyll serve` to run the site live.
- You can use `source watch.sh` to watch changes over screen.scss in case you plan to change default css
- Add your own avatar and welcome picture in `assets/img/` with names `avatar.jpeg` and `welcome.jpeg`
- To use welcome image, uncomment line 415 in `assets/css/style.scss`

##Creating Posts

For creating posts add this snippet in front of your post's markdown file:

```
---
layout: post
title:  "your title here"
tags: your tags here
class: post
---

```

Add content below this and save the post in `_posts` directory (you will have to create it).

#Todo

- Themes
- More customizations options

#License

Open sourced under [MIT License](LICENSE.md) 
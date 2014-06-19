#Limelight

Limelight is a light toned, describing theme for Jekyll.

#Screenshots

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

And save the post in `_posts` directory, you will have to create it. 


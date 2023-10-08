---
title : 'Blog With Hugo'
date : 2023-10-07T21:54:45+08:00
draft : false
ShowToc : true
TocOpen : true
---

## Introduction

For building your blog-site today, what you need is just network connection and 30 minutes, using the following tools:

- [Hugo](https://gohugo.io)
- Github pages

These two services are quite enough for you to start. The first step is to build the site. The instructions in [Hugo](https://gohugo.io) document is quite clear. Read the doc.

## Add $\LaTeX$ Support

Use MathJax and handle the underline issue.

see [jiguankai's blog](https://jiguankai.cn/post/hugo_mathJax/) (I just copy paste the solution XD).

## Add Photos.

You can view your current blog folder as a tiny subsite. Put resource under it and reference them as you like.

```md
![cute-cat](images/cute-cat.jpg)
```

The effect is:

![cute-cat](images/cute-cat.jpg)

*Note: you should store you article as `post/your-post/index.md` rather than `post/your-pos/your-post.md`*

## Add Non-HTML Attachments.

Just attach a link :)

## Restrictions

- **Github** is not a good place to store your data. You should consider migrating your website to a server once you get familiar with Hugo (Renting a server with public ip costs around $50 a year).
- **ParapMod** or other theme is a good place to start, but you should consider managing your own theme if you want to take a change.



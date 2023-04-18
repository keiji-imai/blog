---
title: "Creating a Blog"
date: 2023-04-16
draft: False
description: "How to make your own website"
summary: "How to make your own website"
---

In a previous [post](https://kogappa.com/posts/whyblog/), I explained why I created a blog. Here I will explain how I made it.

## Inspiration

The first step of any project should be doing research. Here are some blogs that were inspirations to me (from a content perspective):
 - Ben Katz's blog, [Build-its](https://build-its-feed.blogspot.com/)
 - Paul Graham's [website](http://paulgraham.com/)
 
## Choosing a Website Builder

The popular options are Blogger, Squarespace, Wordpress, and Wix. These are relatively simple to set up and good options if you don't want to debug or write code. Blogger is free, but it is not very customizable. The other options cost money.

What I used instead was [Hugo](https://gohugo.io/), an open-source website builder. 
Here's how it works:
1. [Choose a theme](https://themes.gohugo.io/)
2. Read the [documentation](https://blowfish.page/) on your theme
3. Set up your website how you like it and run it with 

I used an open-source website builder because although it requires more programming setup, it's free and looks good. I didn't have to write any html or css. That's all handled by the theme. The setup was mostly reading documentation, adding features, and debugging random problems.

You can also build a website from scratch using React or other web dev tools. I was too lazy to do this, but if you are interested in web dev that might be fun.

## Publishing

The first step is to buy a domain. I chose "kogappa.com" because keijiimai.com seemed too boring. A "kogappa" (baby kappa) is a cute mythical creature that lives in lakes and eats people. I was able to get the domain for just $9 per year from Cloudflare domains.

Once you have your domain, you can publish your website for free using [Cloudflare Pages](https://pages.cloudflare.com/). Then whenever you push to your github repo, it will automatically update your website. 
---
layout: post
author: BernardMcWeeney
title: Building this site.
date: 2023-06-15T16:16:40.957Z
image: https://i2.wp.com/adamnaamani.com/wp-content/uploads/2019/12/jekyll.png?fit=1920%2C600&ssl=1&is-pending-load=1
categories: " Code CMS "
tags: " Jekyll Decap-CMS Github-Pages "
pin: false
mermaid: true
summary: "Building a journal site, with Jekyll, Decap CMS, and Github-Pages "
postType: journal
---
# Building This Site

I got invested with Static sites through the use of CloudFlares Pages, Similar to Github Pages (I believe they are the same thing). This allowed me to host my first business website for free, which just had simple html and css.

But then I stumbled across Jekyll and I fell down and I fell down a deep rabbit hole of sorts. I was blown away with this template: [jekyll-theme-chirpy](https://github.com/cotes2020/jekyll-theme-chirpy). I love the features it had out of the box such as search, taxonomy support, dark mode, beautiful design, rss feed , among others. I was quickly able to setup the template on Github Pages and have a working site.

I wanted more though : ), I wanted the ability to simply add posts to the website using a refined editor that handle the Front Matter easily. I thought I had an elegant solution with [prose.io](https://prose.io) but it did not work well with the jekyll - chirpy theme, the front matter wouldn't load properly.  I had to find another solution and that was when I cam across [Decap CMS](https://decapcms.org/) 

Decap CMS basically adds a admin interface to your website, It was exactly what I needed. I followed this excellent tutorial: [Decap Tutorial](https://sujaykundu.com/blog/how-to-setup-netlify-cms-with-github-pages-hosted-jekyll-blog/) which links Netlify to your Github account for login credentials. It's completely free which is the beauty of the whole thing. I also looked at the documentation for slightly tweaking my configuration: [Decap Docs](https://decapcms.org/docs/jekyll/)

I also hosted my site on a custom domain which is easy to do with Github and I bought the domain through BlackNight and I host the dns records on CloudFlare.

My site is now functioning well, however I do plan on expanding the capabilities of the Admin side of things, currently I only have it working on the _post collection, I would like the ability to easily edit the author profile, pages and navigation links, which I believe is 100% doable but will require some integration with the chirpy theme and I might have to fork the chirpy theme instead of using the starter template. However for now its working as I initially intended and I am happy.

Using static websites is really a no brainer for simple sites, they are free and they are super fast. While configuration might take a little longer then a regular WordPress installation, to me the benefits out weigh the negatives.



﻿Author Note: I did fork the site and made the necessary changes I wanted, All pretty hassle free.
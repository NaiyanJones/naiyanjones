---
title: How I built this website
published: true
date:
  'Sun Jun 07 2020 01:00:00 GMT+0100 (British Summer Time)': null
categories:
  - Personal
tags:
  - Website
  - Programming
excerpt_separator: <!--more-->
analytics:
  provider: google-gtag
  google:
    tracking_id: UA-168799890-2
    anonymize_ip: false
---
I had no previous experience with making websites at all. The most I have done was use [Medium.com](https://medium.com/about) which involved typing blog posts out in an editor and then clicking publish. So building this website was a fun learning experience.

To make this website I installed [Jekyll](https://jekyllrb.com/) and the theme [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) which I then hosted on [GitHub pages](http://jmcglone.com/guides/github-pages/).

Jekyll is a static site generator which among other things means you can use templates, load quicker and create content quicker. The Jekyll community is the biggest with many themes, of which Minimal Mistakes too my fancy. It allows good customisation while still being minimal and content first. And GitHub allows free hosting, forks and version control. Meaning you can both test features and rollback if you mess up. Perfect!

Following on from setting up on GitHub I wanted to change the navigation links and add an Contact page with a form. My search led me to [Formspree.io](https://formspree.io/) which is free as long as you get under 30 contact form submissions per month.

I knew I wanted a certain look but since the website was a work-in-progress I used some [placeholder.com](https://placeholder.com/) images as, you guessed it, placeholders. I then settled on a mixture of [UnSplash](https://unsplash.com/) free images and a couple custom images. For free icons I used [FontAwesome](https://fontawesome.com).

Next I had to find a way to import my Medium posts onto this blog. I certainly didn't want to do any copy & pasting! I found that someone had the same problem a few years ago, and followed their instructions for [medium-2-md](https://www.gautamdhameja.com/medium-to-markdown-converter/).

Finally I bought my own domain, naiyanjones.com and set it as a [custom domain](https://help.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site) to override the default GitHub Pages site URL.

Throughout building this website I also searched around and found many resources, from how-to guides, Youtube videos, and other people's blogs which I used for inspiration. A selection which I've linked below.

### Tech

1. [Jekyll](https://jekyllrb.com/) - for generating the static pages of the site
2. [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) - the Jekyll theme for styling my site
3. [Github](http://jmcglone.com/guides/github-pages/) - for version control
4. [medium-2-md](https://www.gautamdhameja.com/medium-to-markdown-converter/) - importing Medium blog
5. [Optimize-images](https://no-title.victordomingos.com/projects/optimize-images/) - to optimise imported images
6. [Prose.io](http://prose.io/#about) - for writing simple posts
7. [Atom](https://atom.io/) - for file editing
8. [Formspree.io](https://formspree.io/) - for contact page

### SEO

1. [Google analtyics](https://analytics.google.com/analytics/web/#/) - track traffic
2. [Google Search Console](https://search.google.com/search-console/about) - optimise SEO

### Languages used

1. [YAML](https://yaml.org/) - for blog posts
2. [Markdown](https://www.markdownguide.org/) - for blog posts
3. [Python](https://www.python.org/) - for using Optimize-images

### Miscellaneous

1. [FontAwesome](https://fontawesome.com) -  site icons
2. [UnSplash](https://unsplash.com/) - images
3. [Images by Nemanja Manojlovic](https://www.behance.net/nemus) - custom images
4. [Setting a custom domain](https://www.youtube.com/watch?v=mPGi1IHQxFM) - Changing naiyan.jones@github.io to naiyanjones.com

## Helpful resources

1. [CommonMark](https://commonmark.org/) - markdown reference guide
2. [Jekyll pages](https://jekyllrb.com/docs/posts/) -  reference guides for Jekyll
3. [Jekyll Tutorial by Mike Dane](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB) - a YouTube playlist on setting up a Jekyll websites
4. [Organizing Jekyll Posts](https://miklb.com/blog/2016/04/26/organizing-jekyll-posts/) - reference guide for organisation

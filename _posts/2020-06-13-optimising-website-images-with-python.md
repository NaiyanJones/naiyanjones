---
published: false
date:
  'Sat Jun 13 2020 01:00:00 GMT+0100 (British Summer Time)': null
categories:
  - Personal
tags:
  - Website
  - Programming
  - Python
excerpt_separator: <!--more-->
analytics:
  provider: google-gtag
  google:
    tracking_id: UA-168799890-2
    anonymize_ip: false
title: Optimising website images with Python
---
## Optimising website images with Python

After downloading all the images from my Medium posts with [medium-2-md](https://www.gautamdhameja.com/medium-to-markdown-converter/) and uploading custom images I plugged my site into Google's [Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/).

Desktop speed was looking good.

![image-center](/assets/images/desktop_before_opti.PNG){: .align-center}

Mobile.... not so good.

![image-center](/assets/images/mobile_before_opti.PNG){: .align-center}

So off I went to find a way to optimise all my images, which led me to [optimize-images](https://pypi.org/project/optimize-images/) written in Python. I'm a simple man and so was the module. I ran it through the command line and chose my folder full of images.

To install:

`pip3 install pillow optimize-images`

Choose folder path filling in the blanks afetr ./:

`optimize-images ./`

As you can see the results were pretty good for desktop.

![image-center](/assets/images/desktop_after_opti.PNG){: .align-center}

And brilliant for mobile!

![image-center](/assets/images/mobile_after_opti.PNG){: .align-center}
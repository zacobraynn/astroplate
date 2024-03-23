---
title: Updated Title!!
meta_title: Updated meta title!
description: this is meta description
date: 2022-04-04T05:00:00.000Z
image: /banner.png
categories: []
author: Farhad
tags: []
draft: false
---
Part of [Hotwire](https://turbo.hotwired.dev/) are Turbo Frames. They allow you to insert a page, or just a part of it, into another page.
I've found this feature quite magical when it was released. 🪄
But it would be useful to apply some Css conditionally, based if the page was viewed standalone or within a turbo frame.
Previously, and still valid, way to do this was adding a wrapper/container class around the turbo-frame and nested the css within here.
With Tailwind Css this is easier to do. Let's take the following example from [Helptail](https://helptail.com/) (Spinal's internally developed email support tool for calm SaaS companies):
|Hello|Hello|
|---|---|
|sdfsdf|sdfdfsd|

This is the email composer on a standalone page.
# Heading 1
## Heading 2
### Heading 3
### Code code
### 
![image](/banner.png "")
---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: '{{ .Date }}'
publishDate: # put the actual date to publish here, format of '2024-02-31T21:02:15-06:00'
draft: true
image_webp: /images/blog/default.webp # put the actual webp image to use here, stored in /static/images/blog/
image: /images/blog/default.jpg # put the actual jpg image to use here, stored in /static/images/blog/
authors: # put each author on its own line as a yaml item
# - author 1
# - author 2
description: "This is meta description"
summary: "This is what displays as the summary on the main page"
categories: # put each category on its own line as a yaml item
# - category 1
# - category 2
tags: # put each category on its own line as a yaml item
# - tag 1
# - tag 2
---
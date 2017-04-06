# jumpstartTriage.github.io
The "official" Jumpstart Triage website.

## How-to:
This guide will teach y'all the basics on how to post on this here website.
This website is built on Jekyll, so remember that and if you have any issues, you can do one of them there fancy google searches to fix it.

1. To make a post on the blog, navigate to /_posts/.
2. Create a .md file under the naming convention; yyyy-mm-dd-name-of-post.md.
   * This website uses markdown for it's post format. Google markdown for formatting guidelines.
3. Put this code snippet on the top:
   * This is YAML, which is REQUIRED for Jekyll to process the post as a post.
```
---
layout: post
title: "Post name here!"
date: yyyy-mm-dd
excerpt_separator: <!--more-->
---
```
4. Write your content under said header, using markdown ass formatting.
5. You can use the `<!--more-->` tag to add a "Read More?" cutoff to your posts.
6. Commit the file, (sync if on desktop) and you should see your post in about 3 minutes.

Any questions? Email hello@yukonw.com for support.
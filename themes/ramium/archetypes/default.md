---
title: {{ replace .Name "-" " " | title }}
date: {{ now.Format "2006-01-2" }}
tags: [tag1, tag2]
image: "/image/blog-pic.jpg"
---

Article goes here. 

For other options, put these in the front matter:
    description:            "A description" other than the blog intro
    draft: true             to not publish article yet
    showDate: true/false    to enable/disable showing dates
    math: true              to enable showing equations (katex)
    chordsheet: true        to add chordsheet styelsheet
    lastmod: 2020-4-11      after modifying an article, set lastmod to let google know
                            that you have updated the article (SEO)

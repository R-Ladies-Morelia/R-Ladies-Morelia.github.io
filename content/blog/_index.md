---
title: R-Ladies Blog
description: |
  Aquí encontrarás....
author: "@rladies_morelia"
show_post_thumbnail: true
thumbnail_left: true # for list-sidebar only
show_author_byline: true
show_post_date: true
show_button_links: false
# for listing page layout
layout: list-sidebar # list, list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: Cosas interesantes
  description: |
    Aquí.....
    
    Check out the _index.md file in the /blog folder 
    to edit this content. 
  author: "@rladies_morelia"
  text_link_label: Subscribete en Meetup
  text_link_url: https://www.meetup.com/es-ES/rladies-morelia/
  categories_link: true
  series_link: true
  tags_link: true
  show_sidebar_adunit: false # show ad container

# set up common front matter for all pages inside blog/
cascade:
  author: "@rladies_morelia"
  show_author_byline: true
  show_post_date: true
  show_comments: false # see site config to choose Disqus or Utterances
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent posts
    text_link_url: /blog/
    show_sidebar_adunit: false # show ad container
---

** No content below YAML for the blog _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside blog/. You may still override any of these by changing them in a page's front matter.**

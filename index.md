---
layout: page
title: Home
tagline: 
---
{% include JB/setup %}
Home of the King of Spice, Spice_King!
{% assign posts = site.posts %}
{% assign listing_limit = 5 %}
{% include post-listing.html %}
---
layout: subpage
title: A1 Q1.
description: "What is the Internet?"
categories: 
tags: [WEB101, Assignment 1]
---

###### What is the Internet?

This is a word test count. I have typed 12 words here.


**Draft One** *max 150 words*.


---

{% capture words %}
  {{ page.content | number_of_words | strip_html | minus: 91 }}
{% endcapture %}
{% unless words contains "-" %}
  {{ words | strip_html | plus: 0 | append: " words" }}
{% endunless %}

{% capture words %}
  {{ page.content | number_of_words | strip_html | minus: 5 }}
{% endcapture %}
{% unless words contains "-" %}
  {{ words | strip_html | plus: 5 | divided_by: 180 | append: " minute read" }}
{% endunless %}

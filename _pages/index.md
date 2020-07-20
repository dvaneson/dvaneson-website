---
layout: defaults/page
permalink: index.html
narrow: true
title: Home
---

## Introduction

{% include components/intro.md %}

### Recent Posts

{% for project in site.projects limit:3 %}

-   [{{ project.title }}]({{ site.baseurl }}{{ project.url }})
    {% endfor %}

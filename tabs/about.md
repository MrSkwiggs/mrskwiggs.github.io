---
title: About
---

## 
<!-- My name's Dorian. I'm a belgian dude currently livin' the life as an iOS Developer in Amsterdam. -->
Yep, that's my very own website.

## Personal Projects
While being an iOS developer by day, I've also got some spare to work on some other projects. You'll find some below :)

{% for project in site.data.projects %}
{% include personal-project.html project=project %}
{% endfor %}

## Professional Experience


### Acknowledgments
This site is running on Github Page and is written with Jekyll.

[Legal]({% link tabs/acknowledgments.md %})

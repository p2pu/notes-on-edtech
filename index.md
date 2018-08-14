---
title: Notes on EdTech
layout: page
---

As part of what we do at P2PU, we often look at tools and resources for online learning. And as time goes, we sometimes forget what we've thought about it in the past. This site's purpose is to document our notes of the different tools. Please bear in mind that we look at things from our perspective of what would be useful to us and our community. Nothing here implies endorsement or dissuasion.

{% assign sortedNotes = site.notes | sort: 'index' %}
{% for notes in sortedNotes %}
  {{ notes.title }} notes on {{ notes.date|date:"%Y-%m-%d" }}
{% endfor %}



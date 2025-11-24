---
title: Historiography Podcasts
layout: base
date: 2025-11-24
cards: 
  - title: My First Podcast
    author: 664 Student
    thumbnail: /assets/images/Johann.jpg
    summary: This is my first episode summary. Delicious!
    audio: /assets/audio/episode1.mp4
  - title: Second Episode
    author: 664 Student
    thumbnail: /assets/images/second.jpg
    summary: Second podcast summary.
    audio: /assets/audio/episode2.mp4

---

# Advanced Historiography Podcasts

{% assign stacked_cards = page.cards %}

{% include card-stack.html cards = stacked_cards %}
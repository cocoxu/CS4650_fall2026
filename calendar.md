---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

**A tentative plan for the schedule (topics, deadlines, etc.) is available [here](https://docs.google.com/spreadsheets/d/1oQO5pFEWfOYj0n64h4IYo-EwjWFrEql53dck1TA8Jdo/edit?usp=sharing).**

CS 4650 covers the foundations of **Deep Learning for Natural Language Processing**, including mathematical foundations, neural networks, classic algorithms such as Viterbi, the origins of language modeling development, and evaluation methods such as F1 and MT metrics.

For more cutting-edge LLM topics, we have developed a dedicated course, CS 7652, which we recommend taking after CS 4650.

{% for module in site.modules %}
{{ module }}
{% endfor %}

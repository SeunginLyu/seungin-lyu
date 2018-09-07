---
title: Agent-Based Simulation of State Formation and Wars
layout: post
date: 2018-09-07 18:22:00 +0000
comments: true

---
This post is part of a report I wrote for Complexity Science course offered by Professor Allen Downey at Olin College of Engineering. Full report is available here on [Github.](https://github.com/CleanestMink126/Power-Laws-and-Wars/blob/master/reports/final_report.md)

### Abstract

Lewis Richardson, in his post-WWII paper in 1945, reported that the severity of wars follows a power law distribution \[3\]. Almost 70 years later, we find the exact reasons behind this observation still not well understood.
Cederman tackles the problem with an agent based model and replicated the power law distribution first reported by Richardson \[1\]. Inspired my Cederman's agent based model, we design and implement a similar model to discover whether it is sufficient to reproduce the same power-law graph with different key concepts including sigmoid function based declaration of wars and resource-based decisions to wage war. Our model produces either a log-normal or log-log distribution depending on the given parameters. We illustrate that the tuning the <i>advantage</i> threshold that affects the probability of attacking yields a log-log distribution. Thus we conclude that the conditions deciding when a country attacks contribute to the power-law distribution of wars.
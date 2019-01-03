---
title: Simulation of Epidemic Spreading in Scale-free Networks
layout: single
date: 2018-09-07 18:20:47 +0000
comments: true

---
This post is part of a report I wrote for Complexity Science course offered by Professor Allen Downey at Olin College of Engineering. Full report is available here on [Github.](https://github.com/SeunginLyu/EpidemicSpreading/blob/master/reports/final_report.md)

### Abstract

How do viruses in scale-free networks spread? What is the probability that a strain of virus survives over a period time? We answer these questions by replicating an experiment by Pastor-Satorras and Vespignani \[1\] which involves running the susceptible-infected-susceptible (SIS) model on Barabasi and Albert's (BA) power law graphs. We apply their methodology to a Facebook dataset \[4\] to further explore their model on a real-world network. We show that viruses with any spreading rate reach a steady state of prevalence of _ρ \~ exp(-C/λ)_ on scale-free networks. We conclude that scale-free networks are prone to epidemic spreading regardless of the spreading rate because there exists a finite prevalence for all network sizes, but the prevalence is kept low for a wide range of spreading rates because the prevalence decays exponentially as the spreading rate increases.

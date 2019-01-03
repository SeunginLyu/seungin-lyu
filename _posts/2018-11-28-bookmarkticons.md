---
title: Bookmarkticons
layout: single
date: 2018-11-28 04:56:31 +0000
comments: false

---
I have been working on a program that generates "bookmarkticons" based on the bookmarks text the user provides. For the first pass prototype, I've implemented an algorithm that overlays various favicon images using a SHA hash along with a simple modulus algorithm. This first pass model was heavily inspired and based on the "Robohash" code ([https://robohash.org/](https://robohash.org/ "https://robohash.org/")). I'm thinking of using the Kaggle database of favicon for the next version. ([https://www.kaggle.com/colinmorris/favicons](https://www.kaggle.com/colinmorris/favicons "https://www.kaggle.com/colinmorris/favicons")). The most challenging question I haven't been able to answer myself is, "What form should I receive the bookmarks? Just receiving texts feels super boring at this point.

![](/uploads/bookmarkticon.gif)

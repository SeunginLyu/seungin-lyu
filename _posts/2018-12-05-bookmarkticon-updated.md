---
title: Bookmarkticon Updated!
layout: post
date: 2018-12-05 00:21:57 +0000
comments: false

---
Here are some of the response I got from the previous feedback session.

* What is the message? Is this just an amalgamation of a person as an icon based on their bookmarks?
* It feels random and tangential to the bookmarks that got fed into the algorithm because the hash is randomly choosing favicons that aren't relevant to the bookmarks.
* There's still something "vague" about this project.

I thought about these points and came to the conclusion that I share the same feelings about my own work. I identified the "randomness" as the main reason why the bookmarkticons felt distant from my original idea of creating identifications for individuals. My outcomes were so too far way from serving as representations of any sort because they lacked a sense of connection. Without me explaining in meticulous detail how exactly the bookmarkticons were formed, the audience was generally confused of how the input bookmarks had anything to do with the final outcome. To resolve the issue, I rewrote the entire script so that when the user feeds a bookmarks HTML file to my python script, it crawls all the favicons from the web, then choose 64 images from the crawled images using the SHA512 hashing to make a final pixelated bookmarkticon. Below are some examples I've created for my own bookmarks and that of my friends who willingly shared theirs to generate bookmarkticons.

 
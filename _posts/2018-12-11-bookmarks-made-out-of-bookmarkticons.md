---
title: "Bookmarks\U0001F516 made out of Bookmarkticons"
layout: post
date: 2018-12-11 04:06:17 +0000
comments: true

---
My hunch for this project was bookmarks. Not the bookmarks we use to indicate the last page you read on a paper book but those that the list of shortcuts to websites on our web browsers. I have always been fascinated by the design efforts that go into creating favicons, and I envisioned an algorithm that would turn a person's bookmarks into a QR code / Identicon (from Github) looking images from a collage of favicons that are relevant to that specific person's bookmarks export. 

I wanted to do this project because random hash images like QR-Code and Identicons lack human personalities in that they do not encapsulate any personal traits, unique aspects, or interesting facts about the person they identify. I wanted to create an image that somewhat encapsulates the sensitive and subtle implication of bookmarks as a dataset because they tell a story about people's interests, internet habits, life-styles, and even sometimes more private information like political opinions. What's even more interesting is that people rarely get to see what other people have on their bookmarks list. What if people can share their bookmarks? What if they can do so without getting concerned about their privacy? What if we can build a culture and community around sharing bookmarks, as if they were holiday gifts?

I came up with my own answers to these above questions by writing a python script that receives a bookmarks html export file (from any browser including Chrome, Firefox, IE but only tested on Chrome) that generates images so called Bookmarkticons. [Here](https://github.com/SeunginLyu/Bookmarkticon)'s the code if you want to create your own bookmarkticons without sharing them with me. Here's how the script roughly works. 

1. Opens the html file
2. Download favicons for each URL included in the bookmarks export (this takes about 3\~5 minutes)
3. Select 64 favicons based on the name of the html file you provided  (seungin.html / seungin_lyu.html will generate different looking images even with the exact same list of websites).
4. 64 favicons get pasted next to each other into a square image, then the square image is pixelated.
5. The final output is saved!

For my final piece, I ended up crafting actual "book"marks 🔖🔖 (with origami). The most challenging part of this project was deciding on the "form" to in which to present these Bookmarticons. I was sold on this idea that popped-up in a feedback session. While this is a fun pun to play, I particularly felt in love with this specific form because it naturally enables me to share this concept of Bookmarkticons with my friends. I actually ended up giving one to my friend as a gift in return for his help with this project. It's also an interesting digital-to-analog transformation that always evokes subtle and strange emotions.

I learned that iteration is the key to really solidifying a hunch into a concrete project, and outside perspectives are always helpful. I'm definetely going to revisit this project later to polish it and make it available for a broader group of people and potentially build a community around it! (But it's a lot of dev hours to invest, so I'm holding onto it for now).

![](/uploads/IMG_3734.png)![](/uploads/IMG_3736.png)![](/uploads/IMG_3738.png)![](/uploads/IMG_3739.png)![](/uploads/IMG_3742.png)
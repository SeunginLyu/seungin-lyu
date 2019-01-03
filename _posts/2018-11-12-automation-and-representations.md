---
title: 'Algorithmic Identification : Bookmarks and Identicon..?'
layout: single
date: 2018-11-12 01:11:54 +0000
comments: false

---
* Upturn's [_Automation & The Quantified Society_](https://mimionuoha.github.io/classmaterials/upturn-abridged.pdf)
* [The odd reality of life under China's all-seeing credit score system](https://www.wired.co.uk/article/china-social-credit)
* [How the QR code conquered China](https://www.abacusnews.com/who-what/how-qr-code-conquered-china/article/2136537)

After reading these articles, I kept asking myself

> "What does it mean to use personal data to create a unique representative mapping of individuals?"

If we think about China's all-seeing social credit score system, we could abstract the system down to a simple function that takes a sequence of human behaviors and outputs a number after going through its internal algorithm.

For example,

    Input :
    {behavior:"cheated in game",time:"09/10/18"},
    {behavior:"harmed two neighbors",time:"09/10/18"},
    {behavior:"earned $100",time:"09/10/18"},
    {behavior:"protested against government",time:"09/10/18"},
    {behavior:"destroyed public property",time:"09/10/18"},

    Output : 123

So this is a mapping from a sequence of behaviors to a credit score. In the end, we are left with no details but with an abstraction of data that can't be reversed back to its original form. (X -> Y is possible, but Y->X is impossible even if we know the internal algorithm!)

The QR code is also a type of abstraction and a mapping of personal information (account number, or ID number) to a representation (QR Code). It's interesting that QR code serves as a means of identification that people feel more comfortable sharing with strangers because the private personal data is encapsulated in the representation.

I feel motivated to dig deeper into this notion of creating identification from personal data and the subtle implications behind this idea.

**Bookmarks** (for internet browsing) interest me because they form a unique collection of an individual's interests, history, and life style. I think of them as our web finger prints that might potentially serve as an identification when abstracted. They are even more interesting because they are super **private. (So the main challenge would be.. how do I collect people's bookmarks?)** So I did a little bit of hunch hunting.

![](/uploads/IMG_3596.png)

I arrived at a potential idea of converting raw bookmarks texts into Identicons, just like the default profile image we see on services like Github and Wordpress. Below are some links to websites that I found helpful brainstorming ideas for bookmarks and Identicons.

* [https://blog.github.com/2013-08-14-identicons/](https://blog.github.com/2013-08-14-identicons/ "Github Identicons")
* [https://barro.github.io/2018/02/avatars-identicons-and-hash-visualization/](https://barro.github.io/2018/02/avatars-identicons-and-hash-visualization/ "https://barro.github.io/2018/02/avatars-identicons-and-hash-visualization/")
* [https://www.npmjs.com/package/identicon-github](https://www.npmjs.com/package/identicon-github "https://www.npmjs.com/package/identicon-github")
* [https://blog.byndyusoft.com/generative-avatars-16bdb15f872d](https://blog.byndyusoft.com/generative-avatars-16bdb15f872d "https://blog.byndyusoft.com/generative-avatars-16bdb15f872d")
* [https://en.wikipedia.org/wiki/Identicon](https://en.wikipedia.org/wiki/Identicon "https://en.wikipedia.org/wiki/Identicon")
* [https://github.com/donpark/identicon](https://github.com/donpark/identicon "https://github.com/donpark/identicon")
* [https://blog.docuverse.com/tag/identicon/](https://blog.docuverse.com/tag/identicon/ "https://blog.docuverse.com/tag/identicon/")
* [https://haacked.com/archive/2007/01/22/Identicons_as_Visual_Fingerprints.aspx/](https://haacked.com/archive/2007/01/22/Identicons_as_Visual_Fingerprints.aspx/ "https://haacked.com/archive/2007/01/22/Identicons_as_Visual_Fingerprints.aspx/")
* [https://github.com/stewartlord/identicon.js/tree/master](https://github.com/stewartlord/identicon.js/tree/master "https://github.com/stewartlord/identicon.js/tree/master")

While I'm left with a lot more exploration to further dive into this topic, I'm looking forward to transformation of bookmarks to Identicons!

![](http://media.rehansaeed.com/rehansaeed/2014/11/Favicons.png)

![](https://cdn-images-1.medium.com/max/2000/1*kRmQXPKUTi9fOzWQViOozQ.png)I'm looking for teammates and please shoot me an email (slyu@olin.edu) if you are interested in this idea!

**Further things to think about** :

* What algorithm am I going to use as the "hash" function?
* What form of bookmarks data am I going to use? (Favicon images, bookmarks html export, raw texts, titles)
* What context and form should I provide to the audience?
* What style makes sense?
* How am I going to gather bookmark data? (Survey? Ask friends? Helpme email?)

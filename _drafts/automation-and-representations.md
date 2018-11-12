---
title: 'Algorithmic Identification : Bookmarks and Identicon..?'
layout: post
date: 2018-11-12 01:11:54 +0000
comments: false

---

* Upturn's [_Automation & The Quantified Society_](https://mimionuoha.github.io/classmaterials/upturn-abridged.pdf)
* [The odd reality of life under China's all-seeing credit score system](https://www.wired.co.uk/article/china-social-credit)
* [How the QR code conquered China](https://www.abacusnews.com/who-what/how-qr-code-conquered-china/article/2136537)

After reading these articles, I kept asking myself

> "What does it mean to use data about individuals to create a unique representative mapping of them?"

If we think about China's all-seeing social credit score system, we could abstract the system down to a simple function that takes a sequence of human behaviors and outputs a number after going through its internal algorithm. 

For example, 

    Input : {
    			{behavior:"cheated in game",time:"09/10/18"}
                {behavior:"harmed two neighbors",time:"09/10/18"}
                {behavior:"earned $100",time:"09/10/18"}
                {behavior:"protested against government",time:"09/10/18"}
                {behavior:"destroyed public property",time:"09/10/18"}
    		}
     Output : 123
     

So this is a mapping from a sequence of behaviors to a credit score. In the end, we are left with no details but with an abstraction of data that can't be reversed back to its original form. (X -> Y is possible, but Y->X is impossible even if we know the internal algorithm!)

Similarly, 
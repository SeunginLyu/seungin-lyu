---
layout: single
title: One out of ten senior Americans don’t use the internet
comments: true
undefined: ''

---
In my previous [blog post](https://seungin-lyu.com/one-third-of-senior-americans-don-t-use-computers/), I wrote that one-third of senior Americans don’t use computers in 2020. This time I look at how many hours Americans spend on the internet. It appears that roughly one out of ten senior Americans don’t use the internet today.

I recall making an old grandma smile by teaching her how to send Facebook messages to her grandchild. She had heard of messengers available online, but she also told me that she doesn’t quite “get the internet” and never had used it. This incident led me to wonder—roughly what fraction of old people in the US never use the internet?

Let’s take a look at the data to answer this question. [The General Social Survey](https://gssdataexplorer.norc.org/variables/2384/vshow) (GSS) asked 62,466 people,  and we have a total of 11,119 valid responses ranging from 0 hours to 184 hours, between 2000 and 2018.

“Not counting email, about how many hours per week do you use the Web? (Include time you spend visiting regular web sites and time spent using interactive Internet services like chat rooms, Usenet groups, discussion forums, bulletin  boards, and the like)”

This question explicitly excludes email usage from the internet hours. The results might be different without this specification, but data on internet services like regular websites, chatrooms, discussion forums are still relevant to my question.

To separate the seniors from the younger population, I categorize the respondents into four age groups : young adults (18-29), adults (30-44), old adults(45-59), and senior adults (60+). I choose the age ranges for these groups so that there are roughly the same number of respondents in each group.

For Figure 1, I defined a respondent who spends 0 hours per week as ‘not using the internet’. In other words, a respondent who answered greater than or equal to 1 hour of weekly internet usage is considered ‘using the internet’.

![](/uploads/fig1.png)  
_Figure 1. Fractions of people “using the internet” by age group over the past two decades. Each dot represents the fraction of the respondents using the internet each year for the age group of the corresponding color. The lines are drawn using linear regression._

I have a few remarks from Figure 1:

* The fraction of people using the internet has consistently increased for all age groups from 2000 to 2006. But afterwards, the rate of increase leveled off for all of them.
* Old adults between age 45 and 59 have fewer people using the internet than younger adults, but the fraction is still higher than that of the senior adults.
* Since 2006, the fraction of senior Americans using the internet has stayed around 85%, which leaves 15% of them not using the internet.

_![](/uploads/fig2.png)  
Figure 2. Median of weekly internet hours by age group over the past two decades. Each dot represents the median internet hours of the respondents each year for the age group of the corresponding color. The lines are drawn using linear regression._

I have a few remarks from Figure 2:

* Over the past two decades, the median weekly internet hours increased for all age groups. In 2018, young adults spend roughly about 2 hours on the internet **_per day_**, a huge increase from 2 hours **_per week_** back in 2000.
* Over the past two decades, the median of weekly internet hours increased the most for young adults and least for senior adults.

So what’s keeping 15% of our senior citizens away from the internet?

I don’t have an answer, but I have some questions.

Do seniors not have adequate access to education opportunities that could potentially facilitate more internet use? How does income level relate to internet hours among seniors?

Lastly, how could we further increase usage of the internet for the older population?  
While some might argue not everyone needs the internet, the COVID-19 crisis has demonstrated that online services serve as great alternatives to many essential services. At this challenging time, 15% of senior Americans who don’t use the internet still need to :

* (physically) show up to a bank to pay their bills.  
  The same task could be easily done virtually through online bank services
* (physically) go to grocery stores.  
  Online grocery services could greatly reduce the number of visits to physical grocery stores.

Given that senior Americans are the age group with the highest mortality rate for COVID-19, the fact that 15% of senior Ameircans don’t use the internet puts them at higher risk. So I argue that further promoting internet usage among senior Americans is desirable.

In short, people from all age groups are spending more time using the internet. Nonetheless, I see an opportunity to further introduce it for senior Americans who just “don’t get the internet”.

_My Google Colab_ [_notebook_](https://colab.research.google.com/drive/1lCQK3mWuIIztVLC9Q_Cw-M3DyUOEjh3h?usp=sharing) _is available under MIT license._
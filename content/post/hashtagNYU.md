---
title: "hashtagNYU"
date: 2018-11-09T10:35:35-05:00
description: "hashtagNYU is a web-app for students at New York University to see NYU communities at Twitter. I've wanted to see how and what people talk about NYU on Twitter. But, I found it hard to find it at once. So hashtagNYU was created to show the contents of Tweets regarding NYU and show the stastics regarding NYU tweets."
categories: ["WebApp","React","Django"]
featuredImage: "img/hashtagNYU.jpg"
dropCap: true
displayInMenu: false
displayInList: true
draft: false
---

[GitHub repo](https://github.com/gpDA/hashtagNYU)
---

OBJECTIVES
---
hashtagNYU is a web-app for students at New York University to see NYU communities at Twitter. I've wanted to see how and what people talk about NYU on Twitter. But, I found it hard to find it at once. So hashtagNYU was created to show the contents of Tweets regarding NYU and show the stastics regarding NYU tweets such as

* which school has posted the most Tweets with its school names
* which language NYU tweets has been posted most
* The distribution of time that tweets regarding NYU has been posted (I get the data of 3 months from (September 2017 - December 2017)

In hashtagNYU. I decide to get the data using Twitter API. I get the contents of #(hashtag) NYU by 15 metadatas such as the contents of tweet itself, the username of the creator, posting date, the number of retweets and favorites, and images of user profile and user banner. Then, I render those contents from the database in the frontend.

I request #NYU and #(hashtag) of NYU schools such as Stern / Courant ... using Tweepy. To request to Twitter API, I made a Twitter developmer account and authenticate with the credentials. I request Twitter API in 3 different criteria 1) recency 2) popularity 3) proximity (geocode - within 1 km to Washington Square Park). Also, I use Memcached Middleware for a better user experience

It is my very first React / Django project to get hands dirty and learn by making projects. I spent 2 months from September 2017 - November 2017 (Fall semester of Senior Year)

SKILLS
---
* React.js
* css
* Twitter API
* Django
* DRF
* PostgreSQL
* Memcached
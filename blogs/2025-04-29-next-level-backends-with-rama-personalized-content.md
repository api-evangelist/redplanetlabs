---
title: "Next-level backends with Rama: personalized content moderation in 60 LOC"
url: "https://blog.redplanetlabs.com/2025/04/29/next-level-backends-with-rama-personalized-content-moderation-in-60-loc/?utm_source=rss&utm_medium=rss&utm_campaign=next-level-backends-with-rama-personalized-content-moderation-in-60-loc"
date: "2025-04-29"
author: "Nathan Marz"
feed_url: "https://blog.redplanetlabs.com/feed/"
---
Backend storage This declares the PState as a map of lists, with the keys being 64-bit user IDs and the list values being post data. The name of a PState always begins with $$ . For each user, it tracks their feed as a list of content.

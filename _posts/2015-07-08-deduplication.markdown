---
title: "De-Duplication"
layout: post
date: 2015-07-08 22:48
image: /assets/images/markdown.jpg
headerImage: false
tag:
- markdown
- components
- extra
projects: true
hidden: true
category: project
author: Yogendra Valani
description: "Saving over £125K per annum proud to be a part of the project from inception to delivery. We overcame many challenges such as integrating into a established legacy workflow."
# jemoji: '<img class="emoji" title=":ramen:" alt=":ramen:" src="https://assets.github.com/images/icons/emoji/unicode/1f35c.png" height="20" width="20" align="absmiddle">'
---

#Company Background

Gorkana prides itself on being a premium media service provider to the PR industry. For Gorkanas clients who may want to plan or gain insight into their (or even a competitors) brand reputation or ad campaign on a global scale. Content from all major and regional publications, news articles, blogs, radio, tv and many other content types are ingested, filtered and analyzed. With clients in the PR industry to companies wanting to track news articles in the world media. The 'premium' is that every article we deliver to you has been read and checked by a human. With electronic content massively scaling the content processed, technology is relied upon to ensure only the most likely articles are read by our human analysts.

#What made this project successful.

As team lead it was my responsibility to ensure we delivered what was required. The application scaled beyond expectations and maintaince costs have been minimal.

#What challenges did we face

 Introduce the program into a workflow with legacy apps. Learning from previous developers who tried to integrate their mlr app into this workflow, added 6months of further work. Proving the topic cluster algorithm could be used for deduplication. I had a couple of weeks to prototype the algorithm. Created an mvc app,

 1. Using a sample set of articles users had to said if the articles were duplicates or not.
 2. A playground where production staff to copy two articles into text boxes and select if the articles were duplicates. There answers were recorded and compared to the algorithm. We determined from this that setting 95% threshold we would have a 1% error rate. Note: Two weeks after full migration of our app the threshold was dropped to 90%. Risks delaying production for anything more than 15 minutes Socially sensitive: the application caused many production readers to worry about their jobs. Hence there was resistance and very little feedback.

---
layout: page
title: Social influence in matters of taste
tagline: Brief overview
description: LMU Hiwi project page
---

![Image of social network](\assets\influence_vs_actual.png)

Here are two networks drawn using potential versus actual influence
in wine recommendation networks. We have 14 expert critics and
121 amateurs. The expert data has been scraped from bordoverview, and
amateur from vivino.com. In total, these 135 raters have rated a minimum
of 50 and a maximum of 1176 wines out of a total of 1978 wines. These
span multiple labels and vintages from the Bordeaux region in France.

We define potential influence network as the social network spanned by 
k-nn by calculating how much a rater is consulted by its nearest neighbours.
This is contrasted by how much influence is actually wielded by a rater r,
dependent upon the number of times a neighbour looks at r for predictions.

Here is another iteration of this work, this time using movie data.

![Image of movie social network](\assets\movies_nw.png)

The dissimilarities between these two networks and more is the subject of
ongoing work at the LMU, in the Crowd Cognition lab.
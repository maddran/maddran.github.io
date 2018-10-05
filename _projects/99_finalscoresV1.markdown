---
layout: page
title: NHL Final Scores V1
description: Visualizing the final score of NHL games
img: /assets/img/fsV1.jpg
---
<div class="note">
  <p><strong>Note 1: </strong> if you're on mobile, go landscape to view the whole plot!<br/><strong>Note 2: </strong> hover (or click) on any data point to view details</p>
</div>
<object class="heatmap" data="../html/scores-heatmap.html"></object>
### Background
It was the summer of 2018, I had just learned how to efficiently wrangle a vast amount of data from the [NHL's statistics portal](http://www.nhl.com/stats/) (see this blog post for more details). In an effort to apply some newly learned Python skills, I started several projects related to NHL stats. This was the first of these projects to reach anything resembling a finished product.

I set out to answer the question: **What are the most common final scores in NHL history?** 

However, that wouldn't make for a very interesting visualization. After much experimentation, I eventually chose to plot the distribution of final scores, split by home vs. away in a heat map.




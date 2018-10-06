---
layout: page
title: NHL Final Scores V1
description: Visualizing the final score of NHL regular season games
img: /assets/img/fsV1.JPG
---
<div class="note">
  <p><strong>Notes:</strong> <br/> 
	- If you're on mobile, go landscape to view the whole plot!<br/> 
	- Hover (or click) on any data point to view details</p>
</div>
<object class="heatmap" data="../html/scores-heatmap.html"></object>
### Background
It was the summer of 2018, I had just learned how to efficiently wrangle a vast amount of data from the [NHL's statistics portal](http://www.nhl.com/stats/) (see this blog post for more details). In an effort to apply some newly learned Python skills, I started several projects related to NHL stats. This was the first of these projects to reach anything resembling a finished product.

I set out to answer the question: **What are the most common final scores in NHL history?** 

Well, the the answer is 3-2 for the home team and 3-2 for the away team; however, that wouldn't make for a very interesting visualization. So, after much experimentation, I chose to plot the distribution of final scores, split by home  in a heat map.
### Tools and Platforms
* Data collection and analysis - Python 3.6 and Jupyter notebooks
* Visualization - [Plotly for Python](https://plot.ly/python/)

### Future iterations
The learning curve has been rather steep for this 
* More interactivity!
	* Add ability to filter by team / final score
* More data:
	* Add goal differentials



---
layout: project
type: project
image: images/election2016image.jpg
title: Data Analysis on Election 2016
permalink: projects/vacay
# All dates must be YYYY-MM-DD format!
date: 2016-12-19
labels:
  - python
  - numpy
  - pandas
summary: The analysis is done on the donations collected by <www.fec.gov> to Donald Trump and Hillary Clinton.
---

Data Analysis on 2016 Election between Donald Trump and Hillary Clinton. The purpose of this project is to see if the amount of donors to donate to the candidates can affect directly their chances of winning the heart of American people, and hence, the Election.

The graph below illustrates the amount of donors for Hillary Clinton is much greater than Trump's. 

![cc](https://cloud.githubusercontent.com/assets/21114221/23250615/fca3af9e-f94d-11e6-88ac-f158fe55c624.png)


If the hypothesis is true, Hillary Clinton should have a big lead in winning Trump and therefore win the election easily. 

However, this is not the case. If we look at the graph at below, which is located at Out[26] in the code, we can notice a different trend.

![ee](https://cloud.githubusercontent.com/assets/21114221/23250700/5f385c0e-f94e-11e6-9859-3d0613a1da47.png)

##### Up means people favor Clinton more, down means people favor Trump more.

As the date of the General Election gets closer, Clinton starts to lose her favorbility among the American people. The reason why this happened can be left for others to discuss, the fact of the matter is: the probability of her losing the election increases each day closer to the Election day. Therefore, we can conclude that the amount of donors being donated to a candidate does not affect directly the chances of winning the Election. 

The source of these data are taken from [here](http://www.fec.gov/data/CandidateSummary.do?format=html&election_yr=2016)

You can learn more at <https://github.com/thinhtedlam/Election-2016-Data-Analysis>

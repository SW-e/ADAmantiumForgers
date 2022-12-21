---
layout: page
title: News & Politics on Youtube: does it reflect the overall polarization in the US political scene?
subtitle: A study of user behaviour and channels communities
cover-img: /assets/img/flag.png
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [books, test]
---

## Introduction

In 2017, with the arrival in power of Donald Trump as president of the United States, the American political world quickly split between the pro and anti-Trump. According to a [study][1] lead by Jesse M. Shapiro, Brown University, this polarization began in the late 1990s and early 2000s and has been only increasing since, promoted by the detrimental properties of the US voting system that incentivize people to become radical. This polarization is also reflected online: according to a [study][2] on Facebook lead by to Brazilian researcher, the polarization one year after the 2017 election can be pictured on the figure below. Can the same effect be measured on YouTube communities ? In this data story, we will analyze the profiles of political communities on YouTube.

## YouTube is more ubiquitous than you think

Donner des data sur YouTube:
- autant de vues sur YT que de recherches sur Google
- proportion de gens qui regardent YT
- YT is used more and more to get news (even more for young generations) and unlike traditional medias, information is much less controlled
- Algorithm that promotes content that works and that might enclose people in filter bubbles



## Research Question

Talk about dataset
 
From milestone 2:

*   Can we identify communities inside the main US News&Politics channels ? Is there a clear left-right polarization or is the polarization independent of classical political party confrontation ?
*   What is the distribution of users polarization? Is it Gaussian? How many very extreme users do we see? For this purpose, we will assign a p-score (polarization or political score) to users
*   Based on the communities identified, can we describe political orientation of audience of non-News&Politics channels ? Study a few particular «neutral» channels (ex : Education, Gaming, Comedy Channels ...) or marginal channels (Flat Earth Society) and analyze their audience and their links with news channels
*   How are main political events treated by channels in different communities ? Study various events by filtering by tags, descriptions or video titles that contains key words, for example "US Election", "Impeachment", "Hunter Biden", "Capitol".



<!--- <img src="images/fb_us_pol.png" alt="fb_us_pol" width="700" style="display: block; margin-left: auto;margin-right: auto"/> -->

<!--- *Complete disconnexion of political landscape. Pablo Ortellado and Marcio Moretto Ribeiro, CC BY* -->

* * *
## 


<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 80%;"
    src="images/category_evolution.png" 
    alt="tilte image">


<a href="https://www.statista.com/statistics/717651/most-popular-news-platforms/" rel="nofollow"><img src="https://www.statista.com/graphic/1/717651/most-popular-news-platforms.jpg" alt="Statistic: Most popular platforms for daily news consumption in the United States as of February 2022, by age group | Statista" style="width: 100%; height: auto !important; max-width:1000px;-ms-interpolation-mode: bicubic;"/></a><br />Find more statistics at  <a href="https://www.statista.com" rel="nofollow">Statista</a>


{% include /figures/overall_categories_evolution.html %}

{% include /figures/2019_category_evolution.html %}

## Importance of news & Politics Channels on Youtube

{% include /figures/news_pol_3pie_overview.html %}
* * *
## Polatization

{% include /figures/heatmap_comunity_w_hover.html %}



```python
1 + 1 # Adding two numbers
```

## Polatization

{% include /figures/heatmap_comunity_w_hover.html %}


* * *
## Polarization of Youtube users

{% include /figures/p-score.html %}



[1]: https://www.nber.org/papers/w2666
[2]: https://theconversation.com/mapping-brazils-political-polarization-online-96434

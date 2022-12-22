---
layout: page
title: News and Politics on Youtube - Does it reflect the overall polarization in the US political scene?
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

The way of consuming the news has not stopped evolving over time. With the invention of the printing press, the world of information has been considerably changed. Then the news, transmitted more and more quickly with the development of the radio, the information has then changed its face to become more widespread and entertaining with the arrival of television in households. Finally, since the creation of the Internet, much information is transmitted through this channel. Today, about 40% of Americans get news online. It is even the number one source of information for the 18-45 age group. With the development of social networks, more and more people are getting information online and this also raises more and more questions.

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;git 
           width: 100%;"
    src="assets/img/main_sources_news_age.png" 
    alt="Sources of news on social media">


In the social media family, after Facebbok, YouTube is the second website where people get most of their news. In 2020, almost one in four people (23%) regulary get news on YouTube.


https://www.pewresearch.org/journalism/2021/01/12/news-use-across-social-media-platforms-in-2020/pj_2021-01-12_news-social-media_0-02/

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="assets/img/sources_of_news.png" 
    alt="Sources of news on social media">

## So, What is the Importance of News & Politics Channels on Youtube?

YouTube contains millions of videos, but you would maybe be surprise that the YouTube category with the most uploaded videos is the News & Politics one.
The category contains more than 18% of the videos contained in the dataset. However, when we are looking at the number of view or channels, the story changes drastically. The News & Politic channel represents less than 3% of the total numberof channel and count for only 1.74% of the total number of views.

{% include /figures/news_pol_3pie_overview.html %}


<a src="/_includes/figures/news_pol_3pie_overview.html" height="600px" width="100%"
>

<a src="assets/img/news_pol_3pie_overview.html" height="600px" width="100%"
>

<iframe src="/_includes/figures/news_pol_3pie_overview.html" height="600px" width="100%" style="border:none"></iframe>



## Where are we going?

Even if the number of views is incomparable with the most attractive categories such as entertainement and music, the News and Politics categories is pushing its way up. Over the last fwe year it can be observed that this is the category with the fastest growth.

{% include /figures/overall_categories_evolution.html %}

Moreover, during the first fews mont of 2019 it even manage to became the first category regarding the number of uploaded videos.

{% include /figures/2019_category_evolution.html %}




<iframe src="assets/img/news_pol_3pie_overview.html" height="600px" width="200%" style="border:none;"></iframe>



## What is the problem then?
You may think. "Well, Great!, One other great plaform to get great sources of information!". I hate to disapoint you but the reallity may be more complex...


 <div w3-include-html="assets/img/news_pol_3pie_overview.html"></div> 


<div src="assets/img/news_pol_3pie_overview.html"></div>

* * *
## Polatization

{% include /figures/heatmap_comunity_w_hover.html %}





## Polatization

{% include /figures/heatmap_comunity_w_hover.html %}


## Polarization of Youtube users

{% include /figures/p-score.html %}

## Communities analysis

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="assets/img/louvain_communities.png" 
    alt="...">
    
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="assets/img/indian_usa_channels.png" 
    alt="...">




[1]: https://www.nber.org/papers/w2666
[2]: https://theconversation.com/mapping-brazils-political-polarization-online-96434

---
title: 'Data visualisation'
subtitle: ''
summary: 
authors:
comments: true
tags:
- Fun
categories: []
date: "2016-04-20T00:00:00Z"
featured: false
draft: false



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  caption: ''
  focal_point: ""
  preview_only: false

---

I have a fascination in the different ways we can present data. Whilst academic data visualisation is often based on enabling readers to accurately perceive the absolute values of the data, and hence make inferences, there is obviously merit in making visualisations that are **aesthetically pleasing** and **engaging**. 

## On this page

[TidyTuesday](#tidytuesday)

[Football](#football-data)

----

## TidyTuesday :computer:

[TidyTuesday](https://github.com/rfordatascience/tidytuesday/blob/master/README.md) is a weekly project produced by the `R4DS Online Learning Community` where each week a raw datset, chart, or article is posted. One is then able to tidy and explore the data, and produce an informative(?) visualisation.

An important aspect of TidyTuesday is this, taken directly from the TidyTuesday website:

>We will have many sources of data and want to emphasize that no causation is implied. There are various moderating variables that affect all data, many of which might not have been captured in these datasets. As such, our guidelines are to use the data provided to practice your data tidying and plotting techniques. Participants are invited to consider for themselves what nuancing factors might underlie these relationships.

TidyTuesday is a bit of fun, and is often used to learn and improve R skills, data visualation techniques, and connect with the R community!

[My GitHub with all of my contributions](https://github.com/HudsonJamie/tidy_tuesday):

### [2021 week 17](https://github.com/HudsonJamie/tidy_tuesday/tree/main/2021/week_17) - Netflix Titles 📺

Netflix show data from Shivam Bansal (Kaggle)
![netflix_shows](https://github.com/HudsonJamie/tidy_tuesday/blob/main/2021/week_17/netflix21042021.png?raw=true)

### [2021 week 16](https://github.com/HudsonJamie/tidy_tuesday/tree/main/2021/week_16) - US Post Offices ✉️📪

US Post Office data from Blevins & Helbock, 2021, "US Post Offices", Harvard Dataverse
![us_post_offices](https://github.com/HudsonJamie/tidy_tuesday/blob/main/2021/week_16/us_post14042021.png?raw=true)

### [2021 week 15](https://github.com/HudsonJamie/tidy_tuesday/tree/main/2021/week_15/) - Deforestation 🌳🪵

Deforestation data from Our World in Data
![deforestation](https://github.com/HudsonJamie/tidy_tuesday/blob/main/2021/week_15/deforestation_06042021.png?raw=true)

----

### [2021 week 14](https://github.com/HudsonJamie/tidy_tuesday/tree/main/2021/week_14/) - Make up shades 💄

Makeup shades data from The Pudding | See original article [here](https://pudding.cool/2021/03/foundation-names/)
![makeup_shades](https://github.com/HudsonJamie/tidy_tuesday/blob/main/2021/week_14/makeup_shades_12042021.png?raw=true)

----

### [2021 week 13](https://github.com/HudsonJamie/tidy_tuesday/tree/main/2021/week_13/) - UN votes 🌐🌍

UN voting data from Harvard Dataverse
![UN vote](https://github.com/HudsonJamie/tidy_tuesday/blob/main/2021/week_13/un_votes25032021.png?raw=true)

----

### [2021 week 12](https://github.com/HudsonJamie/tidy_tuesday/tree/main/2021/week_12/) - Video Games 👾

Video game data from the video game distribution service Steam

![Steam_gaming](https://github.com/HudsonJamie/tidy_tuesday/blob/main/2021/week_12/steam_plot16032021.png?raw=true)

----

### [2021 week 11](/2021/week_11/) - Bechdel Test 🎥🙋‍♀️

The Bechdel test is a measure of the representation of women in fiction

![Bechdel Test](https://github.com/HudsonJamie/tidy_tuesday/blob/main/2021/week_11/bechdel_test_15032021.png?raw=true)

----

## Football data :soccer:

I have produced an R Shiny App with an updating 2020 / 2021 [Premier League Table](https://jamie-hudson.shinyapps.io/premier-league-table/)

It takes a while to load because it downloads the latest matchday results each time (I probably need to improve the script for this).

With this, you can view:

1) The Premier League Table at a set date (If you go to January 15th 2021, Man Utd are three points clear at the top!)

2) The Premier League Table between two dates - the media love to do this to see, for example, the table since Christmas or since a managerial sacking

3) A lineplot of the weekly league position for each team

4) A lineplot of the total number of points attained by each team, on a weekly basis. 

**Please note that I only have a free shinyapps account, so use is limited to 25 active hours per month**


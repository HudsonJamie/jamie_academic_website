---
title: Pokémon type charts
author: Jamie
date: '2021-10-22'
slug: []
categories:
  - data visualizations
  - rstats
tags:
  - data visualizations
  - ggplot2
  - rstats
subtitle: 'A quick visualisation of the different types per Pokémon region 👾'
summary: ''
authors: []
lastmod: '2021-10-22T21:25:43+01:00'
featured: no
draft: no
image:
  caption: ''
  focal_point: ''
  preview_only: yes
  
---

There is a plethora of Pokémon data visualisation online, with much providing informative insights on specific Pokémon stats (HP, Attack, Sp. Atk etc). I thought it would be interesting to visualise the different "type" that each Pokémon is.

I downloaded a dataset from [Kaggle](https://www.kaggle.com/maca11/all-pokemon-dataset) that contains the typing of each Pokémon (some Pokémon have two types), and used *{geom_tile}* to produce a tile representing each Pokémon, where the colour of the tile maps to each Pokémon's typing.

{{< figure src="./featured.png" title="" lightbox="true" >}}


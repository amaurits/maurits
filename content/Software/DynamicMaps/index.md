---
author: Maurits van der Veen
categories:
- gis
- dynamic charts
date: "2021-12-10"
draft: false
excerpt: "**Dynamic choropleth maps**\n\n

Dynamic charts and maps are great for displaying patterns over time. A key challenge with such charts and maps is to keep the mapping of values to colours constant over time. Most charting programs will automatically assign colours depending on the range and number of different values available. This is problematic when both of those factors vary over time, even though we want the colours representing a particular value or level to remain constant. I have added a feature to Jack McKew's excellent pandas-alive dynamic charting program to make this possible for choropleth maps, and provide a sample notebook applying this feature to an over-time mapping of Covid case- and death rates (using the _New York Times_ data)."
layout: single
links:
- icon: github
  icon_pack: fab
  name: "Github repository"
  url: https://github.com/amaurits/pandas_alive
subtitle: An extension to the pandas-alive software
title: Dynamic maps using pandas
---

The Github link is to the forked repository of pandas_alive. For the sample notebook, please contact me directly. 

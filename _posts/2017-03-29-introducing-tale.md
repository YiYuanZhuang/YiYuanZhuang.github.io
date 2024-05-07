---
layout: post
title:  " The Copenhagen House Price Puzzle: Uncovering Convenient Amenities "
author: "YiYuan, JiaNan, LingYu"
comments: true
tags: Tale
excerpt_separator: <!--more-->
sticky: true
hidden: true
date: 2024-05-07
---

In the old and modern city of Copenhagen, the secret of house prices is like a treasure hidden underneath the beautiful streets and canals. Our website takes you on a journey to unravel this mystery through cutting-edge data visualisation techniques. Our goal is to give you not only the information you need to find your future home, but also to enjoy the journey of discovery.

## The beginning of the story: the discovery of the problem
First, we invite you to explore two unique perspectives:
1. Graph of correlation coefficients between house prices and neighbourhood amenities: This graph will show the mysterious connection between the number of amenities per unit area and house prices in different areas. Which amenities really push up house prices? Which ones are unexpectedly unrelated to house prices? The story behind the data awaits your discovery.

<iframe src="https://YiYuanZhuang.github.io/social-data/assets/image/correlation_heatmap.html" width="100%" height="500" frameborder="0"></iframe>

FINDINGS: As you can see from the chart, the types of amenities that have a high correlation with house prices include metro stations (0.7), gyms (0.7), shops (0.66) and restaurants (0.63). This may indicate that house prices are higher in well-located and convenient areas. The abundance of commercial and leisure facilities has a significant impact on the attractiveness of the area in which one lives, which in turn drives up house prices. Comparatively, firms have the lowest correlation coefficient (0. 4), suggesting that the distribution of firms has less of a direct impact on house prices. While firms may bring economic activity and employment opportunities to the city, the distribution and type of firms has a relatively low direct impact on house prices, especially when compared to amenities that directly affect the quality of life of residents. This may be due to the fact that firms are often concentrated in commercial or industrial areas, which may be less attractive to live in than residential areas with good amenities.


2. Scatterplot of regional house prices against amenity scores: Conventional wisdom is that "the more amenities, the higher the house price", but our data paints a more complex picture when the correlation coefficients are used to calculate the amenity scores of different neighbourhoods in relation to house prices. This will challenge your expectations and provoke you to think outside the box.
   
<iframe src="https://YiYuanZhuang.github.io/social-data/assets/image//House_Scores_scatter.html" width="100%" height="500" frameborder="0"></iframe>

FINDINGS: It is clear from the scatterplot that there is a subtle relationship between house prices and amenity scores in each district:
 Overall, there is no clear linear relationship between scores (Scores) and house prices (Average House Price (DKK)). While Frederiksberg, the highest scoring district in the upper right corner of the chart, has the highest scores and the highest house prices, the other districts do not follow this principle.
 Other than that, the rest of the scatter takes on the shape of a crescent, which leads us to notice the two cusps:
 A (top left corner of the scatter): Gentofte and København, where house prices are in the TOP 3, but the amenities score is only about 20 out of 100.
 B (bottom right of the scatterplot): Rødovre and Herlev, with amenity scores in the TOP 3, but house prices only in the middle 30W (up to 600K)
 The emergence of these two extremes makes us wonder what is behind this phenomenon.
 There are many factors that influence house prices, such as population, socio-economics, city policies, and market supply and demand status. In this study, we introduced population and economy as auxiliary research in addition to the factor of city facilities.

## Deeper Exploration: Uncovering the Story Behind the Data
With a deeper understanding of the data, we took demographic and socio-economic data into consideration for further analysis.
3. Interactive Facilities Heat Map: With this heat map, you have the option to see the distribution of different types of facilities in the city. How does the concentration or dispersion of amenities actually affect property prices? Find out.

<iframe src="https://YiYuanZhuang.github.io/social-data/assets/image/heatmap.html" width="100%" height="500" frameborder="0"></iframe>

Number of amenities: Frederiksberg significantly has the most amenities, especially the railway station (172), which may be one of the reasons for its high house prices and high incomes. København (Copenhagen) also has a high concentration of amenities, especially restaurants (141) and the railway station (318), reflecting its status as the capital city's busyness and diversity. Areas with high facility densities not only have a high number of facilities, but also exhibit high economic dynamism. House prices and income levels are generally higher in these areas, showing that the diversity and quality of amenities has a direct impact on the quality of life of residents and the economic attractiveness of the region.
 Areas with high neighbourhood amenity scores and low house prices, such as Herlev have a significantly higher number of parks than other areas. This suggests that the government or community may have invested in more public facilities in these areas to improve residential attractiveness and enhance the surrounding natural environment.

<iframe src="https://YiYuanZhuang.github.io/social-data/assets/image/map.html" width="100%" height="500" frameborder="0"></iframe>

4. Bubble chart of personal economic status versus house prices: This bubble chart will take you through an economic understanding of the inconsistency between house prices and amenity scores. How do house prices move differently in areas with different levels of personal economic status?
 The bubble chart illustrates the relationship between population density (Density, vertical axis) and income level (Income, horizontal axis), and shows the average price of flats (Flat Average Price) in small and large colours. The scatter is small to large and coloured from yellow to purple, indicating that the average price of flats is low to high.
 At the top of the bubble chart are two dots: Frederiksberg and København have very high population density and low per capita income, and they also have in common high house prices, but Frederiksberg has the most comprehensive neighbourhood in the whole of the Copenhagen metropolitan area and København has København has relatively few. As the core of the Copenhagen Capital Region, København has taken on more commercial and administrative functions, which may result in a relative lack of amenities related to residents' lives (e.g. schools, hospitals). This may be due to the fact that more space within the area is utilised for commercial, industrial and administrative facilities rather than residential or community service facilities. The high population density and limited space keep house prices in København high, even if the per capita income is not as high as in Frederiksberg. The demand for housing due to high density pushes up house prices, and also increases the cost of living, potentially reducing living comfort.
 Eliminating these two extremes leads to a more general pattern: high neighbourhood amenity scores and low house prices correspond to areas with low per capita incomes and low populations (e.g., the two regions in Group B), and low neighbourhood amenity scores and high house prices correspond to areas with high per capita incomes and low populations (e.g., the two regions in Group A and Rudersdal and Hørsholm). It can be observed that there is no strong correlation between house prices and population size, but the high house prices in areas with low neighbourhood amenity scores may be due to high per capita incomes, and residents in high-income areas are able to afford higher house prices even if these areas do not have high amenity scores. Low house prices in areas with high neighbourhood amenity scores may be due to the limited purchasing power of residents with low per capita incomes, which affects the level of house prices. This is despite the fact that the government or community may have invested in more public amenities in these areas to increase the attractiveness of living there. This suggests that house prices are related to residents' ability to pay and demand, not just the number of amenities. [References Malpezzi, S. (1999). A Simple Error Correction Model of House Prices. Journal of Housing Economics, 8(1), 27-62.]

<iframe src="https://YiYuanZhuang.github.io/social-data/assets/image/House_economy_scatter.html" width="100%" height="500" frameborder="0"></iframe>

##  A personalised vision of the future: finding your ideal home
Here comes the best part! Through our interactive map game, you can not only give ratings based on your personal preferences for amenities, but you can also see the system's recommendations for where to live that are tailored to you. The game combines the last 20 years of home price data with future trend forecasts to help you make an informed decision.

Every step on this interactive, information-rich platform is full of discovery. We don't just provide data, we want to take you on an unforgettable digital adventure. Are you ready? Let's unlock the secrets of Copenhagen's property prices and find the home of your dreams! Click [finding your ideal home](https://lit-woodland-17019-4fe9595cf520.herokuapp.com/voila/render/interactive.ipynb?)



## Reference
1. Police Department Incident Reports. "[Police Department Incident Reports](https://data.sfgov.org/browse?category=Public+Safety)"
2. CBS News San Francisco. "[SFNext: Theft, Car Break-ins San Francisco](https://www.cbsnews.com/sanfrancisco/news/sfnext-theft-car-break-ins-san-francisco/?intcid=CNM-00-10abd1h)."
3. Valery Nechay Law. "[San Francisco Theft](https://valerynechaylaw.com/san-francisco-theft/)."
4. CBS News San Francisco. "[Walgreens Retail Theft, Shoplifting San Francisco Civic Center Caught on Camera](https://www.cbsnews.com/sanfrancisco/news/walgreens-retail-theft-shoplifting-san-francisco-civic-center-caught-on-camera/)."
5. The SF Standard. "[San Francisco Car Break-In: New Law to Close Loophole](https://sfstandard.com/2023/10/26/san-francisco-car-break-in-new-law-loophole/)."


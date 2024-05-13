---
layout: post
title:  " Copenhagen House Price Puzzle: Uncovering Surrounding Facilities "
author: "YiYuan, JiaNan, LingYu"
comments: true
tags: Tale
excerpt_separator: <!--more-->
sticky: true
hidden: true
date: 2024-05-07
---

In the old and modern city of Copenhagen, the secret of house prices is like a treasure hidden underneath the beautiful streets and canals. This article is a journey to unravel this mystery through cutting-edge data visualization techniques. We hope it can give you inspiration for finding your future home. Let‘s enjoy this journey!

## Dancing on the crescent moon
When you are looking for your ideal home in the Capital Region of Denmark (Region Hovedstaden), will you care about if it is close to Føtex or close to Metro? Are you curious about how much different facilities relate to house prices? This clear correlation coefficient graph (Figure 1)  will tell you the answer.

<iframe src="https://YiYuanZhuang.github.io/social-data/assets/image/correlation_heatmap.html" width="100%" height="500" frameborder="0"></iframe>

The above graph shows the mysterious connection between the number of facilities per unit area and house prices in the Capital Region of Denmark. Which facilities push up house prices? Which ones are unexpectedly unrelated to house prices? The story behind the data awaits your discovery.

As we can see from the chart, the types of facilities that have a high correlation with house prices include  (public transport) stations (0.7), gyms (0.7), shops (0.66), and restaurants (0.63). This may indicate that house prices are higher in well-located and prosperous areas. The abundance of commercial and leisure facilities has a significant impact on the attractiveness of living, which in turn drives up house prices. Comparatively, company(0.4) has the lowest correlation coefficient, showing that the distribution of companies has less impact on house prices, especially when compared to facilities that directly affect the quality of life, although they bring economic activity and employment opportunities to the city. This may be because companies are often concentrated in industrial areas, which may be less attractive to live in than residential areas.

If we score the facilities in each municipality according to the correlation coefficient in the above chart, will the housing prices with higher scores be higher? With this question in mind, we made a scatter plot(figure 2).

<iframe src="https://YiYuanZhuang.github.io/social-data/assets/image//House_Scores_scatter.html" width="100%" height="500" frameborder="0"></iframe>

This result may challenge your expectations, but it also inspires you to think outside the box. Overall, there is no clear linear relationship between scores (Scores) and house prices (Average House Price (DKK)). While Frederiksberg, the highest-scoring district in the upper right corner of the chart, has the highest scores and the highest house prices, the other districts do not follow this principle. Other than that, the rest of the scatter takes on the shape of a crescent, which leads us to notice the two groups: A (top left corner of the scatter): Gentofte and København, where house prices are in the TOP 3, but the amenities score is only about 20 out of 100. B (bottom right of the scatterplot): Rødovre and Herlev, with amenity scores in the TOP 3, but house prices only in the middle 300K (up to 600K).

The emergence of these two extremes makes us wonder what is behind this phenomenon. Many factors influence house prices, such as population, socio-economics, city policies, and market supply and demand status. In this study, we introduced population and economy as auxiliary research in addition to the factor of facilities.

## The beating of the earth

Apart from the number of facilities, does the concentration or dispersion of facilities affect housing prices? Let’s find out. You are welcome to select different facility types to see the changes in the heat map.

<iframe src="https://YiYuanZhuang.github.io/social-data/assets/image/heatmap.html" width="100%" height="500" frameborder="0"></iframe>

From the heat map, we can see, that Frederiksberg significantly has the most facilities, especially the railway station (172), which may be one of the reasons for its high house prices. København (Copenhagen) also has a high concentration of facilities, especially restaurants (141) and the public transport station (318), reflecting its status as the capital city's busyness and diversity. Municipalities with high facility densities not only have a high number of facilities but also exhibit high economic dynamism. House prices and income levels are generally higher in these areas, showing that the diversity and quality of facilities have a direct impact on the quality of life of residents and the economic attractiveness of the region. Municipalities with high facility scores and low house prices, such as Herlev have a significantly higher number of parks than other areas. This suggests that the government or community may have invested in more public facilities in these areas to improve residential attractiveness and enhance the surrounding natural environment.

The bubble chart below will help us understand the inconsistency between housing prices and facility scores from an economic perspective. How will housing prices differ in areas with different personal economic levels?

<iframe src="https://YiYuanZhuang.github.io/social-data/assets/image/House_economy_scatter.html" width="100%" height="500" frameborder="0"></iframe>

This bubble chart illustrates the relationship between population density, income level, and housing prices in various municipalities, with the size and color of each scatter point representing the average price of a flat, ranging from low (yellow) to high (purple).

Notably, Frederiksberg and København, two municipalities at the top of the chart, demonstrate high population densities paired with relatively low per capita incomes. Despite this, both exhibit high housing prices. Frederiksberg, known for its extensive facilities, ranks as the most comprehensive in terms of amenities within the Capital Region of Denmark. Conversely, København, despite its status as the core of the Capital Region, has fewer resident-focused facilities such as schools and hospitals. This is attributed to its significant commercial and administrative roles which demand more space, thus limiting areas available for residential and community services. Consequently, despite the lower per capita income, the intense demand due to high population density drives up housing prices in København.

When excluding these outliers, a general trend emerges: municipalities with high surrounding facility scores tend to have lower housing prices and lower per capita incomes, coupled with smaller populations (e.g., Group A municipalities). In contrast, areas like Rudersdal and Hørsholm (Group B), where surrounding facility scores are lower, see higher housing prices, which correlates with higher per capita incomes and smaller populations. This suggests that housing prices are more reflective of the residents' financial capacity and demand rather than solely on the availability of facilities.

This analysis indicates that while facilities play a role in residential attractiveness, the key drivers of housing prices in these regions are the residents’ income levels and the corresponding demand dynamics, rather than just the quantity of local facilities. Thus, housing affordability in high-facility areas may be constrained by the residents' lower income levels, whereas in wealthier areas, residents can sustain higher housing costs even with fewer facilities. This nuanced understanding aligns more clearly with economic principles of supply, demand, and purchasing power in residential real estate markets [1].

##  Looking to the future
Embark on a tailored journey to find your ideal home in Copenhagen through our interactive map game! By rating your preferences for amenities on a scale of 1, and clicking the "Start" button, you can explore how different amenities align with your lifestyle. 

[Start your adventure here](https://lit-woodland-17019-4fe9595cf520.herokuapp.com/voila/render/interactive.ipynb?)

The map dynamically displays the top three cities that best match your selected amenities scores. Additionally, a line chart visualizes the trends in housing prices over the past 20 years and projects future trends for the next five years, guiding you towards making an informed decision about your potential new home.

Our in-depth exploration into Copenhagen's housing market has revealed the multifaceted influences on house prices. Key factors such as population density, income levels, and government policies significantly impact housing costs, alongside the distribution of supporting facilities. Our findings debunk the simplistic view that more facilities automatically equate to higher house prices; instead, we have seen that socioeconomic conditions and market dynamics play crucial roles. For instance, areas like Frederiksberg and København, despite their high population densities and comprehensive facilities, maintain high housing prices due to strong demand from job seekers and families. Conversely, some regions with fewer amenities still attract high prices, likely driven by the affluent residents' demand for quality living environments.

This comprehensive analysis not only deepens the understanding of the complex mechanisms behind housing price formation but also empowers you to find a residence that suits your personal and financial preferences through interactive maps and data visualization tools. We aim to assist you in navigating Copenhagen's diverse housing market, ensuring you can find your dream home in this vibrant city. This journey, rich in data and insights, is designed to cater to anyone in search of a new home, providing valuable answers and guidance.


## Reference
1.  References Malpezzi, S. (1999). A Simple Error Correction Model of House Prices. Journal of Housing Economics, 8(1), 27-62.
2.  Miller, N. G., Peng, L., & Sklarz, M. A. (2011). House Prices and Economic Growth. The Journal of Real Estate Finance and Economics, 42(4). DOI: 10.1007/s11146-009-9197-8.

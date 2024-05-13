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

This bubble chart shows the relationship between population density and income level, using size and color to show the average price of a flat. The scatter points range from small to large and the colors range from yellow to purple, indicating that the average price of apartments ranges from low to high.

There are two points at the top of the bubble chart: Frederiksberg and København have extremely high population density and low per capita income. They also have a common feature that housing prices are very high, but Frederiksberg's surrounding facilities are the most comprehensive in the entire Capital Region of Denmark, while København's surrounding facilities are relatively few. As the core of the Capital Region, København has assumed more commercial and administrative functions, which may lead to a relative shortage of facilities related to residents' lives (such as schools and hospitals). This is because the space in the area is more used for commercial, industrial, and administrative facilities rather than residential or community service facilities. The high population density and limited space keep the housing prices in København high, even though the per capita income is not as high as Frederiksberg's. The housing demand brought by high density pushes up housing prices, while also increasing living costs.

After eliminating these two extreme values, a more general rule can be drawn: areas with high surrounding facility scores have low housing prices, corresponding to low per capita income and small population (such as the two municipalities in Group B), and areas with low surrounding facility scores have high housing prices, corresponding to high per capita income and small population (such as the two municipalities in Group A). It can be found that housing prices and population size are not strongly correlated, but the high housing prices in areas with low surrounding facility scores may be due to high per capita income. Residents in high-income areas can afford higher housing prices, even if the facility scores in these areas are not high. The low housing prices in areas with high surrounding facility scores may be due to the limited purchasing power of residents with low per capita income, which affects the housing price level. Although the government or community may have invested more public facilities in these areas to improve the attractiveness of living. This shows that housing prices are related to residents' ability to pay and demand, not just the number of facilities[1].

##  Looking to the future
After learning so much about housing prices and amenities, do you want to know how to match your tailored place to live? Welcome to the interactive map game! You can rate your preferences based on your personal preferences for amenities (out of 1), click the "Start" button, and see what happens.

Click [Start journey](https://lit-woodland-17019-4fe9595cf520.herokuapp.com/voila/render/interactive.ipynb?)

Congratulations, you have completed this exploration journey!

In this exploration of Copenhagen's house prices puzzle, we have delved into how different factors affect the city's house prices. From the distribution of supporting facilities to personal economic conditions, each chapter reveals the complex mechanism of house price formation. We found that although good facilities have a clear positive impact on increasing house prices, this is not the only factor. The population density, income level, and government policies of the area also play a key role.

Although there is no simple linear relationship between house prices and the number of surrounding facilities, our data visualization reveals that some areas with abundant facilities have low house prices. This shows that the number of facilities alone cannot fully predict the level of house prices. House prices are also affected by socioeconomic conditions and market supply and demand[2]. For example, in Frederiksberg and København, despite high per capita income and population density, house prices remain high, which may be partly because these areas have comprehensive facilities and attract a large number of job seekers and families. In addition, we also observed that some areas have unexpectedly high house prices despite low facility scores. This is related to residents' high income and demand for a high-quality living environment. This finding challenges the traditional view that more facilities lead to higher house prices.

Finally, our research not only provides an in-depth understanding of Copenhagen house prices but also enables you to find the ideal place to live according to your personal preferences through interactive maps and data games. Our work proves that the formation of housing prices is a complex process with multiple factors and multiple levels, which requires the comprehensive consideration of various social, economic, and geographical factors. In this final chapter, we summarize the previous findings and hope that through our analysis, we can help you better understand the dynamics of housing prices and find your dream home in this charming city of Copenhagen. This is a journey full of data and discovery, and we believe that everyone who is looking for a home can find their answers here.

Uncover the secrets: The map shows the top 3 cities with the recommended facilities scores based on your options, and the line chart shows the housing price trends in the area over the past 20 years, as well as the predicted trends for the next 5 years. I wish we could all find our dream home!

## Reference
1.  References Malpezzi, S. (1999). A Simple Error Correction Model of House Prices. Journal of Housing Economics, 8(1), 27-62.
2.  Miller, N. G., Peng, L., & Sklarz, M. A. (2011). House Prices and Economic Growth. The Journal of Real Estate Finance and Economics, 42(4). DOI: 10.1007/s11146-009-9197-8.

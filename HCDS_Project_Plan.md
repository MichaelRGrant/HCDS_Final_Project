## HCDS – Project Plan A3
### Michael Grant

#### Background

Organic foods have become increasingly popular in recent years. People are becoming more aware that the food they eat has a greater impact on their health, and there has been a growing movement to reduce the amount of chemicals that we ingest. First-world living has many perks, but the first-world cancer rates are much higher than anywhere else on the planet. One possible reason for this is the increase use of chemical pesticides on our food. Since the Green Revolution, conventional agriculture has relied heavily on the use of these chemicals. This did have the intended effect of increasing yields, but the long-term effects of ingesting these products is far more difficult to ascertain. 

The process to get a pesticide approved for agricultural use is much easier in terms of the amount of time it takes to determine that it has deleterious effects for humans. One agrochemical company that often takes the most heat, Monsanto, is responsible for the development of many now banned substances including dichloro-diphenyl-trichloroethane or DDT, 2-4 D an ingredient in the now infamous Agent Orange, a plant defoliating used in the Vietnam War, polychlorinated biphenyls or PCBs a now known carcinogen, and many more. As more of these chemicals are found to be extremely harmful, there is a greater desire for our food to be chemical free and hence the increase in demand for organic foods.

Organic foods are grown without the use of non-approved pesticides or fertilizers. Organic food is generally more difficult to produce on the same scale as conventional agriculture and the amount of loss to diseases is greater resulting in reduced overall yields (Yiridoe et al. 2005). This fact inevitably drives the cost up compared to conventionally grown varieties. Nevertheless, it seems that most consumers buy organic foods for reasons of food safety (Goldman & Clancy 1991; Jolly et al. 1989), knowing that pesticides were not present (Huang 1996; Hutchins & Greenhalgh 1997; Schifferstein & Ophuis 1998) or that the food just tastes better. 

These consumers understand that in order to get the things they want from their food, they will have to pay a premium. There is a large variation in what people are willing to spend to get these advantages. In the US Jolly et al. (1989) found that consumers were willing to pay a 37% price premium while in New York some consumers were willing to pay as much as 100% more (Goldman & Clancy 1991). Overall, Yiridoe et al. (2005) reported that consumers are willing to pay a 10 – 20% premium above the same food conventionally grown, with premiums above 20% showing a sharp decline in demand. 

#### Hypothesis/Interest in the Data

In this study, I wanted to investigate what the price difference was for vegetables, fruit, grains and some dairy and poultry products over time. My overarching hypothesis is that the price differential between organic and conventional products has decreased over time, and that it will not likely be greater than 20%. A qualitative observation I have is that a greater number of organic products are available, and people are buying more of those products. This leads me to believe that the premium on organic products is not greater than 20%, because according to the literature, above this point demand begins to plummet. Furthermore, I would like to investigate if demand for these products is increasing. By looking at the prices over time, this question can be answered. Overall, I wish to explore how the price of organic products changes throughout the year, if at all, what the price differential is on different products and how that has changed over time. It will also be interesting to identify which products have the highest premium on organic versions, and what the demand is like on those products.

#### Data and Analysis

The data I will be using originates from the United States Department of Agriculture’s (USDA) Agricultural Marketing Service (AMS). The data is separated into wholesale prices for fruits, vegetables and grains, in addition to first receiver prices for poultry and eggs. There is also data on sales volume of organic milk. 

The data is under the creative commons attribution license CC-BY, allowing for re-distribution and re-use of this work on the condition that the creator is appropriately credited. 

The data is currently in a number of excel files, and separated even further by sheets within those files. The form of the data does not yield easy analysis, and thus interested me because there is important information in this data, and it needs to be reformatted in order fully realize its value. The analysis that will be performed is mainly a visualization of the prices over time. I will also use a linear regression technique to determine change over time. Because of the size (small) and nature (mainly just prices) of this dataset, this approach will likely be sufficient. As I dive into the data further I may explore other options, but a simple analysis with a nice visualization is my end goal. 

The visualizations will be created using the R programming environment. I may include the use of Power BI if interactivity becomes necessary, but I expect that static visualizations should suffice. All data cleaning will be done in R.

The data consists of a comparison of the prices of various fruits, vegetables, grains and poultry and dairy products segmented by months. Depending on the dataset, the number of years varies. Some archived data goes back as far as 1995 but this is dependent on the vegetable type. The locations data was collected also varies including Boston, San Francisco, and Atlanta. I see the discontinuity of the data as an advantage in order to get a better national picture of organic food prices. Overall the biggest hurdle will be cleaning the data because there seems to be no continuity in how it is presented in the excel sheets. Putting it into a single, tidy table will likely be the bulk of the work but it does not seem as a problem that will be anything more than time consuming. 

<center>References</center>

1. Goldman BJ, Clancy KL (1991) A survey of organic produce purchases and related attitudes of food cooperative shoppers. American Journal of Alternative Agriculture 6:89-96
2. Huang CL (1996) Consumer preferences and attitudes towards organically grown produce. European Review of Agricultural Economics 23:331-342
3. Hutchins RK, Greenhalgh L (1997) Organic confusion: sustaining competitive advantage. British food journal 99:336-338
4. Jolly DA, Schutz HG, Diaz-Knauf KV, Johal J (1989) Organic foods: consumer attitudes and use. Food Technology 43:60-66
5. Schifferstein HN, Ophuis PAO (1998) Health-related determinants of organic food consumption in the Netherlands. Food quality and Preference 9:119-133
6. Yiridoe EK, Bonti-Ankomah S, Martin RC (2005) Comparison of consumer perceptions and preference toward organic versus conventionally produced foods: A review and update of the literature. Renewable Agriculture and Food Systems 20:193-205

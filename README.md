# Kickstarter Analysis 

### Overall, the goal of the project was to deep dive Kickstarted campaigns to determine how launch dates and goals translated into overall campaign outcomes. To do this we visualized both outcomes based on campaign goals (i.e., how much funding was needed), as well as outcomes based on launch date. As Louise's analysis revolves around plays/theater, the analysis focuses on the subset of results for similar funding campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

- Not surprisingly, launch date heavily skewed overall success of similar Kickstarter campaigns. As evidenced in the chart below,  most theater successful outcomes occurred in the warmer months of the year Apr-Sept. May saw the most successful campaigns while June and July placed 2nd and 3rd. It’s important to note that the overall number of campaigns launched also increased in the warmer months, but successful outcomes were still more likely as evidenced by the differential between successful and failed outcomes during those months. Based on this data I would recommend Louise start her campaign in May.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111612130/187039173-2a497faf-984a-4cbc-a45e-4f76130b10f1.png)

### Analysis of Outcomes Based on Goals

- When looking at outcomes vs. goals, it’s important to look at overall project count. Some larger goals $25K+ saw ~50% to ~70% success rates, but there are limited overall projects in that funding range. Not surprisingly, overall, larger funding requirements correlated with higher overall failure rates. As such, I would recommend Louise stick with a smaller campaign goal if she can, ideally below $15K. This will lead to a higher chance her campaign will be successful.

![Outcomes_Vs_Goals](https://user-images.githubusercontent.com/111612130/187039638-cad52fa2-17b9-49ee-bf1f-0fa67290df4e.png)


### Challenges and Difficulties Encountered

- Challenge 1: No regional (city level) data was available, which could skew overall theater outcomes based on launch date. To perform a more comprehensive analysis, it would be usefully to understand if cities with warmer year-round climates had a similar uptick in successful outcomes during the warmer months i.e. was the uptick mainly in cities where there were cold winters but stayed constant in warmer climates. Louise can then make a more informed decision based on her regional location.

- Challenge 2: Its somewhat obvious that smaller goals would have higher success percentages while higher goals would have higher fail rates. Considering there is not a lot of overall data on plays past $25K, 42 of the overall 1,047 plays, Louise could consider analyzing the overall data and/or analyzing the parent category theater which would lead to a more robust data set.

## Results

- Conclusions: Outcomes based on launch date:
  - 1: Warmer months were heavliy correlated with overall successful outcomes for theater campains. 
  - 2: Colder months were heavily correlated with less successful outcomes and overall a higher precentage of failed outcomes.  

- Conclusions: Outcomes based on Goals:
  - 1: Goals of less than $5K had the highest likelyhood of sucess. 
  - 2: Goals of $45K or more had the lowest likelyhood of sucess. 

- Limitations:
  - This dataset only focused on Kickstarter campaigns, i.e. funding for projects. Just because a project was successfully funded on Kickstarter per this data, doesn’t mean it will be a commercial success and will lead to a profit. Louise should consider not only this data to help better determine how to successfully fund her play but should also look for data to help better determine if her play will be a commercial success once funded.  
  - This data, although categorized and regionalized, is not a direct apples to apples comparison to the exact play Louise is looking to fund. As such, there is a relative margin of error present in the data set and small regional nuances (such as city) or different genres of plays could have a big impact on funding, that information is not available in the data set.  
  - This data does not account for broader macro-economic circumstances especially when just looking at months. For example, the data set starts in 2009 and ends in 2017. Were people less likely to fund a campaign in 2009 due to the broader economic recession and more likely to fund a campaign in 2017 due to an improved economy? If so, how does that skew the data? Was Kickstarter less popular in 2009 vs. 2017 or vice-versa? Did Kickstarter launch an add campaign one year during May that skewed the May data set? These are all limitations in the overall data and relative unknowns based on this data set.

- Other Possible Tables and Graphs: 
  - 1: A table which broke the data down by month and year would be beneficial to help better understand if monthly increases in successful campaigns were evident through all years present in the data set or if it’s driven by an anomaly during one year.  
  - 2: Line charts for outcomes based on goals for the entire data set & and the entire data set by parent category. This would give Louise a better idea of how higher funding goals faired more broadly to help determine her funding goal level, as the plays data did not have many plays with high funding amounts.

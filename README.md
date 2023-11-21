# Netflix & Happiness Score Analysis
#### Notebooks are created on deepnote. Visit below website to checkout the result of our findings.
https://deepnote.com/workspace/thomas-learning-44bb20fd-6183-4bf5-bd7d-f755ce6a4cb3/project/HappinessAnalysis-2b19a6b0-4fe5-4d64-8611-c85d7cfa93f1/notebook/Final%20Notebook-a5e5a68f18454257a61b4951d6033c91

## Project Description
### Background
Netflix, a widely popular streaming service, offering services in 190 countries globally has played a big role in our mental health, especially when the COVID-19 pandemic began shutting down the world. In 2020 and 2021, we generally spent less waking time with people outside our own households. With less time out of the house, Netflix subscriber base increased by multiple folds with the world united with one common pastime - binge watching on Netflix content, a way of self-care to relax and de-stress.  

### Motivation
In October 2020, Netflix revised its pricing. Further on January 14, 2022, Netflix revised its pricing again for some countries. Netflix Price is different for each country. We wanted to investigate Netflix Pricing related data to see what factors may have helped Netflix's marketing determine pricing for each country. We wanted to see if there is correlation between Pricing with Netflix Library size, and whether there are key country development factors unique to each country which correlate to Netflix Pricing. 

We wanted to stretch this analysis further by analyzing if Happiness Score, compiled by Gallup World Poll data (which uses global survey data to report how people evaluate their own lives in more than 150 countries) has any correlation with Netflix Price! 

### Questions
To address these motivations, our team investigated how key country development factors - Gross Domestic Product (“GDP”), Population Size by Country (“POP”), Consumer Price Index and Inflation Rate (“Inflation”), collectively known as (“Economic Factors”), Happiness Score and Netflix Library Size compare against Netflix Pricing. We hope to discover meaningful insights on association, if any, between Netflix Pricing, Library Size together with Economic Factors and Happiness Score.

### How will the analysis help us?
The results will help us understand if there are proxy features which could be considered in building  a model to predict Netflix Price for countries where Netflix has no presence in.

### Provide answers to the following questions:
- How much are the top 10 countries paying for Netflix as compared to the bottom 10 countries? If the subscriber countries are paying more, are they rewarded with a larger Netflix Library Size? 
- What is the average price per region, and which region paid the most for Netflix?
Does GDP, inflation and Population Size affect Netflix Price?
- Which region has the highest Happiness Score? For the region with highest happiness score, does this region have a higher or lower Netflix Price? Further, are there any outliers noted which have potential bias to the analysis performed?

## Methodology
### Netflix Pricing for each Country
The dataset has features as follows: 1. Country, 2. Subscription fee, 3. Region, 4. Series library size, 5. Movie library size, 6. Total library size, 7. Subscription fee per title. This dataset enables us to analyze library size vs monthly cost in each part of the world - Bang for buck analysis.

Sources: https://www.comparitech.com/blog/vpn-privacy/countries-netflix-cost/

### World Happiness Report (from 2015 to 2021)
The dataset has features as follows: 1.GDP per capita, 2. Healthy Life Expectancy, 3.Social support, 4.Freedom to make life choices, 5.Generosity, 6.Corruption Perception. This dataset enables us to understand which features have a higher influence on happiness score. 

Sources: https://www.kaggle.com/datasets/mathurinache/world-happiness-report

### World Development Indicators
The World Development Indicators (WDI) are the World Bank's first collection of development indicators, compiled from data from officially recognized international sources. The world bank provides the latest and most accurate global development data, including country, regional and global data. We have decided to use it population and inflation data for our analysis.

Sources: https://datatopics.worldbank.org/world-development-indicators/

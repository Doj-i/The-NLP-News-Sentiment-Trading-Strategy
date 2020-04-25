*Please provide an updated description of any datasets that you are using. Briefly mention any challenges you have faced in cleaning and transforming the data.*

•	We are using ‘US Financial News Articles’ dataset from Kaggle.com for the first 5 months of 2018; we also use the list of S&P companies/industries and their stock/ETF returns for the same period as the supplementary datasets. 

•	Starting originally with 306k articles, we decided to focus only on the articles that are covering S&P 500 companies. Thus, we converted 300k+ articles into the csv / Data Frame, merged with S&P company list, labeled the articles by industry and unfiltered non-industry-specific news. As a result, our dataset shrined to 40k articles.

•	It was an interesting exercise in terms of optimizing the code to be able to scale on Big Data

•	We did not use any of the additional features in the data (author, source of article etc.) so that we could focus solely on the ‘title’, ‘text’ of the articles and ‘date of publishing’.

•	We also noticed that most of our articles are 200-1000 word long, and, given the fact that the articles represent high-dimensional space, we decided to focus only on the articled shorter than 1000 to avoid unnecessary noise.


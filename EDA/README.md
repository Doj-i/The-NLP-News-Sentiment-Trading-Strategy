
*Briefly describe any findings and insights derived from exploratory data analysis (EDA).*

•	 Based on our preliminary EDA, we also realized that there’s a lot of noise: 

	Some of that would be due to the timing of articles ('1st quarter', '4th quarter', '2018' will come up a lot) or the nature of the articles (as the earning releases discussed - you could find a lot of numbers)

	Some noise is tricky – "Financial" Industry came up a lot. Most likely, the analysts from these companies gave their perspective on the market in interviews. 

•	Top ngrams strongly indicated frequency of financial ratios, thus, we want to focus on them, including words that follow these terms along the text (e.g. ‘Net Income increased…’)

•	Top 2-, 3- and 4-grams tend to be more meaningful than 1-n grams
Thus, the next steps would be to clean the dataset further (‘stop-words’, manual cleaning, etc.)

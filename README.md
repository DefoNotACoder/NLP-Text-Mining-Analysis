We conducted a web scraping project to gather reviews from popular dating apps on the Google Play Store, focusing on Bumble, Hinge, Tinder, and OkCupid. 
Our project on Dating Apps Analysis, involved extracting a total of 764,386 reviews distributed across the apps: 154,771 from Bumble, 400,001 from Tinder, 70,717 from Hinge, and 138,897 from OkCupid. 
The data extracted from the Google Play Store included user IDs, review texts, ratings, and review dates. The reviews were contributed only by users who had signed up, making them trustworthy. 
To ensure the quality and consistency of the data, we applied two main criteria: maintaining an equal proportion of review scores across the apps and selecting reviews with a minimum of 20 words to avoid issues of sparsity and noise in short texts. 
The reviews were collected in descending order of recency, covering a temporal range from November 2015 to July 2024, with a majority being the latest submissions. Initially, the dataset included many short reviews and duplicates, totaling 529,126, 
which were subsequently removed. This left us with 235,260 reviews suitable for analysis. However, due to system constraints, we worked with a sample of 100,000 reviews. 
We encountered language variations, with reviews in both Hindi and English, and utilized a custom function to translate common Hindi slang and terms into English. Reviews in Arabic were excluded from the analysis.
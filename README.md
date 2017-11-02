
Bias on Wikipedia

DATA 512 A2 Bias in Data

The goal of this assignment is to explore 'bias' in terms of article coverage and article quality regarding political figures on Wikipedia for many countries.

I used a combination of Wikipedia articles data and country population data for the assignment. For the wikipedia articles,  I used a machine learning algorithm 'ORES' to evaluate the quality of each article. ORES reads article revision id as an input and outputs a quality score for each article.

There are 6 score categories here:
FA - Featured article
GA - Good article
B - B-class article
C - C-class article
Start - Start-class article
Stub - Stub-class article

A dataframe will be created after calculating score for each article and combining it with the population database, it will have the following columns:

Column
country
article_name
revision_id.
article_quality
population

For the analysis, I calculated the proportion of articles per country (number of articles regarding politicians divided by the population) and high-quality articles (number of high-quality articles divided by the total articles regarding politicians) for each country. An article is 'high-quality' when 'ORES' evaluates it in the 'FA (Featured Article)' or 'GA (Good Article)' category.

There will be four visualizations generated for this assignment:
10 countries with the highest proportion of politician articles per capita.
10 countries with the lowest proportion of politician articles per capita.
10 countries with the highest proportion of high-quality politician articles of all politician articles.
10 countries with the lowest proportion of high-quality politician articles of all politician articles.

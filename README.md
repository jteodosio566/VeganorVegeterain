# Project 3: Web-Scraping, Reddit, NLP, and Classification

## Problem Statement

Differentiate post between Vegan and Vegetarian posts.
As we saw in the definitions, these types of diets are somewhat strict. This model can help to classify posts that may contain recipes, ingredients, and foods. Moreover, it can help determine if they  are vegan or vegetarian.

### Outline:
1. Definitions.
2. Problem Statement.
3. Collecting data.
4. Cleaning the data.
5. Making models.
5. Compare models.
6. Conclusion.


## Data Dictionary before modeling dirty_table.csv

Feature|Type|Description
---|---|---
**subreddit**|_object_|name of the subreddit vegan or vegetarian.
**body**|_object_|body text of the subreddit.

## Data Dictionary while modeling clean_table.csv

Feature|Type|Description
---|---|---
**subreddit**|_int_|vegan = 1 and vegetarian = 0.
**body**|_object_|body text of the subreddit.

## Conclusion

- Our Logistic Regression model had an accuracy metric of 76.06% and the naive Bayes classifier had an accuracy metric of 75.73%. 
- The misclassification rate of the Logistic Regression model is 23.95%, and for the naive Bayes classifier, 24.27%. We definitely had a better     performance with our Logistic Regression model. 
- Nevertheless, to get a better performance, I would optimize stop words, or I use a random forest classifier.

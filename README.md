# Sntiment-analysis-of-amazon-product-reviwe-NLP

**Agenda

 1) Abstract
 Recently, Ecommerce has Witnessed Rapid Development. As a Result, Online Purchasing has
grown, and that has led to Growth in Online Customer Reviews of Products. They often want to
know intime what consumers and the public think of their products and services. However, it is
not realistic to manually read every post on the website and extract useful viewpoint information
from it. Therefore, models able to predict the user sentiment from the text review or user
experience from the reviews are critically important. Sentiment analysis allows large-scale
processing of data in an efficient and cost-effective manner. . This thesis considers the problem
of classifying reviews by their overall semantic (positive , extremely positive, negative, extremely
negative and neutral). We used dataset of the Amazon iphone 13 reviews, and then built a model
to predict the sentiment of the comments or reviews given by using Python and Vader (which
is a rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in
social media, and works well on texts

 2)Case Study
  Scrape the reviews of Amazon Product
  Using Natural Language Processing (NLP) do the sentiment analysis of the product

  3)Scraping Data
	Website used – Amazon.in
  Link of the product used -
https://www.amazon.in/Apple-iPhone-13-128GB-Starlight/product-reviews/B09G9D8KRQ/ref=cm_cr_a
rp_d_viewopt_sr?ie=UTF8&reviewerType=all_reviews&filterByStar=five_star&pageNumber=1

Scraping technique used – Beautifulsoup, Selenium

Libraries used – Beautifulsoup, selenium, webdriver, ChromeDriverManager

Programming Language used – Python

1.Selenium &

2.Beautifulsoup

4)Natural Language Processing

Natural language processing (NLP) refers to the branch of computer science—and more
specifically, the branch of artificial intelligence or AI—concerned with giving computers the
ability to understand text and spoken words in much the same way human beings can. It
allows machines to break down and interpret human language.

5)EDA
Normalizing the data
To remove both the leading and the trailing characters
To remove empty strings
Joining the list into one string/text
Removing Punctuations
Tokenization / Removing stopwords / Lemmatization / Stemming
Joining the data
Named Entity Recognition (NER)
TF-IDF Vectorizer
Generate Word Cloud
Named Entity Recognition (NER)
Filtering and counting the nouns and verbs tokens
(Barchart for top 10 nouns + verbs)
6)Sentiment Analysis (Using Affin.csv)
Sentiment Analysis (Using VADER)
One of the most important fields or techniques of NLP is sentiment analysis.

Sentimental analysis is the use of Natural Language Processing (NLP), Machine Learning (ML), or
other data analysis techniques to analyze the data and provides some insights from the data. It is
the process of detecting positive, negative, or neutral sentiment in the text.

We have used fine grained sentiment analysis which gives an understanding of customer feedback.
We can obtain a precise result in terms of the polarity of the input. The labels of the review will be
as
Positive
Extremely positive
Negative
Extremely Negative
Neutral

7)Deployment using Streamlit



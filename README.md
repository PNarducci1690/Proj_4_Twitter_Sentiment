# Determing Tweet Product Sentiment Using NLP

(___)

## Introduction

Over the past decade the impact of social media has expanded from its beginnings as a means to interact with friends and family. Websites like Facebook, YouTube, Instagram, and Twitter are now a means by which consumers can interact directly with their favorite brands, and vice versa. As a business in the 21st century using social media is a must due to ability to not only build your brand quickly, but creating consumer retention by communicating with your audience daily with just a click of a button. According to [Forbes](https://www.forbes.com/sites/forbescommunicationscouncil/2018/05/11/how-social-media-can-move-your-business-forward/?sh=569360cd4cf2), roughly 53% of the world's population is connected to the internet, with roughly 3.2 billion of the population active on social media.Forbes also goes on to mention that a 2017 survey conducted on 5,7000 marketers revealed that 69% had developed loyal fans for their brands.

This loyalty, or consumer retention is very important for a business - especially when using social media. As social organisms, we as a species build bonds or connections with others through interaction. A businesses goal, especially younger businesses seeking to grow, is to retain consumers well into the foreseable future. This is further refleted in the same Forbes article in which the author's company conducted a survey in which 60% of the respondents stated that they kept up to date with the businesses they followed on social media and 54% also believed that they believed that businesses that engaged with their clients and followers were more focused on providing a better service for the consumer.

Now, what does all of this have to do with my project? My project required me to use Natural Language Processing (NLP) on a dataset containing Tweets directed at the tech brands of Apple, Google, and Android. The tweets were categorized into sentiments, as well as brand and product types by humans.  As I explored the dataset, I focused on two main ideas:
* How can I use tweets in order to determine the sentiment directed at a brand?
* How can I determine the true negative tweets within the data set in order to retain customer support?


The latter question was a secodary focus to the former, but was of interest because I wanted to try and create a model that would help businesses interact with consumers that may have had a negative experience with their product. In order to produce an accurate model using text data I had to clean and strip the text of any annomolies, punctuations and other hindering features, tokenize and then vectorize the tweets using three methods - Count Vectorizer, TF-IDF Vectorizer, and Doc2vec. In order to train a model I tried three different model types - Multinomial Naieve Bayes, Random Forest, and XGBoost. The results are discussed below.

(___)

## Results

![Negative Word Cloud](https://github.com/PNarducci1690/Proj_4_Twitter_Sentiment/blob/main/images/neg_word_cloud.PNG)
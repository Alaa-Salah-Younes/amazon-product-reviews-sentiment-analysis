# amazon-product-reviews-sentiment-analysis

## Abstract
  Sentiment analysis or opinion mining is one of the major tasks of NLP (Natural Language Processing). 
  Sentiment analysis has gain much attention in recent years. In this paper, we aim to tackle the problem of sentiment polarity categorization,
  which is one of the fundamental problems of sentiment analysis. A general process for sentiment polarity categorization is proposed with detailed 
  process descriptions. Data used in this study are online product reviews collected from Amazon.com. Experiments for both sentence-level categorization 
  and review-level categorization are performed with promising outcomes. At last, we also give insight into our future work on sentiment analysis.

## Introduction
  Sentiment is an attitude, thought, or judgment prompted by feeling. Sentiment analysis [1-8],
  which is also known as opinion mining, studies people’s sentiments towards certain entities.
  Internet is a resourceful place with respect to sentiment information. From a user’s perspective, 
  people are able to post their own content through various social media, such as forums, micro-blogs, or online social networking sites.
  From a researcher’s perspective, many social media sites release their application programming interfaces (APIs),
  prompting data collection and analysis by researchers and developers. For instance, Twitter currently has three different versions of APIs available [9],
  namely the REST API, the Search API, and the Streaming API. With the REST API, developers are able to gather status data and user information;
  the Search API allows developers to query specific Twitter content, whereas the Streaming API is able to collect Twitter content in realtime. 
  Moreover, developers can mix those APIs to create their own applications. Hence, sentiment analysis seems having a strong fundament with the support of massive online data.

  However, those types of online data have several flaws that potentially hinder the process of sentiment analysis. 
  The first flaw is that since people can freely post their own content, the quality of their opinions cannot be guaranteed.
  For example, instead of sharing topic-related opinions, online spammers post spam on forums. 
  Some spam are meaningless at all, while others have irrelevant opinions also known as fake opinions [10-12].
  The second flaw is that ground truth of such online data is not always available. A ground truth is more like a tag of a certain opinion,
  indicating whether the opinion is positive, negative, or neutral. 
  The Stanford Sentiment 140 Tweet Corpus [13] is one of the datasets that has ground truth and is also public available. 
  The corpus contains 1.6 million machine-tagged Twitter messages. Each message is tagged based on the emoticons (☺as positive, ☹as negative) discovered inside the message.

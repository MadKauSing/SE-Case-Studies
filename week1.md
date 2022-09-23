# Software Engineering Laboratory - UE20CS303

> Ayush Singh - PES2UG20CS081
> 
> Ayushmaan Kaushik - PES2UG20CS082
> 
> Bhavini Madhuranath - PES2UG20CS088

---

## Week 1-Market Research Tool

---

### Aim

To create a data exploration tool that analyses keyword traffic over time, various regions and different languages to help marketers understand their target audiences better.

---

### Abstract

Market Researcher is a free data exploration tool that lets marketers better understand what audiences are interested in and curious about, in real-time. 

This works with a keyword research tool at its heart, which shows the keyword traffic in the form of searches on search engines such as Google. 

Marketers can use this data as a way to gain insight into customer behavior. This allows you to see how interest in a topic has changed, what terms are related to the topic, and even when interest in a topic tends to peak or diminish annually.

---

### Tools

- Google Trends Tool - a keyword research tool
- TensorFlow - An open source library used for creating machine learning models
- HuggingFace - A tokenizer tool to process text
- rake-nltk - A keyword extraction algorithm

---

### Method

1. Web scrape google searches for information regarding the chosen market.

2. Convert them into tokens (using HuggingFace) or keywords (using rake-nltk).

3. Feed the keywords as input to a neural network (RNN, most preferably) with publishing dates of sites. 

4. Use Google Trends Tool in parallel as a supplementary result.

5. Use a voting classifier to give better results.

---

### Conclusion
This market research tool provides a simple yet effective solution for looking up relevant data on a wide variety of topics, trends and documents. This helps our users make informed decisions for their business or personal needs. It also inspires new ideas and visualizations for content creation.

--- 
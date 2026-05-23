# Twitter Brand Sentiment Analysis: Adidas vs Lululemon

## Overview
This project analyzes Twitter conversations related to Adidas and Lululemon to understand public sentiment, customer engagement, dominant discussion topics, and potential micro-influencers.

Using Natural Language Processing (NLP), sentiment analysis, and topic modelling techniques, the project provides insights into brand perception and customer behaviour on social media platforms.

---

## Business Problem
Brands increasingly rely on social media analytics to understand customer opinions, measure engagement, and identify influential voices online.

This project aims to:
- Compare public sentiment towards Adidas and Lululemon
- Identify dominant conversation themes
- Detect potential micro-influencers
- Support data-driven marketing decisions

---

## Dataset
- Twitter datasets for Adidas and Lululemon
- Over 38,000 Adidas tweets
- Over 6,000 Lululemon tweets
- Tweet metadata including:
  - Followers
  - Retweets
  - Likes
  - User information

---

## Technologies & Tools
- Python
- Pandas
- NLTK
- VADER Sentiment Analyzer
- Scikit-learn
- LDA Topic Modelling
- WordCloud
- Matplotlib
- Seaborn

---

## Methodology

### 1. Data Cleaning & Preprocessing
- Removed retweets and promotional tweets
- Lowercased text
- Removed URLs, mentions, punctuation, and stopwords
- Applied lemmatization

### 2. Exploratory Analysis
Analyzed:
- Tweet volume
- User engagement
- Verified users
- Follower distribution
- Retweet behaviour

### 3. Sentiment Analysis
Used VADER (Valence Aware Dictionary and sEntiment Reasoner) to classify tweets into:
- Positive
- Neutral
- Negative

### 4. Topic Modelling
Applied Latent Dirichlet Allocation (LDA) to identify dominant discussion topics for each brand.

### 5. Micro-Influencer Identification
Users were evaluated based on:
- Follower count
- Engagement metrics
- Positive sentiment
- Topic relevance

---

## Key Findings

### Adidas
- Higher overall engagement volume
- Strong brand visibility
- Dominant themes included sneakers, product launches, and promotions

### Lululemon
- More positive audience sentiment
- Discussions focused heavily on customer experience and product satisfaction
- Slightly higher negative sentiment linked to customer service concerns

### Influencer Insights
Potential micro-influencers were identified using engagement and sentiment-based filtering techniques.

---

## Business Impact
This project demonstrates how NLP and social media analytics can support:
- Brand monitoring
- Customer sentiment tracking
- Influencer marketing
- Competitive analysis
- Marketing strategy optimization

---

## Repository Structure

```bash
twitter-brand-sentiment-analysis/
│
├── notebook.ipynb
├── report.pdf
├── README.md
├── images/
└── outputs/
```

---

## Visualizations Included
- Sentiment Distribution Charts
- Word Clouds
- Topic Modelling Outputs
- Engagement Comparisons
- Tweet Frequency Analysis

---

## Future Improvements
- Real-time Twitter streaming
- Transformer-based sentiment models
- Advanced topic modelling
- Network analysis of influencers
- Comparative sentiment trend analysis

---

## Author
Tamasree Chakraborty  
MSc Business Analytics  
University of Nottingham

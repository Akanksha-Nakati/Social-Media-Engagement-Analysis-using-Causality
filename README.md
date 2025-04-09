# 📊 Social Media Engagement Analysis using Causality
This project explores causal inference techniques to analyze and understand the impact of different post parameters (like hashtags, time of posting, or content type) on user engagement metrics (likes, comments, shares, etc.) across Instagram and LinkedIn. The goal is to move beyond correlation and apply causal methods to uncover insights that can drive better content strategies on social platforms.

## 🔍 Objective
To identify causal relationships between content characteristics and engagement metrics.

To optimize posting strategies based on data-driven insights rather than assumptions.

To compare engagement dynamics across Instagram and LinkedIn.

## 🛠️ Methodology
The analysis involves:

1. Data Preparation

Preprocessing engagement metrics and post attributes.

Feature engineering for causal modeling.

2. Causal Inference Techniques

Causal Graphs using DoWhy.

Double Machine Learning (DML) from EconML.

Treatment Effect Estimation to quantify impact of variables.

3. Key Metrics Analyzed

Likes, Comments, Shares, Impressions.

Post timing, content type, hashtag count.

4. Assumptions

Causal sufficiency and correct model specification were assumed during estimation.

## 📈 Key Insights
#### Instagram:

1. Posting in the evenings increases engagement.

2. Too many hashtags (>10) may reduce impressions.

#### LinkedIn:

1. Posts with external links receive less engagement.

2. Hashtag usage positively correlates with reach when kept under 5.

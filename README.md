# 📊 Social Media Engagement Analysis using Causality
This project explores causal inference techniques to analyze and understand the impact of different post parameters (like hashtags, time of posting, or content type) on user engagement metrics (likes, comments, shares, etc.) across Instagram and LinkedIn. The goal is to move beyond correlation and apply causal methods to uncover insights that can drive better content strategies on social platforms.

## 🔍 Objective
To identify causal relationships between content characteristics and engagement metrics.

To optimize posting strategies based on data-driven insights rather than assumptions.

To compare engagement dynamics across Instagram and LinkedIn.

## 🛠️ Methodology
The analysis involves:

#### 1. Data Preparation

1. Preprocessing engagement metrics and post attributes.

2. Feature engineering for causal modeling.

#### 2. Causal Inference Techniques

1. Causal Graphs using DoWhy.

2. Double Machine Learning (DML) from EconML.

3. Treatment Effect Estimation to quantify impact of variables.

#### 3. Key Metrics Analyzed

1. Likes, Comments, Shares, Impressions.

2. Post timing, content type, hashtag count.

#### 4. Assumptions

1. Causal sufficiency and correct model specification were assumed during estimation.

## 📈 Key Insights
#### Instagram:

1. Posting in the evenings increases engagement.

2. Too many hashtags (>10) may reduce impressions.

#### LinkedIn:

1. Posts with external links receive less engagement.

2. Hashtag usage positively correlates with reach when kept under 5.

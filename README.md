# Enhancing E-commerce Recommendations with Amazon Shopping Session

## Authors
- Minwoo Sohn
- Jiayu Shi


## Abstract
This project advances the e-commerce recommendation system for Amazon through the use of Neural Networks (NNs), including Long Short-Term Memory Recurrent Neural Networks (LSTM-RNNs). Over 1.5 million product entries and 1.04 million session records form the dataset basis, with a graph-based approach applied to predict user purchases from session data dynamically. The introduction of price features into the LSTM model marked a significant performance improvement, highlighting the potential of LSTMs in recommendation systems.

## Introduction
Accurately modeling customer shopping intentions is essential for enhancing user experience and engagement on e-commerce platforms. Unlike traditional systems relying on long-term profiles, this project utilizes session-based recommendations to provide real-time personalization.

## Objective
The primary goal is to develop an advanced recommendation system for Amazon to accurately predict products of interest to customers, utilizing comprehensive product attributes and session data.

## Methodology

### Datasets
The project analyzes two main tables: Product and Session.

#### Product Dataset
The Product Dataset includes over 1.5 million entries with essential attributes like ID, Locale, Title, and Price, although some fields have missing data.

#### Session Dataset
Comprising about 1.04 million records, the Session Dataset provides insights into customer browsing and purchasing sequences, critical for optimizing recommendation systems.

## Exploratory Data Analysis (EDA)
The EDA aims to uncover patterns across product attributes that inform the recommendation model's development, noting product pricing trends, popular brands, and consumer preferences for colors and sizes.

## Model Development

### Neural Network (NN)
NNs process and store information through a structure akin to the human brain, with input, output, and hidden units. This adaptability has led to NN breakthroughs in various fields.

### Long Short-Term Memory (LSTM)
LSTMs excel in tasks requiring an understanding of temporal dynamics, overcoming traditional RNNs' limitations and providing a framework to integrate both immediate and long-term shopping behavior into predictions.

## Model Evaluation and Metrics
Accuracy is the key metric, with the model's performance evaluated on the top 100 recommended products.

## Challenges
The initial data posed computational challenges, prompting a reduction to focus on the UK market. Data management involved selecting frequently appearing products and truncating session sequences to manageable lengths.

## Feature Engineering
Feature engineering included retaining the 'price' column and combining other attributes into a single string for BERT model processing, resulting in a 768-dimensional product vector.

## Results
While the baseline model achieved limited accuracy, the LSTM with price features demonstrated a marked increase in predictive performance.

## Conclusion and Future Work
The models surpassed the baseline performance. Future work will focus on expanding feature incorporation, enhancing the LSTM model, and refining data processing to improve predictive accuracy.




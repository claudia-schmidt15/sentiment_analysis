# sentiment_analysis
## Mapping Negative Sentiment in U.S. College Subreddits

Janurary to May 2024 - Data Mining (CS 470), Emory University 

This project analyzes negative sentiment in U.S. college subreddit posts to better understand the drivers of student stress and how these differ across institutions. Using Python and NLP techniques, we built a pipeline to classify themes such as academic pressure, financial concerns, health & wellness, and social/personal issues.

Our findings highlight that financial stress emerged as the leading driver of negative sentiment with a greater share of posts at public universities (33.9%) compared to private ones (23.9%). This work demonstrates how data-driven insights can support more effective institutional responses to student mental health concerns.

## Features
- Large-scale text analysis of posts from 128 university subreddits (~147,000 posts).
- Sentiment classification using a RoBERTa-based NLP model.
- Theme extraction via attention weights, part-of-speech tagging, and clustering.
- Quality-controlled classification of posts into five themes:
  - Academic Pressure
  - Future Anxiety
  - Social/Personal
  - Financial
  - Health & Wellness
- Comparative analysis between public vs. private institutions and across different demographics.

## Included Files

**Sentiment_Analysis.ipynb**

The main Jupyter notebook containing code for data preprocessing, sentiment analysis, theme classification, and results visualization.

**Results.pdf**

Final project report summarizing methodology, experiments, findings, limitations, and possible extensions.

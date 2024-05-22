# Sentiment Analysis on YouTube Comments

## Introduction
This paper presents a comprehensive study on the sentiment analysis of YouTube comments to understand viewer sentiments across various video categories. This analysis helps gauge content effectiveness, enhance user engagement, and inform creators about viewer preferences.

## Dataset Description
### Dataset-1
- **Source:** [Dataset-1 Link](https://zenodo.org/record/4533302)
- **Details:** Includes comments from "Tunnels" by "The Boring Company" from YouTube, capturing diverse opinions about Elon Musk's ideas. The dataset features mixed sentiments and spam comments, consisting of 4403 records categorized by comment content, sentiment, and spam/ham classification.

### Dataset-2
- **Source:** [Dataset-2 Link](https://github.com/pranaykmr/YouTubeSentimentAnalysisandPredictingTrends/blob/master/data/labeled_comments.csv)
- **Details:** Comprises 1100 comments from a Dude Perfect video, labeled for sentiment and spanning positive, neutral, and negative reactions. The comments include user expressions ranging from support to criticism.

Both datasets were merged to form a larger corpus of 4668 comments, enhancing the diversity and representativeness of the data for more robust sentiment analysis.

## Project Description
The project distinguishes itself by employing ensemble learning for sentiment analysis on YouTube comments and comparing the efficacy of various machine learning models, including traditional classifiers and deep learning approaches. Techniques like stemming, lemmatization, and random oversampling were used to tackle class imbalance and enhance data quality.

## Key Findings
- **AI-Powered Sentiment Analysis:** Utilizing CNN and SVM models, our study achieved an accuracy of 76% with the CNN-SVC ensemble model, demonstrating the effectiveness of combining NLP techniques and machine learning.
- **Practical Applications:** Provides actionable insights for content creators and marketers to understand public opinion and tailor content accordingly.

## Differences from Other Studies
Compared to similar studies, this project used distinct datasets and applied a unique combination of preprocessing techniques and machine learning algorithms. Notable comparisons include:
- **Technological Innovations:** Leveraged newer machine learning models and ensemble techniques, contrasting with traditional methods used in other studies.
- **Dataset and Preprocessing:** Focused on two specific YouTube contexts (educational and entertainment), using advanced preprocessing to enhance model training and performance.

## Future Directions
- **Multilingual Analysis:** Expand the model to include sentiment analysis in multiple languages.
- **Real-time Analysis:** Develop capabilities for real-time sentiment analysis to provide immediate insights for content creators.

## Conclusion
Our project illustrates the potential of AI in enhancing sentiment analysis of YouTube comments, offering a significant tool for digital marketers, content creators, and social media analysts. Future improvements will focus on scaling the solution to handle larger datasets and real-time analysis, pushing the boundaries of what is possible in content strategy and viewer engagement analytics.

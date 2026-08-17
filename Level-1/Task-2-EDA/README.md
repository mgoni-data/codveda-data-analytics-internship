## Task 2; Exploratory Data Analysis (EDA)

## Overview

This project was completed as part of the Codveda Technology Data Analytics Internship; Level 1.

The objective was to explore a cleaned sentiment dataset and identify patterns and relationships within social-media engagement data.

## Dataset

The dataset contains 710 observations and 13 columns after preprocessing.

Key variables analyzed include:

 > Sentiment
 > Likes
 > Retweets
 > Year
 > Month
 > Day
 > Hour

## Analysis Performed

The exploratory analysis included:

 > Dataset overview and structure
 > Missing-value and duplicate checks
 > Descriptive statistics
 > Distribution analysis of Likes and Retweets
 > Sentiment distribution analysis
 > Correlation analysis
 > Likes vs. Retweets scatter plot
 > Sentiment vs. engagement analysis
 > Posting-hour vs. engagement analysis

## Key Findings

 > Likes ranged from 10 to 80, while retweets ranged from 5 to 40.
 > Likes and retweets showed an extremely strong positive correlation (r = 0.99847).
 > Engagement varied substantially across sentiment categories.
 > Motivation and Mesmerizing recorded some of the highest average engagement.
 > Helplessness, Jealousy, Numbness, and Boredom were among the categories with lower average engagement.
 > Posting hour was associated with differences in average likes, with late-evening hours showing relatively high engagement in this dataset.

## Tools Used

 > Python
 > Pandas
 > Matplotlib
 > Jupyter Notebook

## Files

- [Jupyter Notebook](./Codveda_Level_1_Task_2_EDA.ipynb); Jupyter Notebook containing the analysis and visualizations.
- [PDF Report](./Codveda_Level_1_Task_2_EDA.pdf); PDF version of the completed analysis.

## Conclusion

The analysis identified clear relationships between social-media engagement, sentiment categories, and posting time. The extremely strong relationship between likes and retweets was particularly notable.

However, these findings represent associations within the dataset and should not be interpreted as evidence of causation. Additionally, sentiment categories with very few observations should be interpreted cautiously.


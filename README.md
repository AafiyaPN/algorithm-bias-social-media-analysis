# Algorithm Bias in Social Media Platforms
## Project Overview

This project investigates **algorithmic bias in social media platforms** by analyzing engagement patterns from Instagram and Twitter datasets.

Modern social media platforms rank content using engagement-based algorithms. This can create **visibility inequality**, where a small number of posts receive most of the attention.

This project explores whether algorithmic amplification contributes to engagement inequality.
## Research Questions

- Do certain posts receive disproportionately high engagement?
- Does early engagement influence long-term visibility?
- Is engagement distribution equal across posts?
- Are there signs of algorithm-driven amplification?
## Dataset

The datasets used in this project are publicly available.

Instagram Analytics Dataset:
https://www.kaggle.com/datasets/kundanbedmutha/instagram-analytics-dataset

Twitter Engagement Dataset:
https://www.kaggle.com/datasets/thedevastator/tweets-and-user-engagement

Due to repository size and best practices, datasets are **not included in this repository**.

After downloading the datasets, place them in:

data/raw/

Required files:

- instagram_analytics.csv
- twitter_engagement.csv

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Results

| Metric | Instagram | Twitter |
|------|------|------|
| Gini Coefficient | 0.379 | 0.931 |
| Pearson Correlation | 0.731 | -0.022 |
| Median Engagement Rate | 0.047 | 0.000 |

These results indicate **stronger engagement inequality on Twitter compared to Instagram**.

## Conclusion

The analysis suggests that **algorithmic amplification exists on both platforms**.

However, Twitter demonstrates significantly higher engagement inequality, meaning visibility is concentrated among fewer posts.

This supports the hypothesis that engagement-based ranking systems may reinforce popularity bias.

## Project Structure

algorithm-bias-social-media-analysis
│
├── data (ignored from GitHub)
│   ├── raw
│   └── processed
│
├── notebooks
│   └── algorithm_bias_analysis.ipynb
│
├── outputs
├── visuals
└── README.md

## Author

Aafiya P N

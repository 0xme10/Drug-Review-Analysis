# Drug Review Analysis

Drug Review Analysis: An exploration on sentiment analysis and how condition classification of text review can extract positive and negative effects of drugs sold to patients.

## Files

This repository contains the following files:

- **Data**: Includes all the data files required for the project, including the original data sourced from Kaggle.
- **Notebooks**: Four Jupyter notebook files that cover different aspects of the analysis:
  - EDA Notebook: Provides an introduction to the project, explores the dataset, performs data visualization, and gains insights into drug perceptions and conditions mentioned in reviews.
  - Preprocessing Notebook: Handles missing data, cleans text reviews, and prepares the data for modeling.
  - Sentiment Modeling Notebook: Develops classification models for sentiment analysis, trains and evaluates different machine learning models, and presents the results of the analysis.
  - Condition Classification Modeling Notebook: Develops classification models for sentiment analysis and condition prediction, trains and evaluates different machine learning models, and presents the results of the analysis.
- **Label Decoder**: A pickle file used for condition decoding.
- **Executive Summary Report**: A PDF document summarizing the key findings, insights, and conclusions of the project.
- **Drug Availability CSV**: A CSV file containing web-scraped data on drug availability from drugs.com.
  
## Enviroment
we create the enviroment drug_review for this project by using the conda terminal.

conda create -n drug_review pandas numpy seaborn matplotlib scikit-learn nltk textblob requests beautifulsoup4 torch transformers tqdm


## Project Overview

Throughout the project, we have organized our analysis into separate notebooks, each addressing a specific aspect of the analysis. This approach ensures clarity, modularity, and a systematic workflow. Here's a brief overview of each notebook:

1. EDA Notebook: This notebook provides an introduction to the project, explores the dataset, performs data visualization, and gains insights into drug perceptions and conditions mentioned in reviews.

2. Preprocessing Notebook: In this notebook, we handle missing data, clean text reviews, and prepare the data for modeling. This includes preprocessing steps such as data cleaning, feature engineering, and data transformation.

3. Sentiment Modeling Notebook: Here, we develop classification models for sentiment analysis. We train and evaluate different machine learning models to achieve accurate predictions and validate the effectiveness of our methodologies. We present the results of our analysis, including model performance metrics, important features, and actionable insights.

4. Condition Classification Modeling Notebook: In this notebook, we develop classification models for sentiment analysis and condition prediction. Similar to the Sentiment Modeling Notebook, we train and evaluate different machine learning models, present the results of our analysis, and summarize the key findings and implications.

By organizing our project into separate notebooks, we maintain clarity, modularity, and a systematic approach throughout the analysis. This structure allows us to focus on each aspect of the project individually while ensuring the coherence and reproducibility of our findings.

## Getting Started

To get started with the project, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have the required dependencies installed. You can refer to the `readme.md` file for more information.
3. Explore the notebooks in the provided order to understand the project workflow and analysis process.
4. Execute the notebooks by running the cells to reproduce the analysis and results.
5. Refer to the Executive Summary Report for a comprehensive overview of the project, including key findings, insights, and conclusions.

## Conclusion

In conclusion, this project aims to analyze drug reviews and predict sentiments and conditions associated with the drugs. By leveraging data science techniques, we have developed models to perform sentiment analysis and condition prediction. The analysis provides valuable insights into user perceptions, helps pharmaceutical companies make informed decisions, and contributes to the development of targeted and effective treatments.

Please refer to the individual notebooks and the Executive Summary Report for detailed analysis, methodology, and results.

For any questions or further information, please contact 0xme10

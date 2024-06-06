# Analytica_UvA

## Project Overview
This project explores the potential benefits and threats of using Large Language Models (LLMs) for automated content moderation on social media platforms, specifically focusing on tweets. The analysis includes both qualitative and quantitative approaches to assess biases, user perceptions, and the effectiveness of LLMs in labeling content.

## Folder Structure
### 1. `code/`
This directory contains all the scripts and notebooks used for various analyses within the project.

- **bias/**: 
  - Scripts for comparing biases in the labeling done by different LLMs.
  
- **label/**:
  - Code and files related to the labeling process of the dataset.
  
- **LLM_comparison/**:
  - Analysis of how different LLMs labelled the Politifact dataset.
  
- **random_sample/**:
  - Scripts for generating random samples from the tweets dataset for testing and analysis purposes.
  
- **regression/**:
  - Implementation of logistic regression models as part of our analysis.
  
- **survey/**:
  - Analysis of survey data including design, execution, and results.
  
- **tm_tweets/**:
  - Topic modeling analysis of the tweets dataset.
  

### 2. `data/`
This directory contains all the datasets used and generated in the project.

- `1976-2020-president.csv`:
  - Dataset containing information about presidents from 1976 to 2020.
  
- `2000_random_tweets_labelled.csv`:
  - A labeled dataset of 2000 random tweets.
  
- `labelled/`:
  - Additional labeled datasets used in the analysis.
  
- `politifact_dataset/`:
  - Politifact dataset used for truth prediction and labeling analysis.
  
- `survey/`:
  - Contains survey responses and related data.

### 3. `README.md`
This file. Provides an overview of the project, directory structure, and instructions for setup and usage.

### 4. `requirements.txt`
Lists the Python packages and dependencies needed to run the project code.

## Research Questions
- **Qualitative Analysis**:
  - What are the considerations behind the moderation of tweets using AI?
  - How can the "hegemony" of content moderation be deconstructed using critical theory?
  
- **Quantitative Analysis**:
  - What are users' perceptions of misinformation moderation through LLMs on social media?
  - What biases emerge when using different LLMs to label tweets as fake or true?
  - Can we predict which tweet GPT-3.5 will label as fake or true?

## Methodology
- **Expert Interviews**:
  - Conducted to gather qualitative insights on AI moderation.
  
- **Thematic Analysis**:
  - Performed on interview data to identify key themes and considerations.
  
- **Survey Design and Execution**:
  - Surveys designed to capture user perceptions of AI moderation.
  
- **Quantitative Analysis**:
  - Analysis of survey responses to quantify user perceptions.
  - Logistic regression model to predict truthfulness of tweets.
  - Confusion matrix to compare classifier performance across different LLMs.

## Analysis and Interpretation
- Critical theory analysis to explore and challenge existing content moderation paradigms.
- Quantitative analysis to assess biases, user perceptions, and the effectiveness of LLMs.
- Interpretation of findings to identify potential benefits and threats of automated content moderation.

## Setup and Usage
1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   cd <repository_directory>

# Contributing
If you would like to contribute to this project, please submit a pull request or contact the project maintainers.

# License
This project is licensed under the MIT License - see the LICENSE file for details.


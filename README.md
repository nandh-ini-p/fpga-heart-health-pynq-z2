# FPGA-Powered Precision: Prediction of Heart Health and its Insights Extraction Using PYNQ-Z2 Board

## Overview

This project explores FPGA-based implementation of two interconnected tasks: heart disease prediction using machine learning models and web text summarization with sentiment analysis. The implementation leverages the PYNQ-Z2 FPGA board with Python and the PYNQ framework to evaluate the potential of edge-oriented processing for healthcare and information-retrieval applications.

## Objectives

- Develop a machine-learning-based approach for heart disease prediction.
- Explore web text summarization using web scraping, tokenization, word frequency analysis, and sentence scoring.
- Apply sentiment analysis to generated text summaries using TextBlob.
- Implement the proposed tasks using the PYNQ-Z2 FPGA platform.
- Examine the potential of FPGA-based processing for efficient edge-oriented applications.

## Dataset

The project uses the UCI Heart Disease Dataset, which contains 303 instances and 14 attributes. The dataset includes the following variables: age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiogram (ECG), maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise relative to rest, slope of the ST segment, number of major vessels colored by fluoroscopy, thallium test result, and target diagnosis.

Data preprocessing involved handling missing values, encoding categorical variables, and performing exploratory data analysis.

## Methodology

### 1. Heart Disease Prediction

The heart disease prediction task includes:

- Dataset acquisition and preprocessing
- Missing-value imputation
- One-hot encoding of categorical variables
- Exploratory data analysis
- Model development and evaluation

Three machine learning models were evaluated:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

Model performance was assessed using the following metrics:
- Accuracy
- Precision
- Recall
- F1 score

### 2. Web Text Summarization

The web text summarization workflow comprises:

- Web scraping to retrieve online content
- Tokenization of text into individual words and sentences
- Removal of stopwords
- Calculation of word frequencies
- Weighted frequency computation
- Sentence scoring based on weighted word frequencies
- Generation of concise summaries from longer web content

### 3. Sentiment Analysis

TextBlob was applied to perform sentiment analysis on the generated text summaries.

### 4. FPGA Implementation

The heart disease prediction and web text summarization tasks were implemented on the PYNQ-Z2 board using Python and the PYNQ framework. The paper discusses FPGA-based processing in terms of latency, throughput, resource utilization, and energy efficiency as evaluation dimensions for edge-oriented applications.

## Machine Learning Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 92.5% |
| Random Forest Classifier | 94.3% |
| Support Vector Machine (SVM) | 90.8% |

The reported results show different predictive accuracies across the three evaluated models, with the Random Forest Classifier reporting 94.3% accuracy in the project.

## Web Summarization Results

The project evaluated FPGA-powered text summarization against conventional software-based processing. TextBlob sentiment analysis was applied to the generated summaries. The paper describes improvements in processing efficiency resulting from FPGA implementation; specific numerical speed and throughput benchmarks are discussed within the project documentation.

## Hardware and Software

| Component | Details |
|---|---|
| FPGA Platform | PYNQ-Z2 |
| Programming / Framework | Python, PYNQ |
| Machine Learning | Logistic Regression, Random Forest, SVM |
| Dataset | UCI Heart Disease Dataset |
| Text Processing | Web scraping, tokenization, word frequency, sentence scoring |
| Sentiment Analysis | TextBlob |

## Key Project Aspects

- Machine-learning-based heart disease prediction using clinical variables
- Web text summarization with automated content extraction and scoring
- Sentiment analysis of textual information
- FPGA/PYNQ-Z2 hardware implementation
- Exploration of edge-oriented healthcare and information-retrieval applications

## Project Documentation

- Project Presentation
- Project Documentation

## Source Code & Further Details

The complete implementation and full project documentation are not publicly distributed in this repository. This repository provides a curated overview of the project methodology, selected results, and technical context for academic and portfolio purposes. For further academic details, the author may be contacted.

## Contact

**Nandhini Palanisamy**  
Electronics & Communication Engineering  
Email: pnandhini2003@gmail.com

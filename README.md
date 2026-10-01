# FPGA-Powered Precision: Prediction of Heart Health and Its Insights Extraction Using PYNQ-Z2 Board

## Overview

This project combines heart disease prediction using machine learning with web text summarization and sentiment analysis, and presents the workflow on the PYNQ-Z2 FPGA board. The work integrates predictive analytics with text-based insight extraction in a single academic system.

## Objectives

- Predict heart disease using a structured clinical dataset.
- Apply web text summarization and sentiment analysis to textual information.
- Implement the described workflow on the PYNQ-Z2 FPGA board.

## Dataset

The study uses the UCI Heart Disease dataset, which contains 303 instances and 14 attributes. The dataset includes demographic and clinical variables. Preprocessing included handling missing values and encoding categorical variables. Exploratory data analysis was also performed.

## Methodology

### Heart Disease Prediction

The heart disease prediction task used three machine learning models:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

Model performance was evaluated using accuracy, precision, recall, and F1 score.

### Web Text Summarization

The documented workflow for web text summarization included:

- Web scraping
- Text extraction
- Tokenization
- Stopword removal
- Word-frequency calculation
- Weighted frequency calculation
- Sentence scoring
- Summary generation
- TextBlob-based sentiment analysis

### FPGA Implementation

The paper describes FPGA implementation on the PYNQ-Z2 board using Python and the PYNQ framework. The implementation covers the heart disease prediction and web text summarization tasks. The paper discusses speed, resource utilization, and accuracy as performance measures.

## Machine Learning Models

The reported test-dataset accuracies for the evaluated models are as follows:

| Model | Reported Test Accuracy |
|---|---:|
| Logistic Regression | 92.5% |
| Random Forest Classifier | 94.3% |
| Support Vector Machine | 90.8% |

These values are reported test-dataset accuracies.

## Results

The project paper includes several documented figures and results, including:

- Target and Sex vs Count bar graph
- Chest Pain Type vs Frequency bar graph
- Age vs Maximum Heart Rate scatter plot
- Age vs Blood Pressure scatter plot
- Correlation heatmap
- Accuracy comparison of the three machine learning models
- Generated text summary
- PYNQ-Z2 implementation
- ROC curve
- Predicted label vs true label heatmap
- Cross-validation metric visualization
- Feature importance bar graph
- Optimized summary output

The reported results summarize the prediction performance, text summarization output, and FPGA-based implementation discussed in the project paper without introducing additional numeric claims beyond those provided.

## Hardware and Software

The hardware and software technologies explicitly documented for this project are:

- PYNQ-Z2 FPGA
- Python
- PYNQ framework
- TextBlob
- UCI Machine Learning Repository

## Project Documentation

- [Methodology](#methodology)
- [Project Presentation](#)
- [Selected Results](#results)

## Source Code & Further Details

The complete implementation is not publicly distributed. Selected methodology and results are provided in this repository for academic and portfolio purposes. For further technical details or academic discussion, please contact the author.

## Contact

Nandhini Palanisamy
Email: [YOUR EMAIL]

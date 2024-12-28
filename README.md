
# Predicting Student Performance in Secondary Education
# Regularization-technique

Overview

This repository contains code and datasets for predicting student performance in secondary education (high school). The data is derived from two Portuguese schools and includes various features related to student demographics, social background, school-related information, and grades. The primary focus is to use this data to predict student achievement in two distinct subjects: Mathematics and Portuguese language.

Dataset Characteristics

Type: Multivariate
Subject Area: Social Science
Associated Tasks: Classification, Regression
Feature Type: Integer
Number of Instances: 649
Number of Features: 30
Missing Values: None
Dataset Information

The dataset approaches student achievement in secondary education through various features collected via school reports and questionnaires. It includes data from two distinct subjects:

Mathematics (mat)
Portuguese language (por)
The data can be used for both binary/five-level classification and regression tasks. The target variable, G3 (final year grade), has a strong correlation with G1 and G2 (grades from the first and second periods, respectively). While predicting G3 without G1 and G2 is more challenging, it provides more valuable insights.

Project Objectives

The primary objectives of this project are to:

Predict the final grades (G3) in Mathematics and Portuguese.
Analyze the impact of various demographic, social, and school-related features on student performance.
Explore the differences in performance prediction between the two subjects.
Evaluate the effectiveness of classification and regression models on this dataset.
Getting Started

Prerequisites
To run the code in this repository, you need to have the following installed:

Python 3.x
Required Python libraries (see requirements.txt)

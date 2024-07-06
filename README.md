# Lab 2: Working with a Data Set

## Overview

This project involves working with a real-life data set and exploring its preparation for machine learning. The dataset used is the Howell dataset, which includes height, weight, age, and gender information. The goal is to perform an initial exploration, prepare the data for modeling, and perform various analyses.

## Table of Contents

1. [Project Structure](#project-structure)
2. [Getting Started](#getting-started)
3. [Requirements](#requirements)
4. [Setting Up the Virtual Environment](#setting-up-the-virtual-environment)
5. [Usage](#usage)
6. [Results](#results)

## Project Structure

The project consists of the following files:

- `lab2_starter.ipynb`: The Jupyter Notebook containing the code and analyses.
- `Howell.csv`: The dataset used in this project.
- `README.md`: This README file.
- `dgraves-ml-lab2-checkpoints.docx`: The document containing screenshots and checkpoint analyses.

## Getting Started

To get started with this project, you need to clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/lab2-working-with-dataset.git
cd lab2-working-with-dataset
```

## Requirements

- pandas
- matplotlib
- scikit-learn
- numpy

## Virtual Environment

1. Create virtual environment and activate

```bash
#Create environment
python -m venv .venv

#Activate environment
source .venv/scripts/activate
```
2. Install  required packages

```bash
pip install pandas matplotlib scikit-learn numpy
```
## Usage

1. Navigate to the project directory
2. Open Jupyter lab with command:

```bash
jupyter lab
```
3.  Follow instructions in starter notebook alongside course reference pdf to run code cells and perform analyses. 

## Results 

1. Data Overview: Displaying basic information about the dataset, including the number of instances, features, and missing values.
2. Data Distributions: Visualizing the distributions of height, weight, and age.
3. Correlation Analysis: Identifying the highest correlation between features.
4. Age vs. Weight Analysis: Exploring the relationship between age and weight.
5. Age Histogram: Comparing the age distribution in the dataset with modern populations.
6. BMI Calculation: Adding a new feature for BMI and categorizing it.
7. Stratified Data Split: Splitting the data into training and test sets while maintaining the ratio of males to females.
8. Male-to-Female Ratios: Computing the male-to-female ratios for the entire dataset, training set, and test set.

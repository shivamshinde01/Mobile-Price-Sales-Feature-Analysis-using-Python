# Mobile Price Sales Feature Analysis

This project focuses on analyzing mobile phone specifications (features) and their relationship with price categories. Using data visualization and descriptive statistics, the analysis aims to reveal how different phone features such as battery power, RAM, and internal memory impact a mobile phone’s price range.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Goals](#project-goals)
- [Dataset](#dataset)
- [Technologies](#technologies)
- [Setup Instructions](#setup-instructions)
- [Analysis and Visualizations](#analysis-and-visualizations)
  - [Price Range Distribution](#price-range-distribution)
  - [Battery Power by Price Range](#battery-power-by-price-range)
  - [RAM by Price Range](#ram-by-price-range)
  - [Internal Memory by Price Range](#internal-memory-by-price-range)
  - [Correlation Heatmap](#correlation-heatmap)
  - [RAM and Battery Power Relationship by Price Range](#ram-and-battery-power-relationship-by-price-range)
- [Conclusions](#conclusions)

## Project Overview

The purpose of this project is to conduct a thorough data analysis on mobile phone features to understand their effect on sales prices. The analysis utilizes a dataset from Kaggle that categorizes mobile phones into price ranges and includes specifications such as battery power, RAM, internal memory, and more. Through visualizations and feature analysis, we can determine which features contribute most to higher price ranges.

## Project Goals

- **Understand the distribution of mobile phones across different price ranges**.
- **Analyze key mobile phone features** (battery power, RAM, internal memory) and their relationship with price.
- **Identify features that may be essential in influencing price for various market segments** (low, mid, high, premium).

## Dataset

- **Source**: [Kaggle Mobile Price Prediction Dataset](https://www.kaggle.com/iabhishekofficial/mobile-price-classification)
- **Description**: This dataset includes mobile phone specifications along with a categorical variable for price range. Each phone is classified into one of four price ranges, from low to high.

### Key Attributes:
- `battery_power`: Battery capacity in mAh.
- `ram`: RAM size in MB.
- `int_memory`: Internal memory size in GB.
- `price_range`: Price category of the phone (0 = low, 1 = medium, 2 = high, 3 = very high).

## Technologies

### Programming Language:
- Python

### Libraries:
- **Pandas** for data manipulation and analysis.
- **NumPy** for numerical operations.
- **Matplotlib** and **Seaborn** for data visualization.


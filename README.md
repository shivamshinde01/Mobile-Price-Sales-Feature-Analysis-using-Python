**Mobile Price Sales Feature Analysis**
This project focuses on analyzing mobile phone specifications (features) and their relationship with price categories. Using data visualization and descriptive statistics, the analysis aims to reveal how different phone features such as battery power, RAM, and internal memory impact a mobile phone’s price range.

**Table of Contents**
Project Overview
Project Goals
Dataset
Technologies
Setup Instructions
Analysis and Visualizations
Price Range Distribution
Battery Power by Price Range
RAM by Price Range
Internal Memory by Price Range
Correlation Heatmap
RAM and Battery Power Relationship by Price Range
Conclusions

**Project Overview**
The purpose of this project is to conduct a thorough data analysis on mobile phone features to understand their effect on sales prices. The analysis utilizes a dataset from Kaggle that categorizes mobile phones into price ranges and includes specifications such as battery power, RAM, internal memory, and more. Through visualizations and feature analysis, we can determine which features contribute most to higher price ranges.

**Project Goals**
To understand the distribution of mobile phones across different price ranges.
To analyze key mobile phone features (battery power, RAM, internal memory) and their relationship with price.
To identify features that may be essential in influencing price for various market segments (low, mid, high, premium).

**Dataset**
Source: Kaggle Mobile Price Prediction Dataset
Description: This dataset includes mobile phone specifications along with a categorical variable for price range. Each phone is classified into one of four price ranges, from low to high.

**Key Attributes:**
battery_power: Battery capacity in mAh.
ram: RAM size in MB.
int_memory: Internal memory size in GB.
price_range: Price category of the phone (0 = low, 1 = medium, 2 = high, 3 = very high).
Technologies

**Programming Language: Python**

**Libraries:**
Pandas for data manipulation and analysis.
NumPy for numerical operations.
Matplotlib and Seaborn for data visualization.
Setup Instructions
Clone the Repository: Clone this repository to your local machine.
Download the Dataset: Download the dataset from Kaggle and place it in the data/ folder within the project directory.

**Install Dependencies:**
pip install pandas numpy matplotlib seaborn
Run the Analysis: Open price_sales_analysis.ipynb in Jupyter Notebook or any other IDE that supports Jupyter Notebooks, and execute the cells to perform the analysis.
Analysis and Visualizations

**Price Range Distribution**
Chart Type: Count Plot
Purpose: To show the frequency of mobile phones in each price category.
Interpretation: This chart allows us to see how many phones are in each price range (low, medium, high, very high). This distribution helps us understand if the dataset contains more budget, mid-range, or high-end phones.

**Battery Power by Price Range**
Chart Type: Box Plot
Purpose: To examine the distribution of battery power across price ranges.
Interpretation: Phones in higher price ranges tend to have higher battery capacities, suggesting that larger batteries are a desirable feature for premium devices.

**RAM by Price Range**
Chart Type: Box Plot
Purpose: To analyze the distribution of RAM in each price category.
Interpretation: As the price range increases, the amount of RAM also generally increases, indicating that high-performance RAM is typically offered in higher-priced phones. This relationship shows that performance features are significant in differentiating phones by price.

**Internal Memory by Price Range**
Chart Type: Box Plot
Purpose: To visualize the distribution of internal memory (storage) across price ranges.
Interpretation: Higher-priced phones tend to offer more internal storage, which appeals to users who need additional space for applications, media, and files. Budget phones usually have limited storage.

**Correlation Heatmap**
Chart Type: Heatmap
Purpose: To display correlations between various phone features and the price range.
Interpretation: Strong positive correlations between price range and features like RAM and battery power suggest that these specifications play a significant role in determining the phone’s price.

**RAM and Battery Power Relationship by Price Range**
Chart Type: Scatter Plot
Purpose: To examine the relationship between RAM and battery power, with price range as a hue.
Interpretation: Phones with high RAM and large battery power are typically in the higher price ranges, which reinforces the finding that these features are essential in differentiating premium phones from budget options.

**Conclusions**
This analysis highlights several key insights into how mobile phone features relate to price range:

Battery Power: Higher battery capacity is often a feature in premium phones, reflecting user expectations for longer battery life.
RAM: Higher RAM is associated with higher-priced phones, indicating its importance in performance differentiation.
Internal Memory: More internal storage is found in expensive models, appealing to users with extensive storage needs.
Feature Importance: RAM and battery power are the two features most strongly correlated with price range, making them crucial for pricing and marketing decisions.
This project provides a foundational analysis for understanding how mobile phone specifications impact pricing. It can serve as a valuable reference for product teams, marketers, or anyone interested in data analysis of product features and market segmentation.

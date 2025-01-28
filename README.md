
# ZeoTap Assignment 

# ECommerce Transactions Analysis and Insights

This repository contains a comprehensive analysis of an eCommerce Transactions dataset, aimed at uncovering business insights, building a customer lookalike model, and performing customer segmentation using clustering techniques. Below is an overview of the project, methodology, and key results.

## Project Structure

The project is divided into three main tasks:

### Task 1: Exploratory Data Analysis (EDA) and Business Insights

- **Objective**: Understand the dataset, identify patterns, and derive actionable business insights.
- **Key Steps**:
  1. Data cleaning and preprocessing.
  2. Exploratory analysis using statistical methods and visualizations.
  3. Generating insights and recommendations.
- **Key Insights**:
  - High revenue from Electronics and Home Appliances categories.
  - Seasonal sales peaks during November and December.
  - Urban regions contribute 70% of total sales.
  - Underperforming categories like Apparel and Accessories.
  - High-value customers drive 60% of revenue.

### Task 2: Lookalike Model

- **Objective**: Recommend 3 similar customers for each of the first 20 customers based on their profile and transaction history.
- **Key Steps**:
  1. Feature extraction from customer and transaction data.
  2. Similarity calculation using metrics like cosine similarity.
  3. Generating top 3 recommendations with similarity scores.

### Task 3: Customer Segmentation / Clustering

- **Objective**: Segment customers into distinct groups based on profile and transaction history.
- **Key Steps**:
  1. Data preprocessing (e.g., scaling, encoding).
  2. Applying clustering algorithms like K-Means.
  3. Evaluating clustering performance using Davies-Bouldin Index.
  4. Visualizing the clusters.
- **Key Findings**:
  - Identified meaningful clusters to target marketing and sales efforts.
  - Achieved a low DB Index indicating effective clustering.

## How to Run the Project

### Prerequisites

1. Python 3.7+
2. Required Python libraries:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn

### Steps to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/username/ZeoTap_Assignment.git
   cd ecommerce_analysis
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebooks for each task and run the cells sequentially:
   - `Firstname_Lastname_EDA.ipynb`
   - `Firstname_Lastname_Lookalike.ipynb`
   - `Firstname_Lastname_Clustering.ipynb`

### Data Files

Ensure the following CSV files are in the project directory:

- `Customers.csv`
- `Products.csv`
- `Transactions.csv`

## Results and Recommendations

- **EDA**: Revealed key insights to enhance business strategies.
- **Lookalike Model**: Delivered accurate customer recommendations.
- **Clustering**: Identified distinct customer segments for targeted marketing.

## Acknowledgments

Special thanks to the eCommerce dataset providers for making this analysis possible.

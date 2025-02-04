# Customer Analysis - Identifying Loyal Customers and Top Products

## Overview
This project analyzes customer transaction data to identify the most profitable products and the characteristics of the most loyal customers. The findings help the marketing department focus on the key target segments rather than marketing to everyone.

## Datasets Used
- **`purchase_behaviour.csv`** - Contains customer demographic and behavioral data, including lifestyle stage and premium/budget segmentation.
- **`transaction_data.csv`** - Contains transaction details such as product names, sales amount, and customer loyalty card numbers.

## Libraries Used
The following Python libraries are used for data analysis and visualization:
- **`pandas`**: For data manipulation and analysis.
- **`matplotlib.pyplot`**: For basic data visualization.
- **`seaborn`**: For advanced visualizations and aesthetics.

## Exploratory Data Analysis (EDA)
Before diving into insights, an EDA was performed, including:
- Displaying dataset info and summary statistics.
- Checking for missing values.
- Understanding the distribution of key variables.

## Key Findings
### 1. Top 3 Most Profitable Products
By aggregating total sales across all transactions, we identified the three highest-grossing products. These products contribute the most revenue and should be prioritized in marketing campaigns.

### 2. Characteristics of Loyal Customers
Loyal customers were identified based on their total spending. Their characteristics include:
- **Lifestage Distribution**: Most profitable customers fall into specific life stages (e.g., young professionals, retirees, families with children).
- **Premium vs. Budget Buyers**: The analysis distinguishes whether high-value customers prefer premium or budget products.

## Hypothesis on Customer Loyalty
- **Pricing & Value Perception**: Budget-conscious or premium-focused customers stick to brands that offer the best value.
- **Convenience**: A significant portion of loyal customers are families,whether they may be older or younger families. They may favor convenience—easy access, quick checkout, and reliable product availability.
- **High-Quality**: Customers might be loyal because of the high quality of the products.

## Visualization Insights
To support the findings, the following visualizations were generated:
1. **Bar Chart** - Highlights the top 3 most profitable products.
2. **Pie Charts** - Show customer distribution by lifestage, spending category (premium vs. budget), marital status, and employment status.

## Usage
To replicate the analysis, run the provided Jupyter Notebook containing the Python code. Ensure that all required libraries are installed and that the dataset files are in the correct directory.

---
**Author:** Fawaz Khan  
**Tools Used:** Python, Pandas, Matplotlib, Seaborn


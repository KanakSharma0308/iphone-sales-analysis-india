This repository contains a data-driven analysis of Apple iPhone sales performance, pricing strategies, and customer satisfaction metrics within the Indian market. Using a dataset of 62 unique iPhone configurations, this project leverages Python and Interactive Visualizations to uncover how pricing and discounts influence consumer behavior.
The analysis transitions from basic data cleaning to complex multi-variable scatter plots, providing a clear picture of which models dominate the market and why.

📊 Key Analytical Features
1. Data Cleaning & Preprocessing
Null Value Check: Verified that the dataset is complete with zero missing values across all 11 columns.
Data Typing: Ensured numerical columns like Number Of Ratings and Sale Price are correctly formatted for mathematical operations.

2. Descriptive Statistics
Pricing: The average sale price for an iPhone in this dataset is approximately 80,073.89, with a maximum price reaching 140,900.
Discounts: Apple offers an average discount of ~10%, though some models see aggressive price cuts of up to 29%.
Customer Sentiment: The average star rating is a high 4.57/5, indicating strong brand loyalty and product satisfaction.

3. Visual Insights
The project utilizes Plotly to create high-fidelity, interactive charts:
Top 10 Rated iPhones: A breakdown of the highest-rated models, highlighting the iPhone 11 Pro Max series (4.7 stars).
Sales vs. Ratings: A scatter plot analyzing if higher-priced models receive fewer ratings compared to budget-friendly options.
Discount Impact: A bubble chart (size-coded by price) showing the relationship between discount percentages and the volume of ratings.

🛠️ Tech Stack & Libraries
Language: Python 3.14

Data Manipulation: pandas, numpy
Visualization: plotly.express, plotly.graph_objects
File Handling: openpyxl (for Excel integration)

📂 Dataset Structure
The analysis is performed on apple_products.xlsx, which includes:
| Column | Description |
| :--- | :--- |
| Product Name | Full name and configuration of the iPhone |
| Sale Price | The current price on Flipkart |
| Mrp | The original Maximum Retail Price |
| Discount Percentage | The percentage of price reduction |
| Number Of Ratings | Total user ratings submitted |
| Star Rating | The average score out of 5 |
| Ram | Memory configuration |
https://github.com/KanakSharma0308/iphone-sales-analysis-india/blob/main/apple_products%20(1).xlsx

💡 Conclusion
The data suggests that while the "Pro Max" models hold the highest ratings (4.7), the standard models and older generations (like the iPhone SE and iPhone 11) tend to accumulate a significantly higher number of ratings, likely due to their more accessible price points and higher discount margins.

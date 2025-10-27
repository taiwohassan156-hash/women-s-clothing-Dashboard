# women-s-clothing-Analysis

# Table of contents 
- [Project overview](#projectoverview)
- [Data sources](#datasources)
- [Recommendations](#recommendations)
- 
### Project Overview 

The Women’s Clothing Sales Dashboard was developed to analyze customer feedback and purchasing patterns in the women’s fashion industry. The main goal of this project was to uncover insights that explain how customer ratings, age distribution, and product categories influence positive feedback and overall satisfaction.
Using interactive data visualizations, the dashboard provides a clear overview of customer behavior based on ratings, recommendations, and product types, helping fashion retailers understand what drives loyalty and product success.

<img width="874" height="498" alt="women's clothing" src="https://github.com/user-attachments/assets/d8131466-ff38-4775-b6c4-32cce17ae4bd" />


### Data sources 

The dataset used in this project was obtained from Quantum Analytics NG.

### Tools 
- Power Bi - incorporating data cleaning, transformation and visualisation techniques.

### Data Cleaning and preparation 

Before beginning the analysis, the raw data underwent a thorough cleaning and preparation process to ensure accuracy and reliability.

The following steps were taken during the data cleaning phase:

- Handling Missing Values
Missing entries in key columns such as Review Text, Title, and Division Name were identified. Text-based missing values were replaced with “No Review” or “Not Specified,” while missing numerical values (like Age and Rating) were handled using appropriate imputation methods or removed where necessary.
- Data Type Correction
Columns were checked to ensure that numerical data (like Age and Rating) were properly formatted as numbers and categorical fields (like Department Name, Class Name) were converted to categorical types for easier grouping and visualization.
- Removing Duplicates and Irrelevant Fields
Duplicate reviews were identified and removed to avoid bias in analysis. Irrelevant columns that did not contribute to insights such as review IDs or unnamed indexes were also dropped to streamline the dataset.
- Creating Derived Columns
New calculated columns were created for better analysis, such as a Recommendation Flag (Yes/No) and Age Group Categories (e.g., 20–30, 31–40, 41–50, etc.) to help identify review patterns across demographics.
- Text Cleaning
Review texts were standardized by removing punctuation, converting to lowercase, and trimming unnecessary spaces. This ensured consistency for potential sentiment analysis.
- Validation and Quality Check
After cleaning, the dataset was validated by checking summary statistics (mean, mode, count) and ensuring all categorical and numerical data aligned correctly.


### Exploratory Data Analysis (EDA)

- What is the overall customer rating for women’s clothing?
- Which department received the highest number of reviews?
- Which of the recommendation has the highest rating review?
-  What is the total count of positive feedback?
-  Which age group provides the most reviews?
- Which age group gives the highest positive feedback?
- Which product class received the highest positive feedback?
- Which department has the highest number of product recommendations?

### Results and Findings

The analysis of the women’s clothing dataset revealed valuable insights into customer behavior, preferences, and satisfaction levels.

- The dashboard showed that the average customer rating was 4.18, reflecting a generally positive shopping experience among customers. The Tops department emerged as the most reviewed category, demonstrating its popularity and wide appeal among shoppers. However, the Dresses department recorded the highest average rating, suggesting that customers are highly satisfied with the quality, design, and overall value of dresses compared to other categories.
- In terms of customer demographics, the age group 25–44 years accounted for the highest number of reviews. This indicates that middle-aged adults are the most active and influential segment in the women’s clothing market. Furthermore, this same age group provided the highest average ratings, emphasizing their loyalty and satisfaction with the brand’s offerings.
- The positive feedback count exceeded 60,000, highlighting strong engagement from customers. Additionally, products with higher ratings were significantly more likely to be recommended by customers, confirming a strong correlation between customer satisfaction and word-of-mouth marketing.
Product classes such as Dresses, Knits, and Blouses stood out for receiving the highest number of positive reviews and recommendations, positioning them as the brand’s top-performing items.
- Overall, the findings reveal that while the brand enjoys a positive perception, maintaining product quality in top performing categories and improving others with lower ratings could further enhance customer trust and loyalty.


### Recommendation

- Based on the findings from the analysis, it is recommended that the company focus on sustaining and improving the quality of products in the Dresses, Knits, and Tops categories, as these are the most loved by customers and have the highest ratings. Greater attention should be given to departments with lower customer ratings to identify and address issues related to product quality, fit, or pricing.

- Additionally, since customers within the 25–44 age group represent the most active and satisfied buyers, targeted marketing campaigns and personalized offers should be directed toward this demographic to strengthen brand loyalty. The company should also encourage more customer engagement by promoting product reviews and feedback collection after purchases.

- Finally, leveraging high rated customer reviews for promotional purposes and implementing a reward system for recommendations can enhance word-of-mouth marketing and drive higher customer retention rates over time.


📊 Amazon Product Rating Analysis

🎯 Objectives

The goal of this project is to analyze Amazon product ratings to understand:

1. The overall distribution of product ratings

2. The relationship between price discounts and customer satisfaction

3. Top-performing brands and product characteristics under the Cables category

4. Whether text sentiment in reviews aligns with the given ratings

🧩 Methodology

1. Data Collection
   Extracted product data (including name, category, brand, price, discount, and rating) and corresponding review content.
   Data source: https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset

3. Data Cleaning & Preparation

   1) Removed duplicates and irrelevant categories.

   2) Standardized numerical columns (price, discount, rating).

   3) Tokenized and cleaned text data for sentiment analysis.

4. Exploratory Data Analysis (EDA)

   1) Visualized rating distributions.

   2) Calculated correlation between price discount and rating.

   3) Identified top brands and keyword frequency in product names.

5. Sentiment Validation
   Performed sentiment analysis on review text to validate whether the written opinions align with the numerical ratings.

🧠 Key Insights & Findings

   1. Rating Distribution
   
   Most products fall between 4.0 and 4.5 stars, showing generally positive but not perfect satisfaction levels.

   2. Price Discount vs. Rating
  
   The correlation coefficient is -0.155, indicating a weak negative relationship between discount and rating.
   ➡️ This means discounts are not a major factor influencing customer satisfaction.

   3. Top Brands in the Cables Category
  
   The best-performing brands (top 80th percentile ratings) include:
          AmazonBasics, Amazon, Wayona, MI, and boAt.
   ➡️ These brands maintain good ratings - consistent quality.

   4. Keyword Insights
  
   Top-rated cables commonly feature keywords such as:
       “feet,” “lightning,” “grey,” “certified,” “MFi,” “HDMI.”
   ➡️ These words indicate that:
      1) Customers value cables with lightning compatibility, specific length units (feet), and appealing colors (grey).
      2) They also appreciate certified, MFi-compliant, and HDMI-type cables, which are often associated with higher quality and reliability.
         
   In contrast, customers are generally less satisfied with:
      1) Cables that emphasize being “Made in India” or come from the Solero brand. 
      2) Products labeled as “480 Mbps” or marketed as “durable” also tend to receive lower ratings, suggesting that these features did not meet customer expectations.
    
   5. Review Sentiment Validation

   Sentiment analysis confirms that customer ratings are genuine — reviews with positive language align with high ratings, and negative wording aligns with lower ratings.
   ➡️ Customers did not leave misleading ratings that contradict their written feedback.

🧰 Tools & Libraries

   1) Python
   2) Google Colab
   3) Pandas, Matplotlib, Seaborn
   4) Hugging Face Transformers for sentiment analysis
   5) NumPy, SciPy

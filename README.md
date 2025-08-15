# 📊 Apple Store Reviews Analysis
Overview

This project analyzes 1,000 Apple Store app reviews to uncover trends in user ratings, purchases, likes, and more. The dataset includes details such as App Name, User Age, Review Date, Rating, Likes, Purchase Amount, and Category.
We perform exploratory data analysis (EDA), statistical calculations, hypothesis testing, and visualization to derive insights about user behavior and app performance.

# 📂 Dataset

File: Apple_Store_Reviews.csv
Rows: 1,000
Columns: 12

Column Name	Description
Review_ID	Unique review identifier
App_Name	Name of the app reviewed
User_Age	Age of the reviewer
Review_Date	Date of the review
Rating	Rating given (1–5)
Review_Text	User's written review
Likes	Number of likes on the review
Device_Type	Device used for the review
Version_Used	App version reviewed
Country	Country of the reviewer
Purchase_Amount	Amount spent in USD
Category	App category
🔍 Key Analyses Performed

Central Tendency of Ratings

Mean: 2.87

Median: 3.00

Mode: 1.00

Best Measure: Median (less influenced by skewed distribution).

Spread of Purchase Amount

Range: 19.97 USD

Interquartile range (IQR) used to understand variability and outliers.

Likes Analysis

Variance: 822.85

Standard Deviation: 28.69 (indicating high variability).

Correlation

Likes vs. Rating: Positive correlation (r = 0.84).

Distribution & Skewness of Ratings

Positively skewed (right skew) → more low ratings, fewer high ratings.

Hypothesis Testing

Instagram vs WhatsApp Ratings: No statistically significant difference at the 95% confidence level.

Central Limit Theorem Demonstration

Sampling distribution of the mean created using 1,000 samples (n=30) shows a near-normal shape.

# 📈 Visualizations

Bar chart of Mean, Median, Mode of Ratings.

Boxplot for Purchase Amount spread.

Scatter plot (regression) of Likes vs. Rating.

Histogram of Ratings distribution.

Sampling distribution histogram demonstrating CLT.

# 🛠️ Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)

Jupyter Notebook for interactive analysis

# 🚀 How to Run

Clone this repository:

git clone https://github.com/yourusername/apple-store-reviews-analysis.git
cd apple-store-reviews-analysis


Install dependencies:

pip install pandas numpy matplotlib seaborn scipy


Run the Jupyter Notebook:

jupyter notebook


Open the analysis notebook and execute cells.

# 📌 Conclusion

Median is the most reliable central tendency measure for ratings.

Likes strongly correlate with higher ratings.

The data distribution supports the Central Limit Theorem when sampling.

Instagram does not have significantly higher ratings than WhatsApp.

# 📜 License

This project is licensed under the MIT License.

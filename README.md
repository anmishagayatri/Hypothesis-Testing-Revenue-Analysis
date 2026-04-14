📊 Hypothesis Testing for Revenue Optimization
🔍 Problem Statement

Businesses often lack clarity on which payment methods drive higher revenue. This project analyzes whether payment type significantly impacts transaction value and overall revenue.

📁 Dataset
NYC Taxi Trip dataset
~20,000+ records after cleaning
Key features:
Payment Type
Fare Amount
Trip Distance
🛠️ Tools & Technologies
Python (Pandas, NumPy)
Statistical Testing (Independent T-Test)
Data Visualization (Matplotlib, Seaborn)
🔄 Approach

1. Data Cleaning

Removed missing values and outliers
Filtered relevant columns for analysis

2. Exploratory Data Analysis (EDA)

Compared average fare across payment types
Visualized distribution of transaction values

3. Hypothesis Testing

H₀: No significant difference in revenue between payment types
H₁: Significant difference exists
Applied Independent T-Test to validate results
📈 Key Insights
Card payments generated higher average transaction value compared to cash
Statistical testing confirmed significant difference (p < 0.05)
Customers using digital payments tend to contribute more revenue
💡 Business Impact
Enables businesses to optimize revenue through payment strategy
Supports adoption of digital payments
Helps in targeting high-value customer segments


📌 Conclusion

The analysis shows that payment methods have a measurable impact on revenue. Encouraging digital payments can lead to higher transaction value and improved overall revenue performance.

🚀 How to Run
git clone <your-repo-link>
cd <repo-name>
pip install -r requirements.txt
jupyter notebook

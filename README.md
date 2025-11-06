# BCG_powerCo_EDA

Problem Statement:

"As a Junior Data Scientist at BCG X, you are tasked with investigating a customer churn problem for a client, PowerCo. PowerCo suspects that price sensitivity is driving their customers to switch providers, and you need to leverage data science techniques to solve this challenge. The problem involves analyzing and cleaning real-world datasets, engineering features, building predictive models, and translating insights into actionable business recommendations.

Your objective is to identify the factors that contribute to customer churn, predict future churn behavior, and provide strategic recommendations to PowerCo that can help reduce churn and improve customer retention." (According to Forage problem statement)

What I Did:
Firstly imported the given template.

Starting from the 12-Month Electricity Consumption Distribution Chart, I:

1. Analyzed Consumption Data: Plotted the distribution of electricity consumption (cons_12m) to understand usage behavior and detect outliers.

2. Mapped and Cleaned Categorical Data: Created mappings for channel_sales and origin_up to replace encoded values with understandable labels like “Email Campaign,” “Phone Channel,” etc.

3. Visualized Cleaned Distributions: Plotted Channel Sales Distribution and Origin Up Distribution to identify which sales channels and acquisition sources were most effective.

4. Explored Churn Distribution: Plotted churn data to check the balance between retained and lost customers, helping identify class imbalance in the dataset.

5. Merged Datasets: Combined the Client_df and Price_df datasets using the id column for correlation analysis.

6. Feature Correlation Heatmap: Visualized correlations between numeric features and churn to identify key drivers, such as consumption, price variations, and margins.

Tools Used

Python (Pandas, NumPy) for data manipulation and cleaning.

Matplotlib & Seaborn for data visualization (histograms, barplots, heatmaps).

Jupyter Notebook for structured analysis and documentation.

Recommendations

1. Target High-Consumption Customers: Customers with higher cons_12m values tend to be more valuable; retention strategies like loyalty discounts can be applied to reduce churn.

2. Optimize Sales Channels: Focus on the most effective acquisition channels (e.g., email and phone campaigns) for better conversion and retention.

3. Monitor Price Sensitivity: Price fluctuations (especially during peak hours) correlate with churn — PowerCo should consider flexible pricing or communication to retain customers.

4. Predictive Modeling Readiness: The clean and merged dataset is ready for predictive modeling, such as churn prediction using classification algorithms.

Conclusion

The EDA provided valuable insights into PowerCo’s customer behavior and churn dynamics. The dataset was well-structured, with minimal missing values and clear patterns in consumption and pricing. Key takeaways include a strong influence of energy consumption and pricing on churn, and the importance of certain acquisition channels in maintaining customer loyalty. This analysis forms a solid foundation for building machine learning models to predict churn and develop data-driven retention strategies for PowerCo.

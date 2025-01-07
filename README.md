# Ecommerce_Project
# Ecommerce Platform Optimization Project

## Project Overview
This project was undertaken for an Ecommerce company based in New York City that sells clothing online and offers in-store style and clothing advice sessions. Customers engage with personal stylists in-store and later make purchases through either a mobile app or a website. The objective of this project was to help the company decide whether to focus on improving their mobile app experience or their website.

## Objective
To determine which platform—mobile app or website—contributes more significantly to annual customer spending, guiding the company's decision on where to focus their development efforts.

## Dataset
The analysis was conducted using the **Ecommerce Customers CSV dataset**, which includes the following features:
- Average Session Length
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent

## Methodology
We used **Linear Regression** to analyze the relationship between customer behavior on different platforms and their annual expenditure. The key steps in our approach included:

1. **Data Preprocessing**: Cleaning and preparing the data to ensure accuracy.
2. **Exploratory Data Analysis (EDA)**: Identifying patterns and correlations between features.
3. **Feature Selection**: Determining which features are most predictive of yearly spending.
4. **Model Training**: Building a linear regression model to predict yearly spending.
5. **Model Evaluation**: Evaluating the model's performance using R-squared and RMSE metrics.

## Results
The analysis revealed a stronger correlation between **Time on App** and **Yearly Amount Spent**, compared to **Time on Website**. This suggests that customers who engage more with the mobile app tend to spend more annually.

## Conclusion
Based on the findings, we recommended focusing on improving the mobile app experience to potentially increase customer engagement and sales. A **Streamlit** application was developed to present the results interactively, allowing stakeholders to explore the data and insights.

## Tools and Technologies
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Streamlit**

## Repository Structure
- `data/`: Contains the Ecommerce Customers CSV dataset.
- `notebooks/`: Jupyter notebooks with data analysis and model training steps.
- `app/`: Streamlit application code for interactive data visualization.
- `README.md`: Project description and overview.

## Future Work
- Further explore customer demographics and their impact on spending.
- Implement advanced machine learning models to improve prediction accuracy.
- Conduct A/B testing on mobile app enhancements to validate the findings.

Feel free to explore the repository, and contributions are welcome!


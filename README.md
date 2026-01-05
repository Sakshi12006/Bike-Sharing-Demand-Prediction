# Shared Bikes Demand Prediction (Multiple Linear Regression)
*Optimizing Revenue for BoomBikes through Demand Forecasting*

## 📌 Project Overview
BoomBikes, a US bike-sharing provider, experienced a dip in revenues due to the pandemic. This project uses **Multiple Linear Regression** to understand the factors affecting the demand for shared bikes in the American market. The goal is to identify which variables are significant in predicting demand and how well they describe the bike dynamics.

## 📂 Repository Structure
- **[data/](./data/):** Contains the `day.csv` dataset featuring environmental and seasonal settings.
- **[docs/](./docs/):** Contains the [Subjective Q&A PDF](./docs/Linear%20Regression%20Assignment%20-%20subjective%20Questions%20%5E0%20Answers.pdf) covering model assumptions and theoretical insights.
- **[notebooks/](./notebooks/):** Contains the [Analysis & Modeling Notebook](./notebooks/Bike%20rental%20daily%20assignment(Linear%20Regression).ipynb) with the full Python implementation.

## 📊 Key Insights & Model Findings
- **Seasonal Impact:** Demand is highest in **Fall** and lowest in **Spring**.
- **Weather Influence:** "Clear" weather significantly boosts rentals, while "Light Snow/Rain" drastically reduces them.
- **Yearly Growth:** There was a significant increase in demand from 2018 to 2019, suggesting an upward trend in bike-sharing popularity.
- **Top Predictors:** Temperature (`temp`), year (`yr`), and winter season emerged as the most significant positive predictors.

## 🛠️ Technical Workflow
1. **Data Visualization:** Performed EDA using box plots and pair plots to identify correlations.
2. **Data Preparation:** Handled categorical variables using dummy encoding and performed scaling.
3. **Model Building:** Used a hybrid approach of **RFE (Recursive Feature Elimination)** and manual selection (VIF/P-value) to build a parsimonious model.
4. **Residual Analysis:** Validated assumptions of linear regression through error term normality checks (Q-Q plots).

## 🎓 Academic Context
This is the third project of the **Executive PG Programme in Data Science and AI at IIIT Bangalore** (affiliated with upGrad). It demonstrates proficiency in statistical modeling and residual validation.

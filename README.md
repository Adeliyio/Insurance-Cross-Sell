# Health Insurance Cross-Sell

This project aims to prioritize a potential client list based on propensity score.

## 1.0 Business Problem

Insurance All, a company specializing in vehicle insurance, contemplates offering a new product: health insurance. The product team seeks to identify potential customers among existing policyholders to target for this new offering. A dataset comprising customer attributes and responses from a survey regarding interest in health insurance has been compiled, with a subset of customers earmarked for a targeted campaign.

## 2.0 Business Assumptions

Cross-selling, a strategy aimed at offering complementary products to customers, has shown to increase Return on Investment (ROI) and Average Ticket Price, as evidenced by research conducted by Harvard Business Review. 

## 3.0 Solution Strategy

This data science project aims to develop a machine learning model to predict customers' interest in health insurance, aiding in the selection of potential clients. The project involves several steps:

**Step 01. Data Description:** Collect and preprocess the dataset, including handling missing values and conducting initial exploratory data analysis.

**Step 02. Feature Engineering:** Generate new features based on hypotheses to enhance model performance.

**Step 03. Data Filtering:** Remove irrelevant columns or rows from the dataset.

**Step 04. Exploratory Data Analysis:** Analyze relationships between variables to inform feature selection and model building.

**Step 05. Data Preparation:** Prepare data for machine learning modeling, including encoding and scaling.

**Step 06. Feature Selection:** Select relevant features using algorithms like Boruta to reduce dimensionality.

**Step 07. Machine Learning Modeling:** Train and validate machine learning algorithms to predict customer interest in health insurance.

**Step 08. Hyperparameter Fine Tuning:** Optimize model parameters to improve performance.

**Step 09. Conclusions:** Evaluate model performance and provide insights for business decision-making.

**Step 10. Model Deploy:** Deploy the final model using Flask API.

## 4.0 Top 3 Data Insights

* **The older the customer, the greater the likelihood of interest in health insurance.**
* **Customers without car insurance are more likely to be interested in health insurance.**
* **Less than 40% of customers who have experienced vehicle damage are uninterested in health insurance.**

## 5.0 Machine Learning Applied

The project evaluated various machine learning models, including Dummy, Logistic Regression, Random Forest, Extra Trees, XGBoost, and LightGBM, based on precision, recall, and F1-score.

## 6.0 Machine Learning Performance

The chosen model, Logistic Regression, demonstrated a precision of 24.1% in identifying potential health insurance clients, with a recall of 98.31%. The model showed capacity to generalize to unseen data.

## 7.0 Business Results

The model enabled targeting of potential clients, with potential cost savings in sales outreach efforts. For instance, the model could identify 80% of interested customers with approximately 155,064 calls.

## 8.0 Conclusions

The final model significantly outperformed random selection, demonstrating its utility in prioritizing potential health insurance clients. The model's insights offer opportunities for cost-effective targeting in sales campaigns.

## 9.0 Lessons Learned

* Interpretation of model results is crucial for effective decision-making.
* Even modest model performance improvements can have significant business impact.
* Understanding top K scores is essential for evaluating model effectiveness.

## 10.0 Next Steps

* Continuously improve model metrics, particularly precision.
* Explore additional hypotheses to uncover further insights from the dataset.

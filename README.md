# Sentiment-Based Product Recommendation

# 

# \## 📌 Problem Statement

# 

# E-commerce has transformed the way people shop by allowing customers to order products online without physical interaction. Leading platforms such as \*\*Amazon, Flipkart, Myntra, Paytm, and Snapdeal\*\* have already set high standards in this domain.

# 

# Suppose you are working as a Machine Learning Engineer at an e-commerce company named \*\*Ebuss\*\*. The company has a wide product catalog, including:

# 

# \* Household essentials

# \* Books

# \* Personal care \& cosmetic products

# \* Medicines \& healthcare

# \* Electrical appliances

# \* Kitchen \& dining essentials

# 

# With rapid technological advancements, Ebuss aims to expand its market presence and compete with industry leaders. To achieve this, a \*\*Sentiment-Based Product Recommendation System\*\* is developed to leverage customer reviews and sentiments for smarter product recommendations.

# 

# ---

# 

# \## 🚀 Solution

# 

# \* \*\*GitHub Repository\*\*: \[Sentiment-Based Product Recommendation](https://github.com/srinivasnv2/sentiment-based-product-recommendation.git)

# ---

# 

# \## 🛠️ Built With

# 

# \* Python \*\*3.9.7\*\*

# \* scikit-learn \*\*1.0.2\*\*

# \* xgboost \*\*1.5.1\*\*

# \* numpy \*\*1.22.0\*\*

# \* pandas \*\*1.3.5\*\*

# \* nltk \*\*3.6.7\*\*

# \* Flask \*\*2.0.2\*\*

# \* Bootstrap CDN \*\*5.1.3\*\*

# 

# ---

# 

# \## ⚙️ Solution Approach

# 

# 1\. \*\*Dataset\*\*

# 

# &nbsp;  \* Available under `dataset/` folder.

# &nbsp;  \* Includes data attributes and description.

# 

# 2\. \*\*Preprocessing \& Feature Engineering\*\*

# 

# &nbsp;  \* Data cleaning, visualization, and NLP-based preprocessing applied.

# &nbsp;  \* Text features (`review\_title + review\_text`) vectorized using \*\*TF-IDF\*\*.

# 

# 3\. \*\*Handling Class Imbalance\*\*

# 

# &nbsp;  \* Applied \*\*SMOTE oversampling\*\* to balance sentiment distribution.

# 

# 4\. \*\*Model Training \& Evaluation\*\*

# 

# &nbsp;  \* Models used: Logistic Regression, Naive Bayes, Decision Tree, Random Forest, and XGBoost.

# &nbsp;  \* Target variable: `user\_sentiment` (positive = 1, negative = 0).

# &nbsp;  \* Evaluation metrics: Accuracy, Precision, Recall, F1 Score, AUC.

# &nbsp;  \* \*\*XGBoost\*\* selected as the best-performing model.

# 

# 5\. \*\*Recommendation System\*\*

# 

# &nbsp;  \* Built using \*\*Collaborative Filtering\*\* (User-User \& Item-Item).

# &nbsp;  \* Evaluated using \*\*RMSE\*\*.

# &nbsp;  \* Top 20 products identified → filtered further to Top 5 with the highest positive sentiment.

# 

# 6\. \*\*Deployment\*\*

# 

# &nbsp;  \* Models saved as pickle files (`pickle/` folder).

# &nbsp;  \* Flask API (`app.py`) used to serve predictions.

# &nbsp;  \* Frontend built with Flask Jinja templates + Bootstrap (`templates/index.html`).

# &nbsp;  \* Application deployed on \*\*Heroku\*\*.

# 

# ---

# 

# \## 📂 Key Files

# 

# \* `SentimentBasedProductRecommendation.ipynb` → Jupyter Notebook with ML \& recommendation code.

# \* `model.py` → Product filtering and sentiment prediction logic.

# \* `app.py` → Flask API for serving predictions.

# \* `templates/` → UI templates (Bootstrap + Jinja).

# \* `pickle/` → Trained ML models stored as pickle files.

# 

# ---

# 

# \## ✅ Features

# 

# \* Sentiment classification of user reviews.

# \* Handles class imbalance with oversampling.

# \* Hybrid approach combining sentiment analysis with collaborative filtering.

# \* End-to-end deployment with live demo.

# 

# ---




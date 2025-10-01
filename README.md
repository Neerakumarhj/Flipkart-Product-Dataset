# Flipkart-Product-Dataset
This is a real dataset collected from Ecommerce company Flipkart and Amazone. This dataset contain fashion related product details such as ID, Rating, Product-details and many more. This dataset is helpful for making prediction for upcoming sale discount. you can also predict the satisfaction of customer.

# 🛍️ Flipkart Fashion Dataset Analysis

## 📌 Project Overview
This project explores an **e-commerce dataset from Flipkart**.  
It contains product details such as product ID, title, ratings, categories, price, and customer reviews.  

### 🎯 Goals
- Explore product trends and customer satisfaction.  
- Identify which categories perform better in terms of ratings.  
- Analyze how factors like price and reviews impact satisfaction.  
- Build a simple machine learning model to predict whether a product may need a discount during upcoming sales.  

---

## 📂 Dataset
- Source: Flipkart dataset (downloaded from Kaggle)  
- Key Columns:
  - **id**: Unique product identifier  
  - **title**: Product name/description  
  - **Rating**: Average customer rating  
  - **maincateg**: Product category  
  - **platform**: Platform name (Flipkart)  
  - **actprice1**: Actual product price  
  - **norating1**: Number of ratings  
  - **noreviews1**: Number of reviews  
  - **star_5f … star_1f**: Distribution of star ratings  

---

## 🛠️ Steps Performed
1. **Data Cleaning**  
   - Checked for missing values and duplicates  
   - Standardized column names for easier handling  

2. **Exploratory Data Analysis (EDA)**  
   - Ratings distribution  
   - Top categories by product count and ratings  
   - Price vs Rating analysis  
   - Platform comparison  
   - Reviews and star rating breakdown  

3. **Predictive Modeling (ML)**  
   - Created a proxy target: `Discount_Needed`  
   - Features: rating, reviews, price, category, platform, star distribution  
   - Model: Random Forest Classifier  
   - Achieved ~99% accuracy with good balance between precision & recall  

---

## 📊 Key Insights
- Most products receive **4★ and 5★ ratings**, showing generally high satisfaction.  
- Certain categories dominate in product count, but highly rated categories differ.  
- Higher prices do not always mean better ratings.  
- The ML model can predict discount-need products with high accuracy, which could help in sales strategy.  

---

## 📚 Skills Learned
- Data Cleaning & Preprocessing (Pandas, NumPy)  
- Exploratory Data Analysis (Matplotlib, Seaborn)  
- Feature Engineering & Encoding (Scikit-learn)  
- Classification Modeling with Random Forest  
- Business Interpretation of ML results  
- Presenting insights in a structured, client-friendly way  

---

## 📌 How to Run
1. Clone the repo:  
   ```bash
   git clone https://github.com/yourusername/flipkart-discount-prediction.git

# 📦 Flipkart Mobile Data Web Scraping

## 📌 Project Overview
This project focuses on **web scraping mobile phone data** from Flipkart and Amazon to analyze product trends.  
The scraped dataset is transformed into a structured **DataFrame**, cleaned, and exported to a CSV file for further analysis.  
The project also includes **data visualization, encoding, scaling, and machine learning tasks** to uncover insights such as ratings distribution and price-based product analysis.

---

## ✨ Features
- Scrape mobile phone data (title, price, ratings, description, reviews)  
- Collect at least **500 rows** of data  
- Clean and preprocess the dataset (handle missing values, remove duplicates, convert data types)  
- Visualize:
  - Phones with highest ratings  
  - Products with maximum number of ratings according to price  
- Apply **bucketing** to bin prices  
- Encode categorical features using **One-Hot Encoding**  
- Scale numerical features for balanced training  
- Train and evaluate models using **train_test_split**  

---

## 🛠️ Tools & Libraries
- **Python**  
- **BeautifulSoup / Requests** – Web scraping  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical computation  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – Preprocessing, encoding, scaling, and ML model training  

---

## 📂 Dataset
- Scraped from **Flipkart & Amazon** mobile listings  
- Columns include:
  - `Title` – Name of the phone  
  - `Price` – Price of the phone  
  - `Ratings` – Average rating  
  - `Description` – Product details  
  - `Reviews` – User reviews  

---

## ⚙️ Workflow
1. **Data Collection** – Scrape product listings from Flipkart & Amazon  
2. **Data Cleaning** – Handle missing values, remove outliers, convert data types  
3. **Data Preprocessing** – Feature engineering, bucketing, encoding, scaling  
4. **Visualization** – Explore rating distributions and price vs. ratings  
5. **Model Training** – Split into train/test sets and apply ML models  
6. **Evaluation** – Measure accuracy, visualize confusion matrix, analyze results  

---

## 📊 Results
- Dataset of **500+ rows** collected and cleaned  
- Visualizations show:
  - Phones with highest ratings  
  - Products with maximum ratings by price bucket  
- Encoded and scaled dataset prepared for ML tasks  
- Train-test split applied for predictive modeling  

---

## ✅ Deliverables
- **CSV File** – Cleaned dataset  
- **Python Script (.py)** – Web scraping, preprocessing, visualization, and ML pipeline  
- **PDF Report** – Documentation of tasks, visualizations, and conclusions  

---

## 🔮 Future Scope
- Extend scraping to more e-commerce sites (Snapdeal, Myntra, etc.)  
- Automate scraping with **Selenium** for dynamic content  
- Apply advanced ML models (Random Forest for better predictions  
- Deploy as a **dashboard** using Streamlit   

---

## 👩‍💻 Author
**Lavanya B**  

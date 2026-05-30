# 📊 Exploratory Data Analysis (EDA) Project

## 📌 Project Overview

This project demonstrates a comprehensive **Exploratory Data Analysis (EDA)** workflow using multiple datasets. The notebook covers **Univariate, Bivariate, and Multivariate Analysis**, along with **Time Series Analysis**, **Text Data Analysis**, and **Customer Segmentation using PCA & K-Means Clustering**.

The goal is to extract meaningful insights, identify patterns, detect relationships between variables, and prepare data for advanced analytics and machine learning tasks.

---

## 📂 Datasets Used

### 1. Customer Sales Dataset (`cleaned_customer_sales.csv`)

Contains customer demographic and purchasing information:

* Age
* Gender
* City
* Purchase Amount
* Feedback Score
* Signup Date
* Last Purchase Date

### 2. News Dataset (`fake_or_real_news.csv`)

Used for basic Natural Language Processing (NLP):

* News Text
* Text Cleaning
* Tokenization
* Word Frequency Analysis

### 3. Weather Dataset (`weather.csv`)

Used for correlation and relationship analysis among weather-related variables.

### 4. Daily Sales Dataset (`daily_sales_data.csv`)

Used for time-series analysis:

* Daily Sales
* Trend Analysis
* Rolling Averages
* Autocorrelation Analysis

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
---

## 📈 Analysis Performed

### 1️⃣ Data Preprocessing

* Dataset loading
* Data type inspection
* Date column conversion
* Data cleaning

---

### 2️⃣ Univariate Analysis

#### Numerical Variables

* Descriptive Statistics
* Mean
* Median
* Standard Deviation
* Interquartile Range (IQR)
* Skewness

#### Visualizations

* Histogram
* Density Plot (KDE)
* Box Plot

#### Categorical Variables

* Frequency Distribution
* Count Plots

---

### 3️⃣ Date & Time Analysis

* Date Range Analysis
* Signup Trends
* Purchase Trends
* Monthly Distribution
* Time Granularity Assessment

#### Visualizations

* Monthly Signup Distribution
* Purchase Trend Line Chart
* Seasonal Decomposition
* Day-Month Purchase Heatmap

---

### 4️⃣ Text Data Analysis (NLP)

#### Text Preprocessing

* Lowercasing
* Removing Special Characters
* Tokenization

#### Analysis

* Token Count Distribution
* Most Common Words
* Stopword Removal
* Word Frequency Comparison

#### Visualizations

* Text Length Histogram
* Top Words Bar Chart

---

### 5️⃣ Bivariate Analysis

#### Numerical vs Numerical

* Correlation Matrix
* Pairwise Regression Analysis
* Scatter Plots

#### Categorical vs Numerical

* Boxplots
* Group Mean Analysis
* Group Median Analysis

#### Statistical Testing

* ANOVA Test
* Chi-Square Test of Independence

#### Visualizations

* Correlation Heatmap
* Regression Pairplots
* Stacked Bar Charts

---

### 6️⃣ Time Series Analysis

Performed on Daily Sales Data:

#### Techniques

* Lag Analysis
* Autocorrelation Function (ACF)
* Partial Autocorrelation Function (PACF)
* Rolling Mean Analysis

#### Visualizations

* Lag Plots
* ACF Plot
* PACF Plot
* Rolling Average Trend Charts

---

### 7️⃣ Multivariate Analysis

#### Interaction Analysis

* Gender + Age → Purchase Amount
* City + Feedback Score → Purchase Amount

#### Principal Component Analysis (PCA)

* Feature Standardization
* Dimensionality Reduction
* 2D Projection Visualization

#### Customer Segmentation

* K-Means Clustering
* Cluster Identification
* Cluster Profiling

#### Visualizations

* PCA Scatter Plot
* Cluster Visualization

---

## 📊 Key Insights Generated

* Customer purchasing behavior patterns.
* Demographic impact on sales.
* Seasonal purchasing trends.
* Most frequently occurring words in news articles.
* Relationships between weather variables.
* Sales autocorrelation and trend behavior.
* Customer segmentation through clustering techniques.

---

## 📁 Project Structure

```text
├── EDA.ipynb
├── cleaned_customer_sales.csv
├── fake_or_real_news.csv
├── weather.csv
├── daily_sales_data.csv
├── README.md
```

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/EDA-Project.git
cd EDA-Project
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels scikit-learn nltk
```

### Launch Jupyter Notebook

```bash
jupyter notebook EDA.ipynb
```

---

## 📚 Learning Outcomes

This project demonstrates:

* Exploratory Data Analysis (EDA)
* Statistical Data Analysis
* Data Visualization Techniques
* Time Series Analysis
* Natural Language Processing (NLP)
* Principal Component Analysis (PCA)
* Customer Segmentation using K-Means
* Hypothesis Testing (ANOVA & Chi-Square)

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a star on GitHub!

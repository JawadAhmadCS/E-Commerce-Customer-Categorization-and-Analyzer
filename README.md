# **E-Commerce Customer Categorization and Analyzer**

## **Introduction**
The **E-Commerce Customer Categorization and Analyzer** project leverages machine learning and data analysis techniques to uncover patterns in customer behavior and product categorization. By analyzing one year of e-commerce purchasing behavior, this project provides actionable insights for businesses to optimize marketing strategies and enhance product offerings.

> **Note**: While designed for learning purposes, it may contain errors, and improvements are possible as it hasn't undergone thorough testing.

---

## **Features**
- Preprocessing and cleaning of raw data, including handling missing and duplicate values.
- Detailed analysis of customer behavior and product performance.
- Product categorization using natural language processing and clustering algorithms.
- Implementation of machine learning models for customer segmentation and classification.
- Interactive and static visualizations for insightful storytelling.

---

## **Technologies Used**
- **Programming Language:** Python
- **Libraries:**
  - `numpy`: Numerical computations
  - `pandas`: Data manipulation and analysis
  - `matplotlib` & `seaborn`: Visualization libraries
  - `scikit-learn`: Machine learning algorithms and metrics
  - `plotly`: Interactive visualizations
  - `nltk`: Natural language processing tasks

---

## **Installation**
1. Clone the repository:
   ```bash
   git clone ttps://github.com/JawadAhmadCS/E-Commerce-Customer-Categorization-and-Analyzer.git
2. Navigate to the project directory:
   ```bash
   cd E-Commerce-Customer-Categorization-and-Analyzer
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
## **Dataset Overview**
This project is built on a dataset that captures **one year of e-commerce purchasing behavior**. The data includes customer orders, product details, and transaction records, enabling a comprehensive analysis of trends and patterns.

---

## **Data Preparation**
### **Data Loading**
- The dataset is loaded, and initial checks for missing and duplicate values are performed.
![Image](https://github.com/user-attachments/assets/1313734c-1b8f-4d10-92bb-fe1bb870558d)
### **Handling Missing Values**
- Missing values are identified and handled appropriately to maintain data integrity.
 ![Image](https://github.com/user-attachments/assets/3959847a-61c3-497a-a161-ab7e4e3f72d5)
 ### **Duplicate Values**
- Duplicate entries are identified and removed for accurate analysis.
  
 ![Image](https://github.com/user-attachments/assets/1be0493d-2847-4854-81ed-c4a2d21896d6)

---

## **Exploring Variables**
### **1. Analysis by Countries**
- Customer and order distribution are analyzed at the country level.
- **Visualizations:**
  - Bar charts to display customer and order counts.
  - Choropleth maps to represent global order distribution.

![Image](https://github.com/user-attachments/assets/c395aff2-ddb3-489c-88e9-42ca0fcec8d3)

### **2. Cancelled Orders**
- Transactions marked as canceled are filtered and analyzed for patterns.

### **3. StockCode and Basket Price**
- Unique `StockCodes` are examined for special transaction types.
- A new variable, **Basket Price**, calculates the total value of each purchase.

![Image](https://github.com/user-attachments/assets/fcf3a0c0-00c1-4ad9-8597-8c307dfd049e)

- **DonutChart**

![Image](https://github.com/user-attachments/assets/ed685547-93ed-48d9-bb96-064d0511b4c6)

---

## **Product Description**
### **1. Keyword Extraction**
- Using `nltk`, 100 common keywords are extracted from product descriptions.
- Part-of-Speech (POS) tagging identifies categorical keywords.
![Image](https://github.com/user-attachments/assets/e9155c9e-8ab2-4ea1-b4db-c0ed568afbc9)

### **2. Data Encoding**
- **TF-IDF** (Term Frequency-Inverse Document Frequency) is applied to measure keyword importance.
- Binary matrices track the presence of keywords in product descriptions.

---

## **Creating Clusters of Products**
### **1. K-Means Clustering**
- Products are grouped into clusters using the K-Means algorithm.
![Image](https://github.com/user-attachments/assets/220915a3-6c2d-48a7-9cdd-cde979ce5dda)

- **Silhouette Score:** Optimal clusters are determined based on this metric.
![Image](https://github.com/user-attachments/assets/2b898e4d-6b3d-4b3e-a473-6878750128a7)

### **2. Word Clouds**
- Visual representations highlight keywords for each cluster.

![Image](https://github.com/user-attachments/assets/6c3d00d2-0dc5-48de-839e-810b86c85c1a)

---

## **Customer Categories**
- Customers are segmented based on their purchasing behavior, including:
  - Number of purchases.
  - mean, and total amounts spent.

![Image](https://github.com/user-attachments/assets/3977389a-4f72-4bec-bcc4-1463a33dc7e6)

---

## **Classifying Customers**
### **1. Feature Definition**
- **X:** Represents spending patterns across product categories.
- **Y:** Indicates the customer cluster.

### **2. Models Implemented**
- Support Vector Machine Classifier (SVC)
- Logistic Regression
- k-Nearest Neighbors (k-NN)
- Decision Tree
- Random Forest

### **3. Model Evaluation**
- **Metrics:**

![Image](https://github.com/user-attachments/assets/7715c039-e373-4817-9bb5-677c1fb009d9)
![Image](https://github.com/user-attachments/assets/8bf0a19b-ab23-4e68-8cd5-07fded645743)


---

## **Visualizations and Insights**
### **1. Visualizations**
- Bar charts and choropleth maps for country-level insights.
- Word clouds for product clusters.
- Scatter plot matrices for PCA components.
- Learning curves for model evaluations.

### **2. Key Insights**
- Effective clustering highlights distinct product categories and customer behaviors.
- Machine learning models deliver varying classification accuracies, with Logistic Regression achieving the best results.
- Insights aid in designing targeted marketing strategies and product optimizations.

---

## **Conclusion**
The **E-Commerce Customer Categorization and Analyzer** showcases the potential of clustering, keyword extraction, and machine learning in deriving valuable insights. This project serves as a foundation for future advancements, such as:
- Optimizing model performance.
- Refining product clusters.
- Implementing advanced machine learning techniques for deeper insights.

---
## **Contact**
For questions, suggestions, or contributions, feel free to reach out:
- **Email:** [help.jawad@gmail.com](mailto:help.jawad@gmail.com)
- **LinkedIn:** [LinkedIn](https://linkedin.com/in/JawadAhmadCS)
  
---

## **License**

> **This project is owned by [Muhammad Jawad Ahmad](https://www.linkedin.com/in/JawadAhmadCS/) and is not the property of any institution. Feel free to use it for educational purposes.**

---



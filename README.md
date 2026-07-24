# Customer Segmentation Using Unsupervised Machine Learning

## 📌 Project Overview
Customer segmentation is the process of dividing customers into different groups based on their characteristics and purchasing behavior. This project applies the **K-Means Clustering** algorithm, an unsupervised machine learning technique, to identify customer segments that can help businesses improve marketing strategies and customer engagement.

---

## 🎯 Objectives
- Analyze customer demographic and purchasing data.
- Perform data preprocessing and feature selection.
- Apply K-Means clustering to group similar customers.
- Visualize customer segments.
- Generate insights for targeted marketing.

---

## 📂 Dataset
The project uses a customer dataset (`new.csv`) containing customer information such as:

- Customer ID
- Year of Birth
- Education
- Marital Status
- Income
- Number of Kids at Home
- Number of Teenagers at Home
- Customer Registration Date
- Recency
- Amount Spent on Wines
- Amount Spent on Fruits
- Amount Spent on Meat Products
- Amount Spent on Fish Products
- Amount Spent on Sweet Products
- Amount Spent on Gold Products
- Number of Web Purchases
- Number of Store Purchases
- Number of Catalog Purchases
- Number of Web Visits per Month
- Campaign Response Information

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / VS Code

---

## 🤖 Machine Learning Algorithm

### K-Means Clustering
K-Means is an unsupervised machine learning algorithm that groups similar data points into clusters based on feature similarity.

The optimal number of clusters was determined using the **Elbow Method**.

---

## 📊 Project Workflow

1. Import Dataset
2. Data Cleaning
3. Handle Missing Values
4. Feature Selection
5. Data Preprocessing
6. Feature Scaling
7. Determine Optimal Clusters using Elbow Method
8. Apply K-Means Clustering
9. Visualize Customer Segments
10. Analyze Cluster Characteristics

---

## 📈 Results

The K-Means model successfully grouped customers into multiple segments based on their purchasing behavior and demographic characteristics.

These customer segments can help businesses:

- Improve targeted marketing campaigns
- Identify high-value customers
- Increase customer retention
- Personalize product recommendations

---

## 📁 Project Structure

```
Customer-Segmentation/
│── new.csv
│── customer_segmentation.ipynb
│── requirements.txt
│── README.md
│── images/
│     ├── elbow_method.png
│     └── customer_clusters.png
```

---

## 🚀 Future Enhancements

- Implement DBSCAN clustering
- Apply Hierarchical Clustering
- Build an interactive dashboard using Streamlit
- Deploy the project on the web

---

## 📦 Requirements

```
pandas
numpy
matplotlib
scikit-learn
jupyter
```

Install all dependencies:

```bash
pip install -r requirements.txt
```

---

## 👨‍💻 Author

**Jagan Mohan Reddy**

---

## ⭐ Acknowledgements

This project was developed for learning and demonstrating the application of **Unsupervised Machine Learning** techniques for customer segmentation.

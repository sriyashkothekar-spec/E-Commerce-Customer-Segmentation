# E-commerce Customer Segmentation & Marketing Insights Tool

## 📑 About the Project

This project is a data-driven customer analytics tool designed for
e-commerce platforms. It applies machine learning clustering techniques
to segment customers based on purchasing behavior and transaction patterns.

The goal of the system is to help online merchants better understand their
customers and make data-informed marketing decisions. By identifying
behavioral segments such as high-value customers, frequent buyers, and
at-risk customers, businesses can personalize marketing strategies,
improve retention, and optimize sales campaigns.

The project demonstrates how machine learning and data analytics can
support SaaS-based e-commerce platforms by providing actionable insights
into customer behavior.

---

## 📂 Table of Contents

- [About the Project](#-about-the-project)
- [Technologies Used](#-technologies-used)
- [Dataset](#-dataset)
- [RFM Analysis](#-rfm-analysis)
- [K-Means Clustering](#-k-means-clustering)
- [Hierarchical Clustering](#-hierarchical-clustering)
- [Results and Insights](#-results-and-insights)
- [Installation](#-installation)
- [Usage](#-usage)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 💻 Features

- Customer segmentation using K-Means clustering
- Visualization of customer behavior patterns
- Identification of high-value and at-risk customers
- Data-driven insights for targeted marketing

---

## 💻 Technologies Used

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

---

## 📊 Dataset

- **Dataset:** Mall Customer Segmentation Data
- **Features used:**
  - CustomerID
  - Gender
  - Age
  - Annual Income
  - Spending Score
    

---

## 🧮 RFM Analysis

**RFM analysis** was performed to segment customers based on:

- **Recency:** How recently a customer purchased.
- **Frequency:** How often a customer purchases.
- **Monetary:** How much money a customer spends.

Steps included:

1. Calculating RFM metrics for each customer.
2. Scoring each metric and creating RFM segments.
3. Identifying high-value customers for loyalty programs.

---

## 📈 K-Means Clustering

- **Why used:** To group customers into segments based on features such as Annual Income and Spending Score.
- **Optimal clusters:** Determined using the **Elbow Method**.
- **Visualisations:**
  - Scatter plots showing customer clusters.
  - Cluster centroids highlighted for clarity.

---

## 🌳 Hierarchical Clustering

- **Why used:** To compare results with K-Means clustering for better segmentation insights.
- **Approach:**
  - Dendrogram plotted to find optimal number of clusters.
  - Agglomerative clustering implemented for final segmentation.
- **Results:** Explained the formation of customer groups based on hierarchical linkage.

---

## 📝 Results and Insights

- Segmented customers into distinct groups:
  - **Cluster 1:** High income, high spending – premium customers.
  - **Cluster 2:** Low income, low spending – discount seekers.
  

**Business recommendations:**

- Offer loyalty programs to premium customers.
- Design targeted campaigns for medium-tier clusters.
- Provide discounts to convert low spending groups.

**Potential Integration:**

This tool could be integrated with e-commerce platforms
such as Shopify to analyze merchant customer data and
generate actionable marketing insights.

---

## ⚙️ Installation

Install required dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy

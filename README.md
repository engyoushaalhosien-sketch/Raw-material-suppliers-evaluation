# Raw-material-suppliers-evaluation
# Procurement KPI Analysis & Supplier Segmentation (K-Means) 🚀

This project demonstrates the application of **Unsupervised Machine Learning** to transform traditional procurement data into strategic insights. By leveraging the **K-Means Clustering** algorithm, this model segments suppliers based on their performance, enabling data-driven decision-making in supply chain management.

## 📊 Project Overview
The primary goal is to categorize suppliers into distinct groups based on their historical performance metrics. This allows procurement and quality managers to identify high-value partners, mitigate risks from unstable suppliers, and optimize the overall supply chain efficiency.

## 🛠️ Tech Stack
- **Language:** Python 🐍
- **Key Libraries:**
  - `Pandas` & `NumPy`: For data preprocessing, cleaning, and feature engineering.
  - `Scikit-learn`: For implementing the K-Means algorithm and calculating performance metrics (Silhouette Score, Inertia).
  - `Matplotlib` & `Seaborn`: For advanced data visualization and cluster mapping.
- **Algorithm:** K-Means Clustering.

## 📈 Key Performance Indicators (KPIs) Analyzed
The segmentation is based on the following features:
1. **Delivery Rate:** Efficiency and timeliness of shipments.
2. **Defect Rate:** Quality metric reflecting the percentage of non-conforming products.
3. **Compliance Score:** Adherence to contractual terms and standards.
4. **Number of Orders:** Volume of business and reliability over time.

## 🔍 Cluster Insights & Strategic Actions
The model identifies four key supplier segments:
- **💎 Cluster 2 — *Strategic Partners*:** High delivery rates, low defects, and high transaction volume. 
  - *Action:* Prioritize and expand long-term collaboration.
- **🌟 Cluster 4 — *High-Potential Suppliers*:** Excellent performance metrics but currently underutilized (low order count). 
  - *Action:* Increase engagement and shift more volume to them.
- **🟠 Cluster 3 — *Unstable Suppliers*:** Low delivery rates and inconsistent compliance. 
  - *Action:* Limit dependency and initiate corrective action plans.
- **🔵 Cluster 1 — *Routine Suppliers*:** Moderate, stable performance for non-critical supplies.

## 🚀 Future Vision (Quality 4.0)
This project is a practical implementation of **Quality 4.0** principles. By integrating Machine Learning into Quality Management Systems (QMS), we move from reactive monitoring to proactive, predictive supplier management.

## 📂 How to Use
1. Clone the repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn

# Customer Segmentation using K-Means

## 📌 Project Overview
This project performs customer segmentation using the **K-Means clustering algorithm**.  
used RFM (Recency, Frequency, Monetary) analysis to identify groups of customers with similar purchasing behavior.
## Dataset
Dataset: [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)  
- Shape: ~500K rows, 8 columns  
- Columns: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country
---
## ⚙️ Steps Performed
1. Data Cleaning  
2. Feature Engineering (RFM)  
3. Scaling & Normalization  
4. Optimal K using Elbow Method  
5. K-Means Clustering  
6. Visualization of Segments  
7. Business Insights

---

## 📊 Results
- **Cluster 0**: High-value loyal customers  
- **Cluster 1**: Recent but low spenders  
- **Cluster 2**: Inactive customers  
- **Cluster 3**: Frequent but low monetary value

---

## 🛠️ Tech Stack
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Visual Studio Code
- git clone https://github.com/<rrahulrajput>/customer-segmentation-kmeans.git
cd customer-segmentation-kmeans

## How to Run:
#Clone this repository
-git clone https://github.com/<rrahulrajput>/customer-segmentation-kmeans.git
-cd customer-segmentation-kmeans


#Create a virtual environment (optional but recommended)
-python -m venv venv
-source venv/bin/activate    # Mac/Linux
-venv\Scripts\activate       # Windows


#Install dependencies
pip install -r requirements.txt


#Run the script
python src/customer_segmentation.py


#View results
-Segmentation plots will be saved in the images/ folder.
-Clustered dataset will be saved as segmented_customers.csv in the output/ folder.

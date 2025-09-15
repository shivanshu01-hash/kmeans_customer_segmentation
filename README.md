# Mall Customer Segmentation using K-Means Clustering

## Project Overview
This project demonstrates unsupervised machine learning for customer segmentation using the K-Means clustering algorithm. We analyze mall customer data to identify distinct customer groups based on their age, income, and spending habits.

## Dataset
The dataset used is the Mall Customers dataset, which contains information about customers including:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Methodology
1. Data preprocessing and exploration
2. 3D visualization of customer attributes
3. Determining optimal clusters using the Elbow Method
4. Applying K-Means clustering
5. Visualizing clusters with interactive 3D plots

## Results
The analysis identifies distinct customer segments that can help businesses tailor their marketing strategies to different customer groups.

## Technologies Used
- Python
- pandas
- numpy
- scikit-learn
- plotly
- matplotlib

## Installation
```bash
git clone https://github.com/your-username/mall-customer-segmentation.git
cd mall-customer-segmentation
pip install -r requirements.txt

Usage
Run the Jupyter notebook to see the complete analysis:

bash
jupyter notebook mall_customer_segmentation.ipynb
Or run the Python script:

bash
python mall_customer_segmentation.py

Files
mall_customer_segmentation.ipynb: Jupyter notebook with complete analysis
mall_customer_segmentation.py: Python script version
Mall_Customers.csv: Dataset
clusters_3d_auto_rotate.html: Interactive visualization of clusters
requirements.txt: Python dependencies
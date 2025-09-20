# 🛍 Customer Segmentation using Clustering

This project demonstrates *Customer Segmentation* using machine learning clustering algorithms such as *K-Means* and *DBSCAN*.  
It explores customer data from a mall dataset, performs data preprocessing, visualization, clustering, and evaluates the performance of the models.

---

## 📂 Dataset

The dataset used in this project is *Mall_Customers.csv*, containing information about mall customers:

- *Gender*: Male/Female  
- *Age*: Customer’s age (18–70)  
- *Annual Income (k$)*: Annual income in thousands of dollars  
- *Spending Score (1-100)*: Score assigned by the mall based on customer behavior  

📊 Dataset size: *200 rows × 5 columns*  
✔ No missing values  
✔ No duplicates  

---

## 🛠 Tools & Libraries

The project is implemented in *Python 3* using the following libraries:

- *pandas* → Data handling  
- *numpy* → Numerical computations  
- *matplotlib / seaborn* → Data visualization  
- *scikit-learn* → Preprocessing, clustering & evaluation  

---

## 🔎 Project Workflow

1. *Data Loading & Cleaning*
   - Loaded the dataset and removed unnecessary CustomerID column.
   - Verified missing values and duplicates (none found).

2. *Exploratory Data Analysis (EDA)*
   - Summary statistics & distribution plots.
   - Gender count visualization.
   - Boxplots & histograms for numerical features.
   - Correlation analysis.

3. *Feature Scaling*
   - Standardized numerical features (Age, Annual Income, Spending Score) using *StandardScaler*.

4. *Clustering*
   - *K-Means Clustering*
     - Elbow method used to determine optimal clusters.
     - Applied clustering and visualized customer groups.
   - *DBSCAN*
     - Identified dense regions and potential noise points.

5. *Model Evaluation*
   - *Silhouette Score* used to evaluate clustering performance.

---

## 📊 Results & Insights

- K-Means was effective in identifying distinct customer groups based on income and spending behavior.  
- DBSCAN helped detect outliers and customers that do not fit well into clusters.  
- Clustering revealed segments such as *high-income high-spenders, low-income high-spenders, and low-spending groups*.

---

## ▶ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
   cd customer-segmentation

2. Install required libraries:

pip install -r requirements.txt


3. Run the Jupyter Notebook:

jupyter notebook customer-segmentation.ipynb




---

📌 Future Improvements

Apply Hierarchical Clustering for comparison.

Use Principal Component Analysis (PCA) for dimensionality reduction.

Develop a dashboard (Streamlit/Power BI) for interactive customer insights.



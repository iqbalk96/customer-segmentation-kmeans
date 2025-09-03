# 🛍️ Customer Segmentation using K-Means

This mini-project applies basic data mining techniques for clustering mall customers based on their annual income and spending score.

## 🔍 Dataset

A simulated version of the popular mall customer dataset, containing:

* Customer ID
* Gender
* Age
* Annual Income (in thousands)
* Spending Score (1–100)

## 🧪 Methodology

* Data preprocessing and feature scaling
* Elbow method to determine optimal number of clusters
* K-Means clustering
* Visualization using Seaborn

## 📦 Requirements & Installation

1. **Install Python**
   Ensure Python **3.9+** is installed. Check version:

   ```bash
   python --version
   ```

   [Download Python](https://www.python.org/downloads/)

2. **Clone Repository**

   ```bash
   git clone https://github.com/iqbalk96/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans
   ```

3. **Create Virtual Environment**

   ```bash
   python -m venv venv
   ```

   Activate the environment:

   * **Windows**

     ```bash
     venv\Scripts\activate
     ```
   * **Mac/Linux**

     ```bash
     source venv/bin/activate
     ```

4. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

### requirements.txt

```txt
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

## 🚀 How to Run

1. Start Jupyter Notebook

   ```bash
   jupyter notebook
   ```

2. Open the notebook:

   ```
   notebooks/clustering.ipynb
   ```

3. Run cells sequentially (Shift + Enter).

4. Visualizations and clustering results will appear:

   * Elbow Method
   * Scatterplot of Customer Segmentation
   * Cluster Insights

## 📦 Tools

* Python (pandas, matplotlib, seaborn, scikit-learn)
* Jupyter Notebook

## 📈 Output

Visual clusters that help identify different customer segments based on purchasing behavior.

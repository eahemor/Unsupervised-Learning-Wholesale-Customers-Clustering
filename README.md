# Unsupervised Learning on Wholesale Customers Dataset-Clustering

This project applies **K-Means** and **Hierarchical Clustering** to segment wholesale customers based on purchasing patterns. The analysis includes **data preprocessing**, **dimensionality reduction (PCA)**, **hyperparameter tuning**, and **visualisation of clusters**.  

---

## 📊 Dataset

- **Source**: Wholesale Customers dataset  
- **Features**: Fresh, Milk, Grocery, Frozen, Detergents_Paper, Delicassen  
- **Goal**: Group customers into meaningful segments for business insights  

---

## 🔧 Preprocessing Steps

- Checked for missing values and duplicates  
- Feature scaling (StandardScaler)  
- Principal Component Analysis (PCA) for dimensionality reduction  

---

## 📚 Libraries Used

![Libraries](screenshots/libraries.png)  

---

## 📈 Visualisations & Outputs

### 📌 Introduction
![Introduction](screenshots/introduction.png)  

### 📊 Dataset Overview
![Dataset](screenshots/dataset.png)  

### 🧹 Data Cleaning
![Checking for Duplication](screenshots/checking%20for%20duplication.png)  

### ⚙️ Hyperparameter Tuning
![Hyperparameter Tuning](screenshots/Hyperparameter%20Tuning%20for%20Model%20Selection.png)  
![Hyperparameter Visual](screenshots/hyperparameter%20visual.png)  

### 📍 K-Means Clustering
![Elbow Method](screenshots/elbow-for-k-means.png)  
![K-Means Optimization](screenshots/k-means-optimization.png)  
![K-Means Cluster](screenshots/k-means-cluster.png)  
![K-Means Cluster 1](screenshots/k-means-cluster1.png)  
![K-Means Cluster 3](screenshots/k-means-cluster3.png)  

### 📍 Hierarchical Clustering
![Hierarchical Cluster](screenshots/hierarachicla-cluster.png)  

### 🧮 Model Evaluation & Comparison
![Model Evaluation](screenshots/model%20eveluation.png)  
![Comparison](screenshots/comparison.png)  

### 📑 Report Screenshots
![Report 1](screenshots/report1.png)  
![Report 2](screenshots/report2.png)  
![Report 3](screenshots/report%203.png)  
![Report 4](screenshots/report4.png)  
![Report 5](screenshots/report5.png)  
![Report 56](screenshots/report56.png)  

### 📌 PCA Visualisation
![PCA](screenshots/PCA.png)  

---

## 🧮 Models Used

- **K-Means Clustering**
- **Hierarchical Clustering**

---

## 🧾 Evaluation Metrics

- **Silhouette Score**
- **Cluster Interpretability**
- **Visual Separation in PCA Space**

---

## 📝 Conclusion

The analysis revealed distinct customer segments based on purchasing patterns.  
K-Means provided clear and interpretable clusters with an optimal number of clusters determined via the elbow method and silhouette score.  
Hierarchical clustering offered additional insights into customer relationships and subgroupings.

---

## 📁 Files

- `/screenshots/`: Markdown report visuals (text, code blocks, and output)
- `requirements.txt`: Python dependencies

---

## ▶️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/USERNAME/Unsupervised-Learning-Wholesale-Customers-Clustering.git
cd Unsupervised-Learning-Wholesale-Customers-Clustering
pip install -r requirements.txt


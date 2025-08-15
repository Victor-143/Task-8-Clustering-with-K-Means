# Task 8: Clustering with K-Means

## 📌 Objective
Perform **unsupervised learning** using the **K-Means clustering** algorithm to group similar data points without predefined labels.

---

## 🛠 Tools & Libraries
- **Python 3.x**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Scikit-learn** – K-Means, PCA, Silhouette Score
- **Matplotlib** / **Seaborn** – Data visualization

---

## 📂 Dataset
You can use any dataset relevant to clustering.  
For this example, the **Mall Customer Segmentation Dataset** is used.  
It contains details like:
- Customer ID  
- Gender  
- Age  
- Annual Income  
- Spending Score  

---

## 📋 Steps

### 1️⃣ Load & Visualize Dataset
- Import the dataset using Pandas.
- Display basic info and statistical summary.
- (Optional) Use **PCA** to reduce dimensions to 2D for visualization.

### 2️⃣ Fit K-Means & Assign Cluster Labels
- Initialize **KMeans** with chosen `n_clusters`.
- Fit the model to the dataset.
- Predict cluster labels and append them to the dataframe.

### 3️⃣ Use Elbow Method to Find Optimal K
- Loop over a range of K values.
- Calculate **inertia** (Within-Cluster-Sum-of-Squares, WCSS).
- Plot K vs. WCSS to find the “elbow point”.

### 4️⃣ Visualize Clusters with Color-Coding
- Use scatter plots to visualize clusters in 2D space.
- Assign different colors to different clusters.

### 5️⃣ Evaluate Clustering with Silhouette Score
- Use `silhouette_score()` from Scikit-learn.
- Higher score indicates better-defined clusters.

---

## 📊 Example Output
**Elbow Method Plot:**

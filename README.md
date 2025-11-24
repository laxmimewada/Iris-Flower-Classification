Iris Flower Clustering using K-Means

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to group Iris flowers into three natural clusters using four numerical features:

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

The objective is to observe whether the clusters formed align with the three real Iris species: **Setosa, Versicolor, and Virginica**.

 📌 Project Overview
This project includes:
- Loading and exploring the Iris dataset  
- Preprocessing and StandardScaler feature scaling  
- Applying the K-Means algorithm  
- Visualizing clusters using PCA  
- Comparing predicted clusters with actual species labels  

📁 Project Files

- **main.ipynb** – Complete implementation  
- **statement.md** – Problem statement and scope  
- **images/** – Architecture diagrams, workflow, PCA plots, elbow method  
- **data/iris.csv** – Dataset used  

🚀 How to Run
1️⃣ Install Required Libraries  
pip install numpy pandas matplotlib seaborn scikit-learn


2️⃣ Open the Notebook  
Open **main.ipynb** in Jupyter Notebook or VS Code.

3️⃣ Run All Cells  
Follow the steps in the notebook to generate visualizations and cluster results.

📊 Results
- K-Means successfully formed **3 clusters**  
- **Setosa** is clearly separable and forms its own cluster  
- **Versicolor** and **Virginica** show partial overlap (expected)  
- PCA visualization shows distinct grouping patterns  
- Elbow Method confirms **k = 3** as optimal  


Author  
**Laxmi Mewada**



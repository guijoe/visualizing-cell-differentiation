# DV_youssef_Eyad_Hadi
Data Visualisation Project
# Visualizing Cell Differentiation

 What is this project about?

In this project, we analyze **gene expression data from mouse embryonic stem cells** to understand how they change (differentiate) over time.

We use **data visualization and dimensionality reduction** to see patterns in the data that are impossible to see just by looking at the raw numbers.

---

## 🧬 About the Data

The dataset contains:

- Gene expression measurements from **single cells**
- **96 different genes** per cell  
- Measurements taken at different times: **0h → 168h (7 days)**
- Two types of stem cells:
  - **E14** – one embryonic stem cell line  
  - **R1** – another embryonic stem cell line  

Each row in the dataset = one cell  
Each column = expression level of a gene

---

##  What we did in this project

### **1) Visualizing individual genes (Part 2)**
We plotted how specific genes (like **Bmp4 and Nanog**) change over time using line plots.

This helped us see how gene expression evolves and how E14 and R1 behave differently.

---

### **2) Studying relationships between genes (Part 3)**

We selected a small group of important genes and:

- Created **correlation heatmaps** at:
  - Time = 0  
  - Time = 168  
- Identified the two most strongly correlated genes at each time point  
- Plotted scatter plots to visually check if the correlation made sense  

 This showed that relationships between genes change as cells differentiate.

---

### **3) Dimensionality Reduction with PCA (Part 4)**

Because 96 genes are too many to visualize at once, we used **PCA (Principal Component Analysis)** to reduce the data to **2 dimensions**.

We plotted:
- PC1 vs PC2  
- Color = Time  
- Marker shape = Cell type (E14 or R1)

 We observed a clear **differentiation trajectory**: cells move across the plot over time.

---

**4) Non-linear method: t-SNE (Part 5)**

We also used **t-SNE**, a non-linear dimensionality reduction method.

Compared to PCA, t-SNE:
- Shows clearer clusters  
- Better reveals local structure in the data  
- Makes differences between time points more visible  

---

 Notebooks in this repository

- `Ahmed_notebook.ipynb` – Ahmed’s analysis  
- `Yousef_notebook.ipynb` – Yousef’s analysis  

Each notebook contains:
- Data loading  
- Gene visualization  
- Correlation analysis  
- PCA and t-SNE plots  

---

 Main conclusions

- Gene expression changes a lot over time.  
- PCA reveals a smooth differentiation path.  
- t-SNE shows clearer clustering than PCA.  
- E14 and R1 start similarly but slowly diverge.

---

Contributors

- Eyad Abdrabu 
- Yousef Sannan
- Hadi Yousef




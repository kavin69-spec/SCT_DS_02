# 🌸 Iris Dataset EDA & Visualization

This project performs **data cleaning** and **exploratory data analysis (EDA)** on the famous **Iris dataset** using `pandas`, `seaborn`, and `matplotlib`. The goal is to understand the relationships between features, detect any outliers, and visualize species-wise differences.

---

## 📦 Dataset

The **Iris dataset** contains 150 samples of iris flowers, divided among three species:
- *Setosa*
- *Versicolor*
- *Virginica*

Each sample includes:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

The dataset is imported directly from `sklearn.datasets`.

---

## 🔍 Tasks Performed

1. **Data Loading** using `scikit-learn`
2. **Data Cleaning**
   - Checked for null values
   - Verified dataset structure and basic statistics
3. **Exploratory Data Analysis**
   - Pairplots to visualize feature distributions by species
   - Heatmap to visualize feature correlations
   - Boxplots to detect outliers and spread

---

## 📊 Visualizations

### 🔹 Pairplot: Feature Distribution by Species
Shows pairwise relationships between features colored by species.

### 🔹 Heatmap: Feature Correlations
Displays the correlation matrix of numerical features.

### 🔹 Boxplots: Outlier Detection
Visualizes the distribution and presence of potential outliers in each feature.

---

## 🛠️ Technologies Used

- Python 3.x
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](https://scikit-learn.org/)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/iris-eda.git
   cd iris-eda

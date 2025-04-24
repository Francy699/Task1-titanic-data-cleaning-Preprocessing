# 🧹 Titanic Dataset - Data Cleaning & Preprocessing

Welcome to the **Titanic Data Cleaning & Preprocessing Project**!  
In this project, we transform the raw Titanic dataset into a clean, machine learning-ready form by applying several essential preprocessing steps.

---

## 📌 Objective

The goal of this task is to **clean**, **normalize**, and **prepare the Titanic dataset** so that it's ready for machine learning modeling. We'll handle missing data, encode categorical variables, and scale numerical features.

---

## 🛠️ Tools & Libraries Used

- 🐍 Python 3.x
- 🧮 NumPy
- 📊 Pandas
- 📉 Seaborn & Matplotlib (for visualization)
- 🤖 Scikit-learn

---

## 📂 Dataset

We use the Titanic dataset available on Kaggle:  
🔗 [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🔍 Data Cleaning Steps

1. **Handling Missing Values**
   - Filled `Age` with the mean age.
   - Filled `Embarked` with the most frequent value (mode).
   - Dropped `Cabin` due to excessive missing values.

2. **Dropping Irrelevant Columns**
   - Removed `PassengerId`, `Name`, and `Ticket`.

3. **Encoding Categorical Features**
   - `Sex` encoded using Label Encoding.
   - `Embarked` encoded using One-Hot Encoding.

4. **Feature Scaling**
   - Standardized `Age` and `Fare` using `StandardScaler`.

5. **Outlier Removal**
   - Removed outliers from `Fare` using the Interquartile Range (IQR) method.

---

## 📊 Visualization

During the preprocessing process, visualization tools like **boxplots** and **heatmaps** are used to:
- Detect outliers
- Understand feature distributions
- Analyze feature correlations

---

## 💾 Output

The output is a clean DataFrame, free from null values, with scaled numerical features and encoded categorical features—ready for use in machine learning models!

---

## 🚀 Getting Started

### Clone or Download

```bash
git clone https://github.com/Francy699/titanic-data-cleaning.git
cd titanic-data-cleaning
```

### Install Requirements

```bash
pip install -r requirements.txt
```

### Run the Notebook

```bash
jupyter notebook titanic_preprocessing.ipynb
```

---

## 🧠 Learning Outcomes

- How to analyze and clean real-world datasets
- Techniques for handling missing data
- Encoding strategies for categorical variables
- Normalization & outlier removal
- Preparing data for ML workflows

---

## 📸 Screenshots (Optional)

_Screenshots of before and after cleaning or visualizations here._

![Screenshot 2025-04-24 111212](https://github.com/user-attachments/assets/f8ee25a6-8e72-45ad-8814-9fd100f54b1b)
![Screenshot 2025-04-24 121936](https://github.com/user-attachments/assets/eb69a024-aa59-4f0b-aefd-8f5811362090)
![Screenshot 2025-04-24 122002](https://github.com/user-attachments/assets/e3c172d4-b5d2-4c89-af2e-783e82cb08b3)


---

## 👤 Author

**Francy**  
📧 Email: your.francypothuraju@gmail.com 
🌐 Portfolio: [Link to Portfolio or GitHub](https://github.com/Francy699)

---

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

---

Happy Learning! 🌊🚢

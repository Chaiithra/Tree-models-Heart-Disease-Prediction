# 🫀 Heart Disease Classification Using Decision Trees & Random Forest 🌳🌲

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualizations-blueviolet?logo=plotly)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

This project focuses on detecting the presence of heart disease using a variety of medical attributes. By leveraging **tree-based machine learning models** such as **Decision Trees** and **Random Forests**, it aims to create interpretable and effective classification systems that can aid in early diagnosis and treatment decisions.

---

## 📂 Workflow Summary

1. **🔍 Data Exploration & Cleaning**
   - Loaded and cleaned a real-world heart disease dataset.
   - Removed duplicates and handled outliers using statistical techniques.

2. **📊 Exploratory Data Analysis (EDA)**
   - Visualized data using histograms, box plots, KDE plots, and correlation heatmaps.
   - Assessed feature distribution and interaction with target class.

3. **📐 Feature Engineering**
   - Renamed features for clarity.
   - Handled skewed data and applied encoding techniques.

4. **🧠 Model Building**
   - Trained a **Decision Tree** classifier for high interpretability.
   - Trained a **Random Forest** classifier for robust generalization.
   - Visualized decision trees using `Graphviz`.

5. **📈 Evaluation**
   - Assessed model performance using metrics like accuracy, precision, recall, F1-score, and confusion matrices.
   - Addressed overfitting through comparison of train-test accuracies.

---

## 📁 Folder Structure

```bash
heart-disease-prediction/
│
├── Heart_Disease_EDA_Tree_Models.ipynb   # 📓 Main notebook with EDA & model training
├── heart.csv                             # 📄 Dataset used for analysis
├── README.md                             # 🧾 Project documentation (this file)
├── LICENSE                               # 📃 MIT License
```

---

## 🎯 Key Insights

- Age, cholesterol, maximum heart rate, and ST depression were key indicators of heart disease.
- Males showed slightly higher heart disease rates than females in this dataset.
- Random Forest consistently outperformed Decision Tree in terms of generalization.
- Proper outlier handling and encoding significantly improved model accuracy.

---

## 🧪 Technologies Used

| Tool/Library        | Purpose                           |
|---------------------|-----------------------------------|
| `Pandas`            | Data manipulation & cleaning      |
| `NumPy`             | Numerical operations              |
| `Seaborn/Matplotlib`| Visualization                     |
| `Scikit-learn`      | ML models, metrics, data splitting|
| `Graphviz`          | Tree model visualization          |

---

## 📉 Model Performance Snapshot

| Model          | Training Accuracy | Testing Accuracy |
|----------------|-------------------|------------------|
| Decision Tree  | 🚀 High (~100%)    | ⚠️  Slight Overfitting (~79%) |
| Random Forest  | ✅ Balanced (~98%) | ✅ Good Generalization (~86%) |

---

## 🔮 Future Work

- 📊 Use `GridSearchCV` to fine-tune hyperparameters.
- 🔁 Implement cross-validation for more reliable accuracy metrics.
- 🧼 Integrate advanced feature selection techniques.
- 🌐 Build a Streamlit/Flask app for public use.

---

## 📁 How to Use

**1. Clone the Repo**
```bash
git clone https://github.com/Chaiithra/Tree-models-Heart-Disease-Prediction.git
```

**2. Navigate to Project Directory**
```bash
cd heart-disease-prediction
```

**3. Run the Notebook**
```bash
jupyter notebook Tree-models-Heart-Disease-Prediction.ipynb
```

---

## 🤝 Contribution

Want to contribute?

- ⭐ Star this repo to support the work  
- 🐞 Found a bug or improvement? Open an issue  
- 🚀 Fork and submit a pull request with enhancements  

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

---

## 🙌 Acknowledgements

- **Dataset**: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)  
- **Libraries Used**: Scikit-learn, Pandas, Seaborn, Graphviz, Matplotlib, NumPy

---

## 📧 Contact  
Made with ❤️ by **Chaiithra Thota**  

- 🔗 [Connect on LinkedIn](https://www.linkedin.com/in/chaiithrathota/)  
- 🐙 [View on GitHub](https://github.com/Chaiithra)  
- 🐦 [Follow on Twitter](https://x.com/DebugDiary_)  

---

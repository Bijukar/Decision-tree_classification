# Decision-tree_classification

## 🐧 Decision Tree Classification on Penguins Dataset

This project demonstrates how to build, tune, and evaluate a **Decision Tree Classifier** using the **Palmer Penguins dataset**. The aim is to predict the species of penguins based on features like bill length, flipper length, and body mass.

---

## 📌 Dataset

- **Source**: [Palmer Penguins Dataset on Kaggle](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data)
- **Features Used**:
  - `bill_length_mm`
  - `bill_depth_mm`
  - `flipper_length_mm`
  - `body_mass_g`
  - `island`, `sex` (encoded)
- **Target**:
  - `species` (Adelie, Chinstrap, Gentoo)

---

## 🛠️ Steps Involved

1. **Import Libraries**
2. **Load and Clean Data**
3. **Exploratory Data Analysis (EDA)**
4. **Feature Encoding and Scaling**
5. **Train-Test Split**
6. **Model Building (DecisionTreeClassifier)**
7. **Hyperparameter Tuning (GridSearchCV)**
8. **Evaluation**:
   - Classification Report
   - Confusion Matrix
   - Decision Tree Visualization
9. **Model Saving using `joblib`**

---

## 📊 Evaluation Metrics

- **Accuracy**
- **Precision / Recall / F1-Score**
- **Classification Report**

---

## 📈 Visualizations

- Pairplot of Features
- Count plot of target
- Decision Tree Diagram (`plot_tree`)
- Confusion Matrix (colored heatmap)

---

## 📁 Files in Repository

| File | Description |
|------|-------------|
| `decision_tree_classification.ipynb` | Main notebook with full code |
| `decision_model.joblib` | Trained model file |
| `README.md` | Project documentation |
| `requirements.txt` | Python libraries used |

---

## 🧪 Libraries Required

```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
joblib

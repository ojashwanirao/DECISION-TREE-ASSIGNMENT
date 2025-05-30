# 🌳 Decision Tree Practical Assignments – Machine Learning (Google Colab)

This repository contains practical solutions for working with **Decision Trees** using Python and **scikit-learn** in Google Colab. Each question is clearly marked in the code with comments like `# Q1`, `# Q2`, etc., to help you identify solutions easily.

---

## 📚 Dataset Used

- **Iris Dataset** (from `sklearn.datasets`) for classification tasks.
- **California Housing Dataset** (from `sklearn.datasets.fetch_california_housing`) for regression tasks.

---

## ✅ Questions and Practical Descriptions

| Question No. | Description |
|--------------|-------------|
| Q1 | Train a Decision Tree Classifier on the Iris dataset and print model accuracy |
| Q2 | Use Gini Impurity as criterion and print feature importances |
| Q3 | Use Entropy as criterion and print model accuracy |
| Q4 | Train a Decision Tree Regressor on housing dataset, evaluate with MSE |
| Q5 | Visualize a trained Decision Tree Classifier using `graphviz` |
| Q6 | Train a Decision Tree Classifier with `max_depth=3` and compare with full tree |
| Q7 | Train with `min_samples_split=5` and compare accuracy |
| Q8 | Apply feature scaling before training and compare with unscaled accuracy |
| Q9 | Use One-vs-Rest strategy for multiclass classification |
| Q10 | Display feature importance scores |
| Q11 | Use `max_depth=5` in Decision Tree Regressor and compare with default |
| Q12 | Apply Cost Complexity Pruning (CCP) and visualize effect on accuracy |
| Q13 | Evaluate classifier using Precision, Recall, and F1-Score |
| Q14 | Visualize Confusion Matrix using seaborn |
| Q15 | Use GridSearchCV to find optimal `max_depth` and `min_samples_split` |
---

## 🛠️ Installation & Setup (Google Colab Recommended)

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `.ipynb` notebook provided or copy-paste the code blocks.
3. Run each cell sequentially. Required libraries:
   ```bash
   pip install matplotlib seaborn graphviz scikit-learn

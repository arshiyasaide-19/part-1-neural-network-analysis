# Part 1 - Neural Network Analysis
## Customer Churn Prediction using Neural Networks

### Project Overview
This project builds and evaluates a neural network model to predict customer churn using a synthetic dataset. It covers data preprocessing, model building, training, evaluation, and hyperparameter experimentation.

---

### Repository Structure

```
part-1-neural-network-analysis/
├── notebook.ipynb
├── requirements.txt
├── README.md
└── results/
    ├── model_comparison_table.csv
    ├── evaluation_outputs.md
    └── confusion_matrix.md
```

---

### Dataset
- **File:** `customer_churn_nn.csv`
- **Rows:** 2000 | **Columns:** 12
- **Target:** `Churn` (0 = No, 1 = Yes)
- Dataset is synthetic and provided as part of the assignment pack.
- Not uploaded to GitHub as per assignment instructions.

---

### Tasks Completed

| Task | Description |
|------|-------------|
| Task 1 | Dataset Understanding - EDA, shape, nulls, distribution |
| Task 2 | Data Preprocessing - encoding, scaling, train-test split |
| Task 3 | Neural Network Model Building |
| Task 4 | Model Training and Evaluation |
| Task 5 | Hyperparameter Experimentation (3 experiments) |
| Task 6 | Final Reflection |

---

### Results Summary

| Experiment | Hidden Layers | Neurons | Batch Size | Epochs | Test Accuracy |
|------------|--------------|---------|------------|--------|---------------|
| Exp 1 | 1 | 32 | 32 | 30 | 86.5% |
| Exp 2 | 2 | 64, 32 | 32 | 50 | 96.25% |
| Exp 3 | 3 | 128, 64, 32 | 16 | 50 | 97.0% |

**Best Model:** Experiment 3 with 97% test accuracy.

---

### Tools and Libraries
- Python 3
- TensorFlow / Keras
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

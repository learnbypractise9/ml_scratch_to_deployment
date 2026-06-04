# 🧠 ML From Scratch to Deployment

> A structured journey through Machine Learning — built with conceptual depth and real-world projects.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![NumPy](https://img.shields.io/badge/NumPy-from--scratch-green?logo=numpy)
![Sklearn](https://img.shields.io/badge/sklearn-practical-orange?logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## 👋 About This Repository

This repo documents my hands-on ML learning process — from mathematical foundations to deployed models. Each concept is:

- **Derived from first principles** — math and intuition explained, not just copied
- **Implemented from scratch** — using NumPy before reaching for sklearn
- **Applied end-to-end** — real datasets, clean pipelines, measurable results

Designed to reflect how I actually think and learn, not just what I can google.

---

## 🗺️ Roadmap

| Stage | Topics | Status |
|---|---|---|
| **01 · Foundations** | Linear Algebra, Probability, NumPy/Pandas | 🔄 In Progress |
| **02 · Supervised Learning** | Linear & Logistic Regression, Trees, SVM, Boosting | 📅 Planned |
| **03 · Unsupervised Learning** | KMeans, PCA | 📅 Planned |
| **04 · Neural Networks** | Perceptron, MLP, Backprop, CNN | 📅 Planned |
| **05 · End-to-End Projects** | See below | 📅 Planned |

---

## 🚀 Projects

| # | Project | Concepts Applied | Dataset | Highlights |
|---|---|---|---|---|
| 01 | [House Price Prediction](./05_projects/01_house_price_prediction/) | Linear Regression, Feature Engineering, Regularization | Ames Housing | Custom loss curves, residual analysis |
| 02 | [Customer Churn Prediction](./05_projects/02_customer_churn/) | Logistic Regression, Random Forest, XGBoost | Telco Churn | Class imbalance handling, SHAP explainability |
| 03 | [Image Classifier](./05_projects/03_image_classifier_cnn/) | CNN, Data Augmentation, Transfer Learning | CIFAR-10 | Grad-CAM visualizations |

---

## 📁 Repository Structure

```
ml-from-scratch-to-deployment/
│
├── 01_foundations/              # Math prerequisites
├── 02_supervised_learning/      # Regression → Boosting
│   └── {algorithm}/
│       ├── concept.md           # Math + intuition
│       ├── from_scratch.ipynb   # NumPy implementation
│       └── sklearn_usage.ipynb  # Practical workflow
├── 03_unsupervised_learning/
├── 04_neural_networks/
└── 05_projects/                 # End-to-end, production-style
    └── {project}/
        ├── README.md
        ├── notebooks/           # EDA + experiments
        ├── src/                 # Clean Python scripts
        └── results/             # Metrics + visualizations
```

---

## 🧩 How Each Concept Module Is Structured

Every algorithm folder follows the same pattern:

1. **`concept.md`** — derivation, intuition, when to use it, failure modes
2. **`from_scratch.ipynb`** — pure NumPy implementation, step by step
3. **`sklearn_usage.ipynb`** — clean, practical workflow on a real dataset

This separation makes it easy to distinguish *understanding* from *usage*.

---

## 🛠️ Setup

```
git clone https://github.com/learnbypractise9/ml_scratch_deployment.git
cd ml_scratch_deployment
pip install -r requirements.txt
jupyter notebook
```

**Core dependencies:** `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `jupyter`

---

## 📬 Contact

**Ashwin Bhandurge** · [LinkedIn](#) · [Email](learnbypractise9@gmail.com)

> *"The best way to learn ML is to rebuild it."*

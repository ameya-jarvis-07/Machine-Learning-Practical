# 🚀 Machine Learning Practical Programs – README
## 📚 Overview
This repo is a collection of all the machine learning practicals I did while being in 3rd year (5th semester) [2026-27]. This README covers interactive Jupyter notebook implementations for various Machine Learning practicals. Each practical is split into a core Experiment (foundational concept) and an accompanying Activity (real-world application/extension).

### 1️⃣ Practical 1 – Decision Trees (Classification & Regression) 🌳
* **Experiment 1 (practical1.ipynb):** Implements a **DecisionTreeClassifier** using the classic *Iris Dataset* to classify flower species based on physical features.
  * **Run:** Open the notebook in a Jupyter environment or VS Code and execute the cells sequentially to load data, split into train/test sets, and train the model.
  * **Usage:** Outputs the dataset structure and evaluates the model performance using an accuracy score.

* **Activity 1 (activity1.ipynb):** Explores a **DecisionTreeRegressor** using a *Supermarket Dataset* to predict sales profit based on product and regional categorical attributes.
  * **Run:** Run the notebook to see features preprocessed via one-hot encoding (`pd.get_dummies`), followed by model fitting and data visualization.
  * **Usage:** Displays data analysis summaries and plots a scatter plot tracking *Sales vs Profit*.

## ⚙️ Requirements and Execution Instructions
1. Ensure you have Python installed alongside package managers like `pip`. 🛠️
2. Install the necessary data science and machine learning libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn notebook

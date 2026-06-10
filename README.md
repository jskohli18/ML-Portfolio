Machine Learning & Deep Learning Portfolio

Welcome! This repository tracks my journey through foundational machine learning and deep learning concepts.
It covers everything from basic data preprocessing and optimization loops to building neural networks from scratch.

Repository Structure

1. [Categorical Encoding & Feature Engineering](./ohe.ipynb)
--What it does: Predicts property prices using multiple linear regression based on spatial area and regional town inputs.
--Key Focus: Explores the mathematical constraints of handling nominal string data. It compares Pandas `get_dummies` against Scikit-Learn’s `ColumnTransformer` + `OneHotEncoder`.
--Tech Stack: Python, Pandas, NumPy, Scikit-Learn

2. [Hyperparameter Optimization via GridSearchCV](./GridSearchCV.ipynb)
--What it does: Compares three different AI models (SVM, Random Forest, and Logistic Regression) automatically to find the best settings for each.
--Key Focus: Uses a simple python loop with 5-Fold Cross-Validation to test different model settings without rewriting code or overfitting the data.
--Tech Stack: Python, Scikit-Learn, Pandas

3. [Heart Disease Classification Engine](./heartDisease.ipynb)
--What it does: Evaluates clinical patient metrics (cholesterol, age, chest pain types) to predict the presence of cardiovascular disease.
--Key Focus: Focuses on medical accuracy by looking at the Confusion Matrix and prioritizing 'Recall.' This ensures the model rarely misses a sick patient (minimizing False Negatives), which is much more important than just looking at overall accuracy.
--Tech Stack: Python, Pandas, Scikit-Learn

4. [XOR Neural Network from Scratch](./XOR.ipynb)
--What it does: Resolves the classic, non-linearly separable XOR logic problem by engineering a Multilayer Perceptron (MLP) Neural Network entirely from scratch.
--Key Focus: Deep learning mathematics. Instead of using high-level frameworks like PyTorch or TensorFlow, this project utilizes pure `NumPy` to map out raw forward propagation, hidden layer activation tracking, backpropagation calculus, and gradient descent weight updates.
--Tech Stack: Python, NumPy

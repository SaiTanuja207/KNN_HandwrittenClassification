# 🧠 KNN – Handwritten Digit Classification

This project demonstrates handwritten digit classification (0–9) using the **K-Nearest Neighbors (KNN)** algorithm on the **sklearn digits dataset**.

The objective of this task is to understand how **distance-based classification** works and how tuning the value of **K** impacts the model performance.

---

## 📌 Dataset Used

- Dataset: `load_digits()` from `sklearn.datasets`
- Total samples: **1797 images**
- Image size: **8 x 8 pixels**
- Classes: **Digits from 0 to 9**

Each image is flattened into 64 features (8×8).

---

## 🛠️ Tools & Libraries

- Python
- Scikit-learn
- Matplotlib
- NumPy

---

## 🚀 Steps Performed

1. Loaded the digits dataset and inspected its structure.
2. Visualized sample digit images to understand the data.
3. Split the dataset into training (80%) and testing (20%).
4. Applied **StandardScaler** for feature scaling (important for KNN).
5. Trained KNN model with **K = 3**.
6. Tested multiple K values: **3, 5, 7, 9**.
7. Plotted **Accuracy vs K** graph to find the best K.
8. Generated **Confusion Matrix** to analyze misclassifications.
9. Displayed 5 test images with their predicted labels.

---

## 📊 Results

- Best K value selected based on highest accuracy from the graph.
- High classification accuracy achieved on test data.
- Confusion matrix shows very few misclassifications.
- Model successfully predicts handwritten digits.

---

## 📈 Output Visualizations

✔️ Accuracy vs K graph  
✔️ Confusion Matrix  
✔️ Predicted digit images  

---

## ❓ Interview Questions & Answers

### What is K in KNN?
K represents the number of nearest neighbors considered while classifying a new data point.

### Why is feature scaling required for KNN?
Because KNN uses distance calculations. If features are not scaled, larger values dominate the distance.

### What is Euclidean Distance?
It is the straight-line distance between two points in space, used by KNN to find nearest neighbors.

### What happens if K is too low?
Model may **overfit** (very sensitive to noise).

### What happens if K is too high?
Model may **underfit** (too generalized).

### Limitations of KNN
- Slow for large datasets
- High memory usage
- Sensitive to irrelevant features

---

## ✅ Conclusion

This project helped in understanding:

- How KNN works as a distance-based classifier
- Importance of feature scaling
- How to tune hyperparameter K
- How to evaluate model performance using accuracy, graphs, and confusion matrix

KNN proved to be an effective algorithm for handwritten digit classification.

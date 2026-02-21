# Handwritten Digit Classification using Multiple Supervised Learning Algorithms

## 📌 Problem Definition

Handwritten digit recognition is a classic classification problem in machine learning.  
The goal of this project is to classify grayscale images of handwritten digits (0–9) using supervised learning algorithms and compare their performance using statistical evaluation metrics.

This project focuses on analyzing different models and understanding their generalization ability through bias-variance analysis.

## 📊 Dataset

This project uses the `load_digits()` dataset from Scikit-learn.

**Dataset Details:**
- Total Samples: 1797
- Image Size: 8 × 8 pixels
- Features per Image: 64
- Number of Classes: 10 (digits 0–9)
- Data Type: Grayscale images

Each image is flattened into a 64-dimensional feature vector for model training.

## ⚙️ Approach

The project follows the standard supervised machine learning pipeline:

1. Data Loading
2. Data Exploration and Visualization
3. Train-Test Split (80% training, 20% testing)
4. Model Training using multiple algorithms
5. Model Evaluation using statistical metrics
6. Performance Comparison
7. Bias–Variance Analysis
8. Batch Prediction on custom input images

## 🤖 Models Used

The following supervised learning algorithms were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## 📈 Evaluation Metrics

Model performance was evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Training vs Testing Accuracy Comparison (Bias–Variance Analysis)

## 📊 Results

After training and evaluation:

- SVM achieved the highest testing accuracy.
- KNN also performed strongly with competitive accuracy.
- Logistic Regression performed well but slightly lower than SVM.
- Training and testing accuracy were close, indicating good generalization and low overfitting.

The confusion matrix shows strong diagonal dominance, indicating correct classification for most digits.

## 🧠 Bias–Variance Analysis

- If training accuracy >> testing accuracy → Overfitting
- If both accuracies are low → Underfitting
- In this project, SVM demonstrated a good balance between bias and variance.

 

## 📁 Project Structure
```
Handwritten-Digit-Classification/
│
├── digit_classification_project.ipynb
├── README.md
├── requirements.txt
```

## 🚀 How to Run the Project

1. Clone the repository:
   ```git clone https://github.com/your-username/your-repo-name.git```
2. Install dependencies:
   ```pip install -r requirements.txt ```

3. Open the notebook:
   ```jupyter notebook```
4. Run all cells to reproduce results.
   
## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Pillow


## 📌 Conclusion

This project demonstrates how multiple supervised learning algorithms can be applied to a multi-class classification problem and evaluated using statistical performance metrics.

Among the tested models, SVM achieved the best overall performance while maintaining good generalization.

The project successfully illustrates core machine learning concepts including:
- Supervised learning
- Multi-class classification
- Model comparison
- Confusion matrix analysis
- Bias–Variance tradeoff

## 👤 Author
Janhavi Pandey


# Credit Card Fraud Detection Using Machine Learning

# Table of Contents
1. [Project Description](#project-description)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation and Setup](#installation-and-setup)
5. [How It Works](#how-it-works)
6. [Project Structure](#project-structure)
7. [Results and Evaluation](#results-and-evaluation)
8. [Future Scope](#future-scope)
9. [Contributors](#contributors)

---

# Project Description

This project focuses on creating an efficient Credit Card Fraud Detection System using machine learning. By leveraging Python and scikit-learn, it tackles the challenge of identifying fraudulent credit card transactions in real-time. The solution is designed to minimize false positives and negatives, offering a scalable and accurate fraud detection mechanism that can be seamlessly integrated with payment systems.

The key components of this project include data preprocessing for imbalanced datasets, applying machine learning algorithms like Logistic Regression and Random Forest, and optimizing their performance for better precision and recall.

---

# Features
- Preprocessing: Handle imbalanced datasets using oversampling techniques like SMOTE.
- Algorithms: Logistic Regression, Random Forest, Decision Tree Classifier, and Gradient Boosting.
- Evaluation Metrics: Precision, Recall, F1-score, and ROC-AUC.
- Real-Time Application: Framework for detecting fraudulent transactions with minimal latency.
- User Interface: Built using Tkinter to display predictions interactively.

---

# Technologies Used
- Programming Language: Python
- Libraries:
  - Data Analysis: `pandas`, `NumPy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
- User Interface: `Tkinter`

---

# Installation and Setup

1. Clone the Repository
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. Install Dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Application
   ```bash
   python app.py
   ```

---

# How It Works

1. Data Preprocessing
   - Handle missing values and normalize datasets.
   - Balance the dataset using oversampling techniques like SMOTE.

2. Model Training
   - Train and evaluate models such as Logistic Regression, Random Forest, and Gradient Boosting.
   - Optimize model parameters using Grid Search.

3. Fraud Detection
   - Predict fraudulent transactions on test data.
   - Visualize results using precision, recall, F1-score, and ROC curves.

4. Interactive UI
   - Provide fraud prediction through a Tkinter-based user interface.

---

# Project Structure
```
CreditCard-FD/
│
├── data/                  # Dataset files
├── models/                # Saved models and training scripts
├── notebooks/             # Jupyter notebooks for EDA and development
├── app.py                 # Main application file (Tkinter UI)
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

# Results and Evaluation
- Achieved high accuracy and reliable performance using:
  - Logistic Regression: Balanced precision and recall.
  - Random Forest: Optimal for imbalanced datasets.
  - Gradient Boosting: Achieved the best ROC-AUC score.
- Visualization of results with confusion matrices, ROC curves, and F1-scores.

---

# Future Scope
- Deploy the application as a web service for broader accessibility.
- Explore deep learning techniques for fraud detection.
- Integrate with real-time transaction systems to test scalability.

---

# Contributors
- Mahadev Akale
- Rahul Bhosale
- Pratik Nimangare
- Jayshree Arerao
- Guided by: Prof. U.S. Gatkul
```

This `README.md` covers all the necessary details and provides a clear, professional structure for your project documentation. Adjust the repository URL and additional details as per your project's specifics.

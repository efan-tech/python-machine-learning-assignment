# python-machine-learning-assignment
Ai-assignment
*NAME* Albert wanjohi

## Project Overview
This repository contains Python scripts for supervised and unsupervised machine learning assignmentS.

###  Supervised Learning Project (`supervised_ml.py`)
- Uses `LinearRegression` from `sklearn.linear_model`.
- Trains on a dataset mapping hours studied to exam scores, formats features into 2D arrays, and predicts exam performance based on user input.

###  Unsupervised Learning Project (`unsupervised_ml.py`)
- Uses `KMeans` from `sklearn.cluster` and `StandardScaler` from `sklearn.preprocessing`.
- Analyzes customer spending and visit data, clustering them into $3$ groups (`n_clusters=3`, `random_state=42`, `n_init=10`).


## Installation & Running Instructions

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/efan-tech/python-machine-learning-assignment.git](https://github.com/efan-tech/python-machine-learning-assignment.git)
   cd python-machine-learning-assignment
   ```


2.  **Install dependencies **

   ```bash
   pip install -r requirements.txt

   ```
   
3.   **Run the script **
for supervised

  ```bash 
python supervised_ml.py
  ```
for unsupervised 
 ```bash
python unsupervised_ml.py
 ```

   

# Theory Questions

**What is supervised machine learning?**
   A type of machine learning where the model is trained on a labeled dataset.

2. **What is unsupervised machine learning?**
   A type of machine learning where the model works with unlabeled data.

3. **Explain the difference between supervised and unsupervised learning.**
   Supervised learning requires labeled data to learn a linear regression function from inputs to a known target output, whereas unsupervised learning analyzes unlabeled data to find inherent patterns or clusters without predefined target answer.

4. **Why is Linear Regression considered supervised learning?**
   Because it learns from the data and find a pattern within which every other input is predicted from.

5. **Why is K-Means considered unsupervised learning?**
   Because it groups data points together based on feature similarities  without requiring any labels or target outputs.

6. **What is the difference between fit() and predict()?**
   fit() trains the model using the dataset so it can learn patterns and relationships, while predict() uses that trained model to estimate outcomes for new, unseen data.

7. **Give two real-world applications of supervised learning and two of unsupervised learning.**
   - Supervised learning: House price prediction and spam email detection.
   - Unsupervised learning: Customer segmentation and fraud detection like a preson receiving ahuge amount of money in there account.

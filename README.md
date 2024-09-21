# Sentiment Analysis on Amazon Product Reviews

## Project Overview
This project aims to perform sentiment analysis on Amazon product reviews to classify them as positive or negative. Utilizing various machine learning models, the goal is to analyze the textual content of reviews and predict sentiments effectively.

## Dataset Overview
The dataset consists of Amazon product reviews and includes the following columns:
- **`reviewText`**: The textual content of the review.
- **`Positive`**: A binary label indicating sentiment (1 for positive, 0 for negative).

## Steps Involved

### 1. Data Preprocessing
- Handled missing values.
- Preprocessed the `reviewText` by:
  - Lowercasing
  - Removing stop words and punctuation
- Split the dataset into training and testing sets.

### 2. Model Selection
Implemented the following machine learning models for sentiment classification:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- Naïve Bayes
- Gradient Boosting (e.g., XGBoost)

### 3. Model Training
Trained each selected model using the training dataset, employing appropriate vectorization techniques such as TF-IDF for the text data.

### 4. Formal Evaluation
Evaluated the performance of each model on the testing set using metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### 5. Hyperparameter Tuning
Conducted hyperparameter tuning for selected models using techniques like Grid Search, with explanations of chosen hyperparameters.

### 6. Comparative Analysis
Compared the performance of different models based on evaluation metrics, identifying strengths and weaknesses.

### 7. Conclusion
Summarized findings, insights into challenges faced, and lessons learned throughout the project.

## Key Results and Visualizations
- Performance metrics of each model are included in the results section.
- Visualizations demonstrate model comparisons and significant findings.

## Code Submission
The repository includes well-commented code for each step of the project, along with comprehensive documentation.


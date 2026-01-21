# Restaurant Dataset Classification Using Naive Bayes on Snowflake Cloud Platform

## Project Overview
This project demonstrates a **cloud-based classification system** where a **restaurant dataset** stored in the Snowflake cloud platform is used to train and evaluate a **Naive Bayes classifier**.

Naive Bayes is a probabilistic supervised learning algorithm based on Bayes’ Theorem and is efficient for classification tasks with structured data.

---

## Objectives
- To use Snowflake as a cloud platform for restaurant data
- To apply Naive Bayes for supervised classification
- To analyze classification performance on restaurant data
- To understand probabilistic learning models

---

## Cloud Platform
### Snowflake
- Cloud-based data warehouse
- Used for storing and managing restaurant dataset
- Provides scalable access to structured data

---

## Dataset Description
- **Dataset Name:** Restaurant Dataset
- **Domain:** Restaurant / Food Service Analytics
- **Storage:** Snowflake Cloud Platform
- **Learning Type:** Supervised Learning
- **Task:** Classification

Each record represents restaurant-related information with a corresponding class label.

###  Example Attributes
- Restaurant type  
- Location  
- Pricing range  
- Service quality  
- Customer feedback  
- Target class label  

---

## Algorithm Used
### Naive Bayes
- Supervised classification algorithm
- Based on Bayes’ Theorem
- Assumes feature independence
- Fast and efficient for large datasets
- Implemented using `scikit-learn`

---

## Tools & Technologies
- Python  
- Jupyter Notebook / Google Colab  
- Pandas  
- NumPy  
- Scikit-learn  
- Snowflake  

---

## Project Workflow
1. Store restaurant dataset in Snowflake
2. Load data into Python environment
3. Preprocess the dataset
4. Split data into training and testing sets
5. Train Naive Bayes classifier
6. Predict class labels
7. Evaluate classification performance

---

## Evaluation Metrics
- Accuracy Score  
- Confusion Matrix  
- Classification Report  
  - Precision  
  - Recall  
  - F1-score  

---

## File Description
| File Name | Description |
|----------|-------------|
| `snowflake_naive_bayes_restaurant_classification.ipynb` | Main notebook |
| `README.md` | Project documentation |

---

## Future Enhancements
- Compare with Logistic Regression and KNN
- Test different Naive Bayes variants
- Deploy as a cloud-based ML service
- Use real-time restaurant data


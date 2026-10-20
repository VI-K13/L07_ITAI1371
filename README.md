# Module 07 Lab Model Evaluation

**Course:** ITAI-1371 – Machine Learning  
**Group:** 1  
**Team Members:** Viktoriya Kurmisheva, Tien Manh Nguyen, Zaid Alayedy  
**Professor:** Viswanatha Rao

## Overview

In this lab, our group continued working with the Titanic dataset and used Logistic Regression to predict passenger survival. This time, we focused on evaluating our model beyond just checking its accuracy. We explored the Confusion Matrix, Classification Report, and Cross-Validation to better understand how well our model performed and where it made mistakes.

## What We Did

- **Confusion Matrix:** Created a heatmap to compare actual survival results with our model's predictions and identify correct and incorrect predictions.
- **Classification Report:** Used Precision, Recall, and F1-Score to understand how well our model predicted each survival category.
- **Cross-Validation:** Performed 5-fold Cross-Validation to check how consistently our model performed across different parts of the dataset.
- **Knowledge Check:** Answered questions about the importance of Precision, Recall, and Cross-Validation in real-world situations.

## Results

Our Logistic Regression model achieved approximately **80% accuracy** on the test set. The Confusion Matrix showed that the model correctly identified 90 passengers who did not survive and 54 passengers who survived.

The Classification Report showed that the model performed slightly better when predicting passengers who did not survive. Our 5-fold Cross-Validation also produced an average accuracy of **78.68%**, with a standard deviation of **0.0094**.

## Tools and Libraries

- Python
- Google Colab / Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## What We Learned

This lab helped us understand why accuracy alone cannot explain everything about a model's performance. We learned how different evaluation metrics reveal different types of prediction mistakes and why choosing the right metric depends on the problem. We also saw how Cross-Validation helps us check whether a model performs consistently instead of relying on a single train-test split.

## Repository Files

- `L07_Group1_ITAI1371.ipynb` – Completed lab notebook with code, results, and Knowledge Check answers.
- `L07Journal_R_Group1_ITAI1371.docx` – Group Reflection Journal.
- `L07Journal_C_Group1_ITAI1371.docx` – Team Member Contribution Journal.

## Group Contributions

- **Viktoriya Kurmisheva:** Classification Report, Knowledge Check Question 2, and Reflection Journal.
- **Tien Manh Nguyen:** Confusion Matrix, Knowledge Check Question 1, and final notebook review.
- **Zaid Alayedy:** Cross-Validation, Knowledge Check Question 3, and Team Member Contribution Journal.

All group members contributed to the lab discussions and understanding of the results.

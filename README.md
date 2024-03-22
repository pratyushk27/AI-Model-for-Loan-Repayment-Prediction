# AI-Model-for-Loan-Repayment-Prediction

# Introduction:
In today's financial landscape, lending institutions face the challenge of identifying reliable borrowers to minimize the risk of default and maximize returns. To address this challenge, we propose the development of an AI model that predicts whether a borrower will fully repay a loan or not. This predictive model will assist lending institutions in making informed decisions regarding loan approvals, thereby enhancing the efficiency of their lending processes and reducing financial risks.
# Dataset Description:
The dataset used for this project contains information related to loan applicants, including credit policy, purpose of the loan, interest rate, installment amount, annual income, debt-to-income ratio, FICO score, credit history length, revolving balance, revolving utilization rate, inquiries in the last 6 months, delinquencies in the past 2 years, public records, and loan repayment status (fully paid or not fully paid).
# Data Preprocessing:
- Check the shape of the dataset and identify any missing values.
- Drop unnecessary columns that do not contribute significantly to the prediction task.
- Split the dataset into two dataframes: one containing records of fully paid loans and the other containing records of loans that were not fully paid.
# Model Development:
- Define a Sequential model using Keras, a popular deep learning library.
- Add dense layers with dropout regularization and batch normalization to prevent overfitting and improve model generalization.
- Configure the output layer with softmax activation to predict the probability of loan repayment or default.
# Model Training:
- Compile the model using categorical cross-entropy loss function and the Adam optimizer.
- Train the model on the dataset, optimizing for accuracy as the evaluation metric.
# Model Evaluation:
- Evaluate the trained model's performance using various metrics, including accuracy, precision, recall, and F1-score.
- Generate a confusion matrix to visualize the model's predictions and actual outcomes.
# Results:
Based on the evaluation metrics, the developed AI model demonstrates exceptional performance, achieving perfect scores in accuracy, precision, recall, and F1-score. This indicates that the model accurately predicts loan repayment outcomes, enabling lending institutions to make reliable decisions regarding loan approvals.
# Conclusion:
The AI model developed in this project serves as a valuable tool for lending institutions in assessing the creditworthiness of loan applicants and minimizing the risk of default. By leveraging advanced machine learning techniques, financial institutions can streamline their lending processes, enhance risk management practices, and ultimately contribute to a more stable and efficient financial ecosystem.

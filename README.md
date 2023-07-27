Module 20 
# creditriskclassification_challenge
# Background
We are developing a program to determine whether a loan is risky or not, a process known as "credit risk analysis." To achieve this, we are utilizing a machine learning technique called logistic regression.
# Step 1: Data Collection and Splitting
First, we gather loan data from a file named "lending_data.csv." The crucial aspect we examine is the "loan_status" column, which indicates whether a loan is classified as risky or not (our target variable). The remaining information in the other columns serves as features that will aid us in predicting the target variable.

Additionally, we ensure that the number of risky and non-risky loans is approximately equal. If there is an imbalance, we implement a solution to address this issue.

Subsequently, we split the data into two sets: one for training the program, allowing it to learn, and the other for testing its performance and evaluating how well it has learned.

# Step 2: Training the Program with Original Data
In this stage, we use the training data to teach our program how to predict loan risk. After the learning process, we assess its performance using the test data.

To evaluate the program's effectiveness, we calculate its "accuracy," which measures how often it makes correct predictions. Additionally, we create a "confusion matrix," a table that helps identify areas where the program may be making errors. Furthermore, a "classification report" provides us with detailed information about the program's overall performance.

# Step 3: Balancing Data and Re-training the Program
To address potential data imbalances, we apply a technique called "oversampling." This involves generating additional data instances for the program to learn from, ensuring a more balanced representation of risky and non-risky loans.

With the newly balanced data, we re-train the program and assess its performance once again.

# Conclusion
Finally, we compare the program's performance based on its learning from both the original and balanced data. This comparative analysis sheds light on the efficacy of logistic regression in predicting loan risk and highlights the significance of balanced data for the program's performance.

By completing these steps, we aim to develop a robust credit risk analysis program capable of making accurate loan risk predictions.

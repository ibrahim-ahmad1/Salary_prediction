# Salary_prediction
I have made an project that calculate the salary of the employee based on the asked inputs. 
These are the steps that I followed to built my project
1) Imported numpy, pandas, Matplotlib, Scikit-learn Libraries.
2) Loaded the Kaggle salary prediction dataset
3) handled the missing values by dropping the rows with missing values
4) I also droped the Job title column because there were less amount of data and there was high variance in  the job title column.
5) Then I divided the dataset into 8:2 ratio 80% for training and 20% for testing.
6) then I trained the linear regression model
7) Tested the Linear regression model
8) At last the evaluation of the model. Here are the scores of the model
   MAE: 10613.910121260105
   RMSE: 15251.066471878252
   R2 Score: 0.9029876738433329

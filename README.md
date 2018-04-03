# kaggle-Job-Salary-Prediction
Advanced Machine Learning group coursework

Describtion of Adzuna Salary Prediction [here](https://www.kaggle.com/c/job-salary-prediction)

Aim of this project:
*    Using different method to predict
*    Comprasion

# Step 1: data_cleanning - fixed -> reduce the dimention of input data

fill NaN and transofom strings to integer vector. At the sametime, update location information by mathching LocationTree.

orginal data format: 
![image](https://raw.githubusercontent.com/Trouble404/kaggle-Job-Salary-Prediction/master/readme_pic/word.PNG)

after [step 1](https://github.com/Trouble404/kaggle-Job-Salary-Prediction/blob/master/job-salary-datacleaning.ipynb)

![image](https://raw.githubusercontent.com/Trouble404/kaggle-Job-Salary-Prediction/master/readme_pic/wordtovec.PNG)

Processed data can be downloaded at link：https://pan.baidu.com/s/1DrLCkmjK4GxdOsHHnDpEZw pin：8nk1

# Step 2: Train model

transfrom vector to one-hot vector and using Embedding or HashingVectorizer to process data in FullDescribtuion

# Predicting Student Performance

## About the Project
This repository contains the final project completed as part of our first Machine Learning course at university. In it, we went through the entire process of data analysis and building predictive models, from the very beginning to drawing business conclusions. The main goal was to investigate which factors have the greatest impact on students' final grades.

## What Did We Learn?
Since these were our first steps in this field, the project allowed us to practically master many key concepts:

* **Data exploration and cleaning:** We understood how important it is to prepare information before feeding it to a model. We learned how to handle missing values, convert text values to numerical ones (LabelEncoder, OneHotEncoder), and standardize data (StandardScaler).
* **Dataset balancing:** We learned techniques for dealing with imbalanced classes using methods such as SMOTE and RandomUnderSampler.
* **Building models:** We built and compared the performance of several basic classification and regression algorithms (including Logistic Regression, K Nearest Neighbors, and Support Vector Machines).
* **Performance evaluation:** Instead of blindly trusting the results, we learned to use metrics such as accuracy, precision, and recall, as well as how to read a confusion matrix.
* **Visualization:** We used Matplotlib and Seaborn libraries to create clear charts that help understand the relationships in the data.

## Dataset
The analysis was performed on a dataset of student information containing 2392 rows and 13 columns. We analyzed variables such as age, gender, parents' education, time spent studying per week, number of absences, and involvement in extracurricular activities.

## How to Run the Project?
To reproduce our results on your own computer, follow the steps below.

1. Download the files from this repository to your local drive.
2. Make sure you have all the required libraries installed. You can install them inside your environment using the terminal:

```bash
pip install -r requirements.txt
```

3. Run the `UM_Wandzel_Walus_Adamiak_Szymczyk.ipynb` notebook file in your favorite code editor (for example, Jupyter Notebook, VS Code, or PyCharm) and execute the cells one by one.
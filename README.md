# Engineering_Placements_Analysis
A method called the placement prediction system forecasts the placement status of final-year B-Tech students.

### About Dataset
We are all aware of how comprehensive machine learning is. Numerous algorithms are accessible and used on a regular basis. Statical approaches of data analysis are very desirable in the field of handling enormous amounts of data. They are analyzed, processed, and framed by data scientists in order to interpret the results and develop a useful plan for the organizations. One such method is the identification of a few independent variables against a single dependent variable using multiple logistic regression.

### Data 
The data we used to create this paper was obtained from the Kaggle website. The dataset is based on the 2013 and 2014 placement results of an unidentified university, whose reference can be found via the aforementioned link.
“https://www.kaggle.com/tejashvi14/engineering-placements-prediction”  

The dataset includes information on the students' overall academic progress from those years as well as their placement results in relation to that advancement.

### RESULT 
The table below lists the outcomes of using several machine learning algorithms. For the analysis, I took into account KNN, Logistic Regression, Random Forest, and SVM. I used the same dataset for training and prediction, and I calculated each algorithm's Accuracy, Precision, Recall, and F1-Score. And it is summarized in the table that follows.

| Machine Learning Algorithms | Accuracy | Precision | Recall | F1-Score |
|----------------------------|----------|-----------|--------|----------|
| Logistic Regression        | 76%      | 75%       | 75%    | 75%      |
| KNN                        | 83%      | 84%       | 84%    | 83%      |
| SVM                        | 78%      | 78%       | 78%    | 78%      |
| Random Forest              | 88%      | 87%       | 88%    | 87%      |

### CONCLUSION 
Final-year B-Tech students' placement status is predicted using a technique known as the placement prediction system. Several data mining techniques are used in the Python environment for data analysis and prediction. The accuracy of the methods that I looked at is shown in the table above. The accuracy rating of Random Forest, which is 88, makes it clear. KNN is also efficient, with an accuracy of 83 based on the supplied dataset. The accuracy of machine learning algorithms varies with the dataset. By providing accuracy rates of at least 75%, Random Forest, KNN, SVM, and Logistic Regression are all proven to be efficient approaches for handling binary classification issues, according to the results of our investigation.

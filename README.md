# predicting_exam_pass_with_logistics_regression
The project predicts whether a student could pass an exam based on their 2 previous exam scores with logistic regression. The project is taught by Flare Zhao in his course, "Python 3 Intro to Artificial Intelligence".

The data is composed of exam1 and exam2 scores for each student, and the label for each is either a 'pass' or 'fail'. 

The original data is displayed with a passed or failed label. 

The logistics regression model is trained on the exam1 and exam2 data, with ‘Pass’ as the label. A prediction is made and evaluated. 

Coefficients and intercept are extracted from the model and used to calculate the exam2 data (assuming X1 given). The decision boundary is then displayed with the original data.

More data is generated based on exam1 and exam2 data to create more complex decision boundaries which better fit the data. The decision boundary is then visualized with the original data.


Studying Hour VS Scores

================================================

Question:

1. Does studying hour has infulence on the score that students achieve? (Hypotheis: yes, hour studying has influence on the score and vice versa)

2. Predict the score of student that study for x amount of hour

Dataset was obtained onlined in a form of .csv file, the table structure only contain number of hour studying and the score that the students get.

================================================

Achieved Task:

1. Proof a strong correlation between hour of styding and scores

2. Make a model to predict the score that a student get if they were studing 'x' amount of hour

================================================

Step by Step Analysing Process

1. Importing Data and Cleaning Data

Data is imported into python and making sure the dataset is clean and there is no null value that can effect the calculation
![Import Data and Cleaning](https://user-images.githubusercontent.com/98216564/185345336-aabf3fec-20af-43df-9fcb-ded981c3161f.png)

2. Correlation

First we need to find if 2 columns actually have a correlation with each other and then displaying the correlation using a Heat Map
![Heat Map and Correlation](https://user-images.githubusercontent.com/98216564/185345909-01371292-fe1f-4a08-aa79-b251bad1a328.png)
We can see from the visualization that Scores and Hours have a strong correlation value of 0.98, so that means that hours has a strong influence on the scores that students achieve.

To further visualize this we can use a scatter plot
![Scatter Plot visualization](https://user-images.githubusercontent.com/98216564/185346505-2b9a6b7e-1e22-4a93-addb-c4d12f2a1777.png)
As we can see from the scatter plot, hour and scores has a possitive correlation with each other.

From this alone we can conclude that Hour has a storng positive correlation with the scores

================================================

Predict Scores of Students That Study 'x' Amount of Hour

1. First we need to split the data as an 'input_data' and 'target_data'
![Split Data ](https://user-images.githubusercontent.com/98216564/185347657-39fab120-98fb-4565-9120-1ffdc517ba60.png)

2. Fitting our model into Linear Regression
![Fit Data into LinearRegression Model](https://user-images.githubusercontent.com/98216564/185348411-e6da64ef-af09-4175-905c-7732376ef921.png)

3. Make a prediction using the Linear Regression model with 'train_input'
![Making a Prediction From The Input](https://user-images.githubusercontent.com/98216564/185348738-e2151700-ecb1-4190-9bb1-5ec04a471750.png)

4. Visualize the prediciton using plot
![Predicted Scores in a Plot Graphs](https://user-images.githubusercontent.com/98216564/185349014-fa64ca23-43d3-4155-9584-66fbd49149ab.png)

5. Comparing predictied value with the actual value
![Comparing Actual Result VS Prediction](https://user-images.githubusercontent.com/98216564/185349197-a849354a-2920-4a04-ac82-d7c96b12bc83.png)
As we can see the predicted value come quite close the the actual value from the dataset, and we can check the accuracy from our model which is around 94%
![Prediction Accuracy](https://user-images.githubusercontent.com/98216564/185349569-51cd0c02-db88-4311-8b1d-05edc6a0cd88.png)

6. Evaluate the model
![Evaluation](https://user-images.githubusercontent.com/98216564/185349859-b07bcd7f-7797-4760-891c-154548d5c14c.png)
And we can check the accuracy of our model which is still high around 96%, and from this we completed our model training and testing, we can use our model to predict the scores that the students get if they were studying 'x' amount of hour
![Accuracy and Prediction](https://user-images.githubusercontent.com/98216564/185350245-154d1f5b-6d74-48ce-ad45-cbe855548173.png)

Conclusion

1. Yes, hour of studying has a strong influence witht he amount of score a student gets. The more hour student put into studying, the higher the score is.





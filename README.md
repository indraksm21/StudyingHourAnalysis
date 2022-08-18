Studying Hour VS Scores

Question:

1. Does studying hour has infulence on the score that students achieve? (Hypotheis: yes, hour studying has influence on the score and vice versa)

2. Predict the score of student that study for x amount of hour

Dataset was obtained onlined in a form of .csv file, the table structure only contain number of hour studying and the score that the students get.

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

# gradepredandanalysis
Analysis of student datasets and their features, creating a ml model to predict grades and see how we can assist students to overcome whatever hurdles they may be facing.

# Objective
The objective of this paper is to analyze student data and make a grade predicting model.
Via analyzing the student data we will be able to see which features effect a student’s grades the most.
The predictive model can be used to predict which students may score bad in an exam, helping us create a list and automatically contact them to provide them with the necessary educational help.
The model will also be able to predict which students are likely to score higher, and if they don’t , we will be able to investigate why they did not and what factors link to their lack of performance.

# Reasoning
In general , it is common knowledge that if a student doesn’t study/participate in class they will not score good marks, but why do students who do participate and fulfill all the criteria still score low marks? Or alternatively why do some students who do not participate in class obtain good marks? What are the other common features among good scorers ? What links them together?
If we can find out the answers to the questions above we will be able to improve the educational system, we will be able to know what helps a student achieve apart from all  the common knowledge, eliminating obstacles , creating a more suitable environment for success.
The model is a step forward towards automated education, it will help the education system be a fairer world.
Via prediction, the model will be able to create a list of scorers who can be sorted into :
Students who are predicted to score bad, they will be contacted and provided with help.
Students who are predicted to score good, we will be to list out and see the common features between the top scorers and see which features matter most and if there are any outside school features which effect their grades.
Further on, we can also detect “anomalies”, that is, wrong predictions by the model meaning :
Student predicted to score good but scored bad marks.
Student predicted to score bad but scored good marks.
By analyzing the student data we will be able to see exactly why these anomalies occur.


# Dataset

Scoured for the dataset on kaggle.
I edited the dataset into a school dataset and a dataset with features related to home and family.
This will help us see how different features come into play in determining our target variable.
"Dataset edit and adding new features.ipynb" contains code to create a new feature called assndays wich is amount of days taken to submit the assignment.
I had added the code to generate such a feature in order to make this project a little more realistic. The code includes the trial and errors i went through. Successful trial generates assignment days where a larger number is assigned to students with low activity in class, this was added on request of my professor who said there were'nt enough features, however since they were not willing to provide data themselves, i had to edit it myself.

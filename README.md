# Logistic-regression---University-admission---project-2
implement logistic regression and apply it to two different datasets.


Introduction
In this exercise, you will implement logistic regression and apply it to two
dierent datasets. Before starting on the programming exercise, we strongly
recommend watching the video lectures and completing the review questions
for the associated topics.
To get started with the exercise, you will need to download the starter
code and unzip its contents to the directory where you wish to complete the
exercise. If needed, use the cd command in Octave/MATLAB to change to
this directory before starting this exercise.
You can also nd instructions for installing Octave/MATLAB in the \En-
vironment Setup Instructions" of the course website.
Files included in this exercise
ex2.m - Octave/MATLAB script that steps you through the exercise
ex2 reg.m - Octave/MATLAB script for the later parts of the exercise
ex2data1.txt - Training set for the rst half of the exercise
ex2data2.txt - Training set for the second half of the exercise
submit.m - Submission script that sends your solutions to our servers
mapFeature.m - Function to generate polynomial features
plotDecisionBoundary.m - Function to plot classier's decision bound-
ary
[?] plotData.m - Function to plot 2D classication data
[?] sigmoid.m - Sigmoid Function
[?] costFunction.m - Logistic Regression Cost Function
[?] predict.m - Logistic Regression Prediction Function
[?] costFunctionReg.m - Regularized Logistic Regression Cost
? indicates les you will need to complete
1
Throughout the exercise, you will be using the scripts ex2.m and ex2 reg.m.
These scripts set up the dataset for the problems and make calls to functions
that you will write. You do not need to modify either of them. You are only
required to modify functions in other les, by following the instructions in
this assignment.

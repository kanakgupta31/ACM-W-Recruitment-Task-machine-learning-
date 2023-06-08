# kanACM-W
# IRIS DATASET:
The data set consists of 50 samples from each of three species of Iris. It is used for testing out machine learning algorithms and visualizations. Each row of the table represents an iris flower, including its species and dimensions of its botanical parts, sepal and petal, in centimeters.

The objective of this project is to solve the iris dataset using two machine learning methods, namely, the logistic regression method and the k-nearest neighbors algorithm(knn method).
To run the project successfully, I had to install the numpy , scikit-learn modules and also the python latest version software.
![WhatsApp Image 2023-06-08 at 16 31 28](https://github.com/kanakgupta31/kanACM-W/assets/135737270/cf65956d-d9a1-4f15-8c47-45857e1ac712)
![WhatsApp Image 2023-06-08 at 16 29 25](https://github.com/kanakgupta31/kanACM-W/assets/135737270/1d5ffeec-0e2c-48f6-b73a-da5722bb1c28)
I installed these modules using the pip command in the windows powershell.The python's latest version was downloaded from the www.python.org site.

First of all, I started by importing all the required modules. Next, I loaded the iris datsaset and split it into training and testing sets. It is a mandatory step as a training set is one with which the learning algortihm adapts or learns the model and the testing set is used to evaluate the generalization performance of the model.

Then I applied the feature scaling to standardize the features. Feature scaling is a method used to normalize the range of independent variables or features of data. 
These above steps are common to both the methods, below is the screenshot attached for the same:
![WhatsApp Image 2023-06-08 at 16 55 35](https://github.com/kanakgupta31/kanACM-W/assets/135737270/d2852ceb-7363-4fab-890c-13ce6cf9c54c)

# LOGISTIC REGRESSION:
I created a logistic regression model and fit it to the training sets using the .fit command. Then I used the .predict command to procide predictions on the test data splitted above. Finally the accuracy of the logistic regression model is printed using the print command and the result is displayed.
![WhatsApp Image 2023-06-08 at 13 53 14](https://github.com/kanakgupta31/kanACM-W/assets/135737270/01a3015d-1850-4916-8ed1-330e3b43ffe0)

# KNN METHOD:
For this method, steps performed are same except that now i had to create the k-nearest neighbors model using the KNeighborsClassifier() command.
The result is displayed below:
![WhatsApp Image 2023-06-08 at 13 52 30](https://github.com/kanakgupta31/kanACM-W/assets/135737270/ae991d04-2501-4a6c-a04a-07de5b679b8e)

This was the complete overview of the project and how I proceeded in the making of this project.

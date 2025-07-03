# Titanic_db
predict survival rate from Titanic dataset

Goal- the goal of this project was to predict the survivors given the titanic dataset

Steps-
1.Read the data and explore the data
2.check the columns correlation to each other and the heatmap
3.Split the data into train and test and even amount of data in each column
4.Values missing so we use estimator so fill the nan values and drop irrelevent features/columns
5.Using pipeline and using relevent model selection in this case radom forest classifier.

Result- We got a 81% accuarcy on the test data which is alright. The columns/features that was the most important was gender, class and maybe less important then the first two was the fare.  

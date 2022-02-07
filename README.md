# Logistic-Regression

# Project Introduction<br>
In this project you will be provided with real world data which is related with direct marketing campaigns (phone calls) of a Portuguese banking institution.

The classification goal is to predict if the client will subscribe a term deposit (variable y).

## Section I : Data Loading
Part I : Load the dataset into the notebook
Part II : Explore and make note of Attribute Information from UCI
Part III : What is the significance of the y column in the dataset and what are the value counts of the y column?
Part IV : What is the ratio of the two classes ? Are they balanced ?

## Section II : Data Cleaning
Since this is real world data , A good practice is to make sure the dataset is devoid of any nuances

Part I : Get the dtypes of all the columns of our dataset
Part II : Refering to the UCI data description , explore the data in your columns and check if there are any errors
Part III : Make note of the deviation in the dataset compared to the description provided by UCI
Part IV : Using Data Cleaning principles you learned from Pandas Tutorial) figure out the best ways to get rid of the dirty data Part V : Print the cleaned data

## Section III : Exploratory Data Analysis
Let us put Matplotlib to use !

Part I : Create bar graphs to the frequency of purchase with respect to the job , martial etc
Part II : Also create stacked bars to same data columns with respect to
Part III : Explore the age column using a histogram and note down your observations

## Section IV : Categorical Variable Encoding
Part I : Create dummy variables for your categorial variables
part II : Explore your new dataset with these new dummy variables !

## Section V : Preliminary Training
Part I : Import your Logisitc Regression libraries
Part II : Split your train and test dataset and train on the data
Part III : Make note of the classification report and other metrics

## Section VI : Let's Improve the performance !
Part 0 : What was your answer to Section - Part IV? Do you think class imbalance affects the model performance? Explore SMOTE implementation

Part I : Make note of the performance from the last training
Part II : Try implementing SMOTE to balance the two class labels
Part III : Make note of the y label data now , what are the rations now ?

## Section VII : Let us Re-Train!
Part I : Explore what RFE means
Part II : Implement your training process inside the RFE
Part III : What are the best columns that your RFE found? Please make a list of it

## Section VIII : Training time !
Now that you have found the best columns for this problem

Part I : Now train the model with the new data you have created after the RFE
Part II : Create the prediction system to get the metrics such as accuracy

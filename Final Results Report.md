# Final Performance Report 

# Overview
The purpose of this analysis was to use a neural network ML model to help predict if applications will be successful or not in their venture.
The given data was used to train and test the 3 models. 

# Results
- The target variable used from the data set “IS_SUCCESSFUL”
- The features that were used in the analysis include: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT
- The variables removed from the data during pre-processing: EIN and NAME… these were not needed because the do not have a factor on funding as they are identifiers for the applicants

Compiling, Training, and Evaluating the Model


1. Attempt 1- I started with 2 hidden layers and a smaller amount of neurons
layer 1= 9
layer 2= 9

I wanted to start small and build from there. If I could achieve decent accuracy with a simpler model that would be ideal for performance

Accuracy= 72.5% and Loss= 55%

2. Attempt 2- I had 3 layers and upped the nodes 
layer 1= 9
layer 2= 18
layer 3= 27

I thought that more nodes and another layer would give me better accuracy and it did. 

Accuracy= 73% and Loss= 55%

3. Attempt 3- Added more layers and more epocs
layer 1= 18
layer 2= 18
layer 3= 27

I figured that I would take a small hit on performance to get better accuracy by upping the nodes and the epocs. However, the model took longer to run and did not have better accuracy than attempt 2.

Accuracy= 72.9% and Loss= 55.1%


# Summary
In summary, I did not achieve the target accuracy of 75% after 3 attempts. The highest accuracy that I achieved as 73%. I think that I may have cut down my data too much and also may
need to play around with the functions. I stuck with only the ReLU and Sigmoid functions in my first 3 attempts.   

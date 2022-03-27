# Neural_Network_Charity_Analysis

In this module we designed and utilized a deep learning neural network to help predict which networks are worth donating to and which foundation is too high risk. We put together a mathematical solution that can accurately predict which foundation would be best to donate to. We helped beks learn about neural networks and how to design and train the models using the python tensorflow library.
Data Preprocessing

What variable(s) are considered the target(s) for your model?
-	Our target is for a “IS_SUCCESSFUL" for the module.

What variable(s) are considered to be the features for your model?
-	We had to remove a few columns to have the correct features for the model. We following variables remained in the model: ASK_AMT, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, APPLICATION_TYPE, STATUS,SPECIAL_CONSIDERATIONS, INCOME_AMT.

What variable(s) are neither targets nor features, and should be removed from the input data?
-	After dropped both the 'EIN','NAME' and 'IS_SUCCESSFUL' columns from the dataframe.
-	We dropped them because neither features because they only identify the data.
 ![image](https://user-images.githubusercontent.com/93060074/160265403-f582d2a1-0b11-4b5b-8214-6e0825c45379.png)


How many neurons, layers, and activation functions did you select for your neural network model, and why?
-	The neural network model there is 1 input and 2 hidden layers(80 and 30 nodes). We also used two  layers for 100 epochs utilizing ReLu and Sigmoid activation functions.

Were you able to achieve the target model performance?
-	We fell just short of our target model performance of 75.
 
 ![image](https://user-images.githubusercontent.com/93060074/160265395-2d6fdfd0-93d4-4aaa-a89e-16d774af15fa.png)

What steps did you take to try and increase model performance?
-	We made two additional attempts and increased the number of epochs to increase performance. We made some changes to the bins and added a third hidden layer to try to increase model performance. 


# SUMMARY:
After my compete analysis I would recommend using the random forest models.  The model handles classification problems with ease.  Accuracy using this model is better than the other models.

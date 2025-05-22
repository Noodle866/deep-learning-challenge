# deep-learning-challenge
module 21 challenge

## REPORT

Purpose of this analysis: To make a deep learning model to predict the success of charitable organizations.

What variable(s) are the target(s) for your model: The target variable is "IS_SUCCESSFUL".
 
What variable(s) are the features for your model: The variables that are the features for the model is APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, and IS_SUCCESSFUL.

What variable(s) should be removed from the input data because they are neither targets nor features: The variables that should be removed from the model are EIN, and NAME.

How many neurons, layers, and activation functions did you select for your neural network model, and why:

For the original model I used 80 and 30 neurons, 2 hidden layers, and the activation functions used are "relu", and "sigmoid".

For the first retest model I used 80, 30 and 10 neurons, 3 hidden layers, and activation functions used are "relu", and "sigmoid". I added one hidden layer to see how that effected the model first.

For the second retest model I used 100, 50, 20, 20, 10, 10 neurons, 6 hidden layers, and activation functions used are "relu", and "sigmoid". I changed the neurons to allow  the model to learn more. I changed the hidden layers to add ther the model learning ability.

For the thrid retest model I used 200, 125, 100, 100, 50, 50 neurons, 6 hidden layers, and activation functions used are "relu", and "sigmoid". No major changes happened in the first two restest so I up the game with many neurons added. 

Were you able to achieve the target model performance: I was not able to achieve the target model performance.

What steps did you take in your attempts to increase model performance: I changed columns dropped, number of neurons, amount of hidden layers, and times model ran "epochs".

## Summary

Over all no major changes happened thoughout the retest. If you did not drop the "NAME" column the accuracy to 75% but due to challenge requirments that is not allowed.  


## Images showing corrections 

<ins>Retest 1<ins/>

Dropped column "STATUS".

![image](https://github.com/user-attachments/assets/c6671e19-2fdb-4893-8f16-bbed7cd98b19)

Added 3rd hidden layer.

![image](https://github.com/user-attachments/assets/19304ca3-624a-42be-94e8-1c72edc0eed1)

Changed epochs to 125.

![image](https://github.com/user-attachments/assets/5591a3a3-3521-42eb-a112-3fc8967a38df)

Results

![image](https://github.com/user-attachments/assets/34e2fa4b-2fa9-4330-a8e9-736022a355c7)

<ins>Retest 2<ins/>

Changed dropped columns back to original.

![image](https://github.com/user-attachments/assets/c57679cc-80ec-4849-8c4f-748cbbce746e)

Added 6 hidden layers.

![image](https://github.com/user-attachments/assets/35a00719-4dbf-49c1-92f6-43191cf7a9ed)

Changed epochs to 50.

![image](https://github.com/user-attachments/assets/8185afb7-146d-4c93-8343-fceef73047f8)

Results

![image](https://github.com/user-attachments/assets/d632403a-1852-44d4-8e4f-c9b3c0fc6427)

<ins>Retest 3<ins/>

Only dropped NAME and EIN columns.

![image](https://github.com/user-attachments/assets/3ff0e375-e65a-4b08-a489-cc2d37a20cd7)

Added 6 hidden layers.

![image](https://github.com/user-attachments/assets/e0060255-9708-492e-80bc-a322041430ac)

Changed epochs to 200

![image](https://github.com/user-attachments/assets/12865c37-c3ef-4adf-8ac6-6273576a3ab3)

Results

![image](https://github.com/user-attachments/assets/4eb51587-1d1f-4898-b0a1-1a8385b6abc0)





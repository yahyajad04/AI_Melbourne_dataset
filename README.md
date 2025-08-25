# AI_Melbourne_dataset

This project consists of making a model to estimate the prices of houses in Melbourne,Australia.

Firstly we handled the problems in the dataset such as missing data, useless column, data scales difference, different datatypes that needs to be encoded.

After we have the data cleaned, we started with the model training using different algorithms from sklearn library such as SVM,Randomforest,Kneihbors,etc..
since its a regression problem because th output we are waiting for is a price, we use the regressors of them not the classifiers.

We also used neural networks with Keras so we can see what will give us the optimal model with no over or under fitting, we made the neural model with 4 dense layers and used the "MSE" to be our loss function.

At the end we found out that neural networks is not always the better solution since on our dataset the other models such as Decision tree and Random Forest models gave excelent results that are a little bit better than the Neural model.

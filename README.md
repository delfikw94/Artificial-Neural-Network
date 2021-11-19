# Predictive Model for Customer Retention in Telco Company
Classifying customer's loyalty using articial neural network model

**Tools Used** : Python, Google Colab, Numpy, Pandas, Scikit-Learn, Keras Tensorflow

**Category** : Deep Learning, Classification

**Year** : October 2021

**Features** : Customer's personal information (dependent, gender, senior citizen) and customer's subscription information (tenure, phone servise, internet service, billing type, payment method, etc)

**Model Algorithm** : ANN (with sequential API) and ANN (with Functional API)

**Result** : After the first model training, the ANN with Sequential API achieved better result (higher accuracy and lower loss score) than the Functional API. Then after we did the hyperparameter tuning, the accuracy is slightly better but the loss score is higher than before for Sequential API. Meanwhile, it worked much better for the functional API (the accuracy was getting higher and the loss score was getting lower). Therefore, the ANN model with functional API was chosen to do the model inference.

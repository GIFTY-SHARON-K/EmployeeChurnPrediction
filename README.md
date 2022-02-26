# EmployeeChurnPrediction
This study aims to predict who is going to leave the company.
PROJECT LINK : https://gallery.azure.ai/Experiment/Employee-Churn-Prediction-5

PROBLEM STATEMENT :  With the proliferation of big data, the need for intelligent and automated Systems has risen. This need is probably felt the most in the field of Financial Technology. That to in this situation of Covid-19 many companies did layoff to manage it's profits. So, this model will help to predict who will leave the company.

PROJECT DESCRIPTION : Using this model we would be able to predict the employees who are likely to leave and take precaution about it.It is done by way of Machine Learning using Azure ML.What are the things we do are followed below
            => Train a Machine Learning model in Azure ML that can predict the probability of employee churn.
            => Determine what factors predict an employee leaving his/her job.
            ![image](https://user-images.githubusercontent.com/71095797/155856984-8f59df91-cb94-431f-b760-2bd7cb1c1a25.png)
In the above model, 
    1. Import the Dataset required for training.
    2. Select the columns required as we exclude the data which are in the form of boolean or string instead accepts data in the form of integer.
    3. Editing the Metadata by this way we are selecting the output column.
    4. Splitting the data into training data and testing data in which 80% goes to training data and 20% goes to testing data.
    5. Using Two-Class Decision Forest as this classifier works so good as it gives the maximun area under curve if a classifier works too well it means the area under the curve is maximum.
    ![image](https://user-images.githubusercontent.com/71095797/155857415-4b07251f-07fe-4601-a319-ba9759237396.png)
    6. Training the model this is done by combining the result of the Two-Class Decision Forest Classifier and the training data from the split data which holds 80% of the data.
    7. Score model is done by combining the result from train model and the testing data from the split data which holds 20% of the data.
    8. Evaluate model this is done by taking score model as input and the output can be visualized as follows and is also followed by a youtube video of demonstration of Employee Churn Prediction.
            ![image](https://user-images.githubusercontent.com/71095797/155858378-6b17dd8e-b1bf-4c23-904a-48829e19f434.png)

    https://youtu.be/Ul0Ai4gTke8
      
      

# Machine learning classification model 
 This model will help marketers to predict if a customers with certain attributes (features) will convert after becoming lead in a cross selling campaign
 
 Model performance is pretty good even with imbalanced class with 98% auc score.
 
 The model has been successfully tested in FastAPI and deployed on Heroku and can be accessed using https://conversion-prediction.herokuapp.com/ ("/docs" to test the model output)
 
 4 features are the input to the model with following type:     
    Region_Code: int (e.g. 3732) \n
    Reco_Insurance_Type: int (e.g. 0 for individual type and 1 for joint type)
    Upper_Age: int (e.g. 32 ) (in years)
    Reco_Policy_Cat: int (e.g. 19)
    
 To get all possible values, kindly download the train.csv file.
 
 Thank you!

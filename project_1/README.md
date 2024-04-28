# Machine Learning Pipeline for a Regression Project

Create  a machine learning pipeline that using modified version of car mileage dataset to predict MPG

This project includes the following steps:

- ETL

    - Load csv dataset 
    - Remove duplicates 
    - Remove rows with null values 
    - Make transformations 
    - Stored cleaned data 

- Machine Learning Pipeline 

    - Using StringIndexer convert the string column into Index 
    - define VectorAssmbler pipeline stage 
    - Using standard scaler to scale the features
    - Create a Linear Regression stage 
    - Combine all the stages
    - Fit the model to training data 
    - Save the model 
    - Evaluate the model using metrics and testing data 

- Model Persistance 

    - Save the model for future production use 
    - Load and verify the stored model

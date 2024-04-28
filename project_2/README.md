# Machine Learning Pipeline for Airfoil noise prediction

Building a ML pipeline on the modified version of the NASA Airfoil Self Noise database. I need to clean this dataset, by dropping the duplicate rows, and removing the rows with null values. I create an ML pipe line to create a model that will predict the SoundLevel based on all the other columns. After that, I evaluate the model and towards the end I will persist the model.

- ETL (Extract, Transform, Load) data
    
    - Load csv dataset 
    - Remove duplicates 
    - Remove rows with null values 
    - Make transformations 
    - Stored cleaned data 

- Create and evlaluate a Machine Learning Pipeline

    - Using StringIndexer convert the string column into Index 
    - define VectorAssmbler pipeline stage 
    - Using standard scaler to scale the features
    - Create a Linear Regression stage 
    - Combine all the stages
    - Fit the model to training data 
    - Save the model 
    - Evaluate the model using metrics and testing data 

- Persist the model 

    - Save the model for future production use 
    - Load and verify the stored model

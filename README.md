# NLP Project Codes
These are the codes used for our NLP project: Detection of ARG1 of Partitive Group Predicates using Neural Network

### Description of files:
NomBank Partitive Datasets.zip: Contains NomBank partitive dataset (Train, Development and Test)  
CSV Datasets: Contains the CSV files after parsing NomBank partitive files
ModelTraining.ipynb: Contains the code for featureset generation, training the model, and saving it to be used for inference. 
ModelInference.ipynb: Uses the dev and test csv files and gets results using saved model. 
Score.py: Professor's scoring program to get f-measure

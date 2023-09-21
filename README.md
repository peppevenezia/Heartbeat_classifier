# Heartbeat_classification
Deep learning and machine learning for single heartbeats' classifiaction as normal, premature atrial contraction (PAC) or premature ventricular contraction (PVC) from 2 lead ECG  
  
This project was developed in collaboration with https://github.com/KarimKassem , https://github.com/peppevenezia    
## Index:
#### Report
Detailed report of:  
the task, its critical aspects and the criteria adopted for decision making throughout the project;  
preprocessing, modeling, evaluation and comments on results.
#### Main_notebook
Fed the dataset split into train and validation as obtained from the genetic algorithm;  
signal analysis and preprocessing;  
signal splitting in heartbeats;  
extraction of wide features;  
using the selected models from DLmodels and MLandHybridModels to build an ensemble.
#### GeneticAlgorithm
Split the patients in train and validation with no 1 patient in both sets and the best stratification possible of the 3 classes (1 per heartbeat)
#### DLmodels
Data-driven feature extraction only;  
different approaches for balancing classes and dealing with windowed timeseries;  
single and multi-step prediciton;  
#### MLandHybridModels
Use both of data_driven and knowledge-driven features.

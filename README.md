# w266_project

The following illustrate the project workflow

Step 1:Gathering of news articles and sampling news articles using various publications
initial_preparation.ipynb -> initial_data.csv
Step 2: Label the Data using ChatGPT API"
ClassifyingData_modified -> training_data_modified_final

Step 3:Subjectivity classification Model baseline + fine-tuning
Subjectivity_Classification_final -> training_data_with_objectivity (relabeled the data using the fine-tuned model)

Step 4:Summarization using objective sentences deteremined using Step 3
Objective_Summary.ipynb -> summary_final.csv

Step 5: Used the fine tuned model (subjectivity_classification_final) to classify the summary_final 
summary_final_classified

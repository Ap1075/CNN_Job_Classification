### Classifier which takes in a job description and gives the department name for it.

*   Use a convolutional neural network model
*   Makes use of a pre-trained Word Embeddings (GloVe)

### Data Structuring

All the data required can be found in the data folder in the root of the project

There are two sources for loading your training/test data

*   For *Job Description*:  
   **docs** folder contains around 1000 json files, each of which is a single job posting. You have to use the value of `description` field inside the `jd_information` field.

*   For *Job Department*:  
   **document_departments.csv** file contains the mapping of document id to department name where document id is the name of the corresponding file in docs folder.

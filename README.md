# Overview
To predict whether a applicant will be successful if funded by Alphabet Soup, and help Alphabet Soup select applications with the best chance of success in their vectures.

# Results
## Data Preprocessing
- What variables are the targets for your model: "IS_SUCCESSFUL" - this is the unit that gauges whether a applicants is successful (1) or unsuccessful (0)

- What variables have been removed: "EIN" and "NAME" have been removed as they are identifiers and have no weight in whether an applicant is successful

- What variables are features for your model: All other columns are features of the dataset:
        - APPLICATION_TYPE
        - AFFILIATION 
        - CLASSIFICATION
        - USE_CASE
        - ORGANIZATION
        - STATUS
        - INCOME_AMT 
        - SPECIAL_CONSIDERATIONS 
        - ASK_AMT 

## Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why? In an attempt to improve target model performance, the number of neurons was increased.

- Were you able to achieve the target model performance? I was able to improve accuracy slighlty from 72.43% to 72.73%. Improving the accuracy proved to be a challenging task.

- What steps did you take in your attempts to increase model performance?
    - Changed application type bin from 1000 to 200 
    - Changed classification bins from 500 to 1000
    - Neurons change (16 to 100 for the 1st hidden layer, 4 to 50 for the 2nd hidden layer)
    - EPOCHS change from 25 to 150.

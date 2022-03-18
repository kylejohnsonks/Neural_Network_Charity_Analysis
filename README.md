# Neural Network Charity Analysis Overview

Alpahbet Soup takes funds charity activities and has a preexisting data set with metadata about organizations who have received funds and if they were used effectively.  The goal of this project is to determine if a model can be built to accurately predict if an organization will use funds effectively based on the metadata provided, specifically to 75% accuracy. 

# Data Processing

The original data contains 12 columns.  The target variable is the 'IS_SUCCESSFUL' column, which shows if the organization successfully used the funds.  

The features used in the final model are:
- APPLICATION_TYPE
- AFFILIATION
- CLASSIFICATION 
- USE_CASE
- ORGANIZATION

The variables removed form the data are:
- SPECIAL_CONSIDERATIONS
- ASK_AMT
- EIN
- NAME
- STATUS
- INCOME_AMT

# Results
The final model achieves 69.4% accuracy on the test data, using a neural network with 4 hidden layers plus the output layer. The model employes a total of 211 neurons, arranged in the four layers 100 - 50 - 30 - 30 plus a single neuron for the output layer.  

The 69% accuracy falls short of the desired accuracy of 75% despite many attempts to improve the model.  

<img src="Resources/nn_model.png" />



Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

## Deliverable 4 Requirements

You will earn a perfect score for Deliverable 4 by completing all requirements below:

Structure, Organization, and Formatting (6 points)

The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections (2 pt)
Each section has a heading and subheading (2 pt)
Links to images are working, and code is formatted and displayed correctly (2 pt).
Analysis (24 points)

The written analysis has the following:

Overview of the loan prediction risk analysis:

The purpose of this analysis is well defined (4 pt)
Results:

There is a bulleted list that answers all six questions (15 pt)
Summary:

There is a summary of the results (2 pt)
There is a recommendation on using a different model to solve the classification problem, and justification (3 pt)

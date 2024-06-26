
# **PROJECT-4**
![image](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/dc3e3aab-170b-4fa7-8656-40ef0f4ebacb)
## Project Presentation & Analysis
[Tableau Presentation](https://public.tableau.com/views/DatamindsEnsemblePresentationdraft4/MarketAnalysisLeadScorePrediction?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)


**PROJECT TITLE:**  Market Analysis & Lead Score Prediction

[PROJECT DESCRIPTION](#project-description)  

[CONTRIBUTORS](#contributors) 

[INSTALLATION](#installation) 

[DOCUMENTATION](#documentation)  

[DEVELOPMENT](#development)  

[CONCLUSIONS](#conclusions)

[REFERENCES](#references)  




#### PROJECT DESCRIPTION

 This projects focuses on the practice management software that acts as a toolkit in providing client interface for law and account firms on a single platform. Looking to expand into the US market, a novel company is willing to perform market research and analysis for this purpose. By utilizing 500 data records, the aim of this project is to provide a detailed analysis framework in scraping website data for compilation of law and accounting firms, along with their corresponding services and fees. Additionally, the framework will include a model to predict lead scores for a given query based on the clients demands. These lead scores will indicate how likely it is that a client will benefit from the product.



#### CONTRIBUTORS
- Anita Kumar Github Link: https://github.com/Ani2587
- Carter Jackson Github Link: https://github.com/musicace17
- Mita Josh Github Link: https://github.com/Mitajoshi
- Felix egwuagu Github Link: https://github.com/FelixEgwu
- Kelechi Joel Github Link: https://github.com/kcjoel
  
#### INSTALLATION 
  - Python :snake:
  - ![image](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/cf3ef0c3-5ad5-4541-9682-87a6d50d589c)
  - ![image](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/058d78b1-7449-4260-8ecc-daedf934d474)
  -  ![image](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/c43897a8-17b5-4ac0-83fa-06a6a619e8df)
  -  ![image](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/470f0e81-7cd0-4287-9b01-945cbef3d1a0)
  - langchain 
  - chatgpt
  - Tableau 
  - Machine Learning
  - ![image](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/ed335e56-ed86-4fda-82b5-85ff10276cd6)
  - ![image](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/5ad9a288-b4f9-4a45-a5ca-ae159bcd29fd)



####  DOCUMENTATION

*Data source:*

Data was acquired as a dataset from the team at BrightReturn Management. This can be found in the /resource part of this repository.


#### DEVELOPMENT 

1. *Data Retrieval & Transformation*
- Install add dependencies (langchain, numpy, panda, OS)
- import dataset (dataset1_lawyers.csv)
- Set up the Openai Set up with API key
- Crafting the prompt to instruct the LLM model to perform specific desired tasks
- Creating a chain for passing a list of Documents to a model
- Code block for the Langchain setup
- Looping through the dataframe to access the websites, load text from them, retrieve required data via LLM
- Store and Convert the list of responses to a DataFrame
- Tranform data by concation
- Filter Dataframe and convert to a dictionary
- Now modifying the above dataframe to have only those rows whose values are NOT zero
- Concatenate the DataFrames vertically (along rows)
- Making a copy of the result_df for the first chunk of data obtained; Deep copy
- The rest of data was cleaned and redefined into lawfirmdata_cleaned_100.csv



2. *Visualization-Analysis*
- Market Analysis & Lead Score Prediction
![vis1](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/8bb014a3-988b-41e7-b431-d66b61533d42)

- Law Firm Pratice Areas
![vis2](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/8c5f7ea0-2d1e-4111-9bae-11f5131cac19)


3. *Lead Score Prediction Model*
- This file obtains a compiled and pre-processed dataset of records containing various types of information about Law Firms from across 48 States of USA.
- Import dependecies (Sci-kit,tensorflow, matplotlib, pandas)
- Prepare data for ML model by definning path
- Dropping the non-beneficial columns
- Assign scores based upon Lead Score Matrix
- Creating the score as the target variable column
- split our preprocessed data into our features and target arrays
- Separating the y variable, the labels
- Splitting the preprocessed data into a training and testing dataset
- Creating a StandardScaler instances and scaling data
- Looking at the training and test data sizes
- Compile, Train and Evaluating the Model
- Calculating the confusion matrix
- Calculating the accuracy score
- Utilizing the Random Forests (sklearn) module to calculate feature importance
- Sorting and Visualizing the features by importance
  
- Machine Learning Configurations:
![image](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/cc57b5d7-40b2-4866-b8b0-f08da0996424)

- Lead Score Prediction Moel:
![vis5](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/93bc964a-9257-44f5-bd97-a3c486ed5f74)

- Confusion Matrix: 
![vis4](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/92aaeff8-5e2a-4960-83cc-f602775edc30)


- Classification Report:
![vis3](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/b2615bed-5c74-400b-bd1f-1ed4015b285d)


- Feature Importance:
![Market Analysis   Lead Score Prediction (1)](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/5de3c055-e82e-440b-9421-1d3c7f3c1ece)


- Model Analysis:
![vis6](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/d037507f-c9f1-4896-9c4e-674e5dd6c298)





####   CONCLUSIONS
Using the power of machine language, our project has successfully created a framework that possesses the ability to scrap data on legal firms and the services they provide for our clients. Using data presented by team, we’ve constructed a model that also predicts lead scores on these firms. By using our platform clients are guaranteed to have the most efficient experience and their needs attended to.


  
#### REFERENCES
- https://www.statista.com/topics/6737/research-and-development-worldwide/#topicOverview



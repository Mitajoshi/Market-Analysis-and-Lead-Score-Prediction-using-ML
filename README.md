
# **PROJECT-4**
![image](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/dc3e3aab-170b-4fa7-8656-40ef0f4ebacb)


**PROJECT TITLE:**  BRIGHTRETURN: A PRACTICE MANAGEMENT SOFTWARE

[PROJECT DESCRIPTION](#project-description)  

[CONTRIBUTORS](#contributors) 

[INSTALLATION](#installation) 

[DOCUMENTATION](#documentation)  

[DEVELOPMENT](#development)  

[REFERENCES](#references)  

[CONCLUSIONS](#conclusions)




#### PROJECT DESCRIPTION

 This projects focuses on the practice management software that acts as a toolkit in providing client interface for law and account firms on a single platform. Looking to expand into the US market, a novel company is willing to perform market research and analysis for this purpose. By uilizing 500 data records, the aim of this project is to provide a detailed analysis framework in scraping website data for compilation of law and accounting firms, along with their corresponding services and fees. Additionally, the framework will include a model to predict lead scores for a given query based on the clients demands. These lead scores will indicate how likely it is that a client will benefit from the BrightReturn product.

*Research questions to ask:*

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

Data was acquired as a dataset from the team at Brightside Management. This can be found in the /resource part of this repository.


#### DEVELOPMENT 

*Data Retrieval & Transformation*
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



*Visualization-Analysis*


  


*Machine Learning Configuration*
![image](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/2cdf3631-a691-4d16-b27d-47639c448e2a)



*Lead Score Prediction Model*
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

![image](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/75a622af-2c33-480e-9e03-94ef6200fd4b)



![Dashboard Lead Score Prediction Model](https://github.com/Mitajoshi/Market-Analysis-and-Lead-Score-Prediction-using-ML/assets/72319764/fb601f7c-a03d-4841-af45-9a3de532c3b3)

#### CONCLUSIONS
Using the power of machine language, our project has successfully created a framework that possesses the ability to scrap data on legal firms and the services they provide for our clients. Using data presented by team, we’ve constructed a model that also predicts lead scores on these firms. By using our platform clients are guaranteed to have the most efficient experience and their needs attended to.


  
#### REFERENCES
- https://www.statista.com/topics/6737/research-and-development-worldwide/#topicOverview



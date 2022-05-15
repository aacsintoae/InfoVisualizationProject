# InfoVisualizationProject
Project for Info Visualization 2022

The Project has as purpose the analysis of the Netflix Dataset (source: https://www.kaggle.com/datasets/shivamb/netflix-shows) composed of information on the Movies and TV Shows uploaded on Netflix in the period of time 2008 to 2021. 

The work on the project has been split into the following:
  1. Dataset Analysis
       
  2. Data Visualization and Interactive Plotting
  
  3. Classification Tasks employed using multiple ML algorithms for three different experiments:
                    i) Random Forest Classifier (Experiment I & II)
                    ii) SVM Classifier (Experiment I & II)
                    iii) Logistic Regression (Experiment I & II)
                    iv) Pre-trained Bert model in English (Experiment III)

# 1. Dataset Analysis
     - For a better understanding of the Netflix Dataset, its attributes and its properties please check the HTML file uploaded and the .csv file
     - For a better overview on the dataset you can also access it at its source link: https://www.kaggle.com/datasets/shivamb/netflix-shows
     
# 2. Data Visualization and Interactive Plotting
     - The purpose of the second part was understanding the properties of TV Shows and Movies on Netflix, such as their rating, which countries are contributing most to this industry, how the industry evolved with time and the chosen release months of Movies and TV Shows, from which we can extrapolate information on consumer behavior, since Netflix is a company focused on meeting customer's needs.
     - Data  Visualization with Basic Plots can be found on the HTML file uploaded. On this part, we set the focus on several types of data  analysis that displayed the above mentioned categories and information.
     - Data Visualization with Interactive Plots was conducted for an even thorough investigation and understading of the Netflix dataset, since it gives the ability to check the details on a lower level by comparison to Basic Plots. For interacting with these plots, you should clone the NetflixDataset-EDA_classification.ipynb Jupyter Notebook and run it on the local computer. Most interactive plots are also displayed on the HTML file (the only ones missing are the interactive widgets on which filtering by genre can be performed)
     
  # 3. Classification Tasks employed using multiple ML algorithms for three different experiments
       - The following classification algorithms have been employed on the experiments:
            i) Random Forest Classifier (Experiment I & II)
            ii) SVM Classifier (Experiment I & II)
            iii) Logistic Regression (Experiment I & II)
            iv) Pre-trained Bert model in English (Experiment III)
        - In order to re-create the experiments please clone the following Jupyter Notebooks:
            1. Experiment I & II: NetflixDataset-EDA_classification.ipynb
            2. Experiment III: NetflixDataset-Bert-model.ipynb
        - The results of the experiments have been the following:
            - Experiment I - Type based on Description Experiment
                Random Forest Classifier   : The accuracy is 73.81258023106547
                SVM (C = 1)                : The accuracy is 75.1604621309371
                Logistic Regression(C = 1) : The accuracy is 74.77535301668806
                Logistic Regression(C = 10): The accuracy is 75.54557124518614
            - Experiment II - Type based on Description Experiment
                Random Forest Classifier   : The accuracy is 37.869062901155324.
                SVM (C = 1)                : The accuracy is 32.22079589216945.
                Logistic Regression(C = 1) : The accuracy is 40.50064184852375
                Logistic Regression(C = 10): The accuracy is 41.91270860077022.
            - Experiment III - Related to the interpretation of the results for the Bert model, 
                               we obtained an accuracy of 0.8 on the train data set and 0.7 accuracy 
                               on the validation data set with a loss of 0.09 in the train data set and 0.1  
                               validation data set. For the evaluation part we obtained an accuracy of 0.7 on the test data set. 
     
     

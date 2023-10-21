![image](https://github.com/Ashutosh-ML/Project-COVID-19-prediction-system/assets/147541395/d2d33d06-1321-4a7f-be7d-2f832207dbce) 

# COVID 19 Prediction System
A speedy and accurate diagnosis of COVID-19 is made possible by effective SARS-CoV-2 screening, which can also lessen the burden on healthcare systems. There have been built prediction models that assess the likelihood of infection by combining a number of parameters. These are meant to help medical professionals all over the world treat patients, especially in light of the scarcity of healthcare resources. The current dataset has been downloaded from ‘ABC’ government website and contains around 2,78,848 individuals who have gone through the RT-PCR test. Data set contains 11 columns, including 8 features suspected to play an important role in the prediction of COVID19 outcome. Outcome variable is covid result test positive or negative. We have data from 11th March 2020 till 30th April 2020. Please consider 11th March till 15th April as a training and validation set. From 16th April till 30th April as a test set. Please further divide training and validation set at a ratio of 4:1.  


Please perform all appropriate feature engineering tasks. 
* Perform important data visualization techniques to find the pattern in data.
* Report characteristics of important features, such as total number and percentage of each category in a table format after performing all relevant tasks.
* Perform multiple machine learning models relevant to your hypothesis, justify your model.
* Perform important cost functions to justify which model is better. 

The following list describes each of the dataset’s features used by the model: 


A. Basic information: 
1. ID (Individual ID)
2. Sex (male/female). 
3. Age ≥60 above years (true/false) 
4. Test date (date when tested for COVID)


B. Symptoms: 
5. Cough (true/false).
6. Fever (true/false). 
7. Sore throat (true/false). 
8. Shortness of breath (true/false). 
9. Headache (true/false). 

C. Other information: 
10. Known contact with an individual confirmed to have COVID-19 (true/false).

D. Covid report
11. Corona positive or negative


# The Opioid Epidemic 
## A Machine Learning Approach to understanding the United States of America's Opioid Addiction and Overdose Epidemic

The increasing number of overdose deaths in the U.S.   is an urgent issue. The research we will be conducting will be an attempt to leverage data analysis and machine learning techniques in order to identify potential solutions, and most of all raise awareness.  This project was completed for DePaul University DSC 540 Course, Advanced Machine Learning


![Logo](https://www.insurancejournal.com/app/uploads/2020/11/opioid-1-scaled.jpg)

    
## Authors

- [@Amal-Nasir](https://github.com/Amal-Nasir)
- [@jordanrbickelhaupt](https://github.com/jordanrbickelhaupt)
- [@yiannimercer](https://github.com/yiannimercer)



  
## Datasets Used

- [**U.S. Opiate Prescriptions dataset** *contains a subset of data from The Centers for Medicare & Medicaid Services*](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Part-D-Prescriber.html)
    > Sub-datasets included 'Prescriber Info', 'Opioid Drug Descriptions' and 'Overdose counts by State'  
    > This dataset assisted in the development of a dataframe which summarized specific prescriptions of drugs for each state, combined with the total deaths for the same state(s)

- [**Deaths Casued by Opioids by State (1999-2014)**](https://data.world/health/drug-induced-deaths)
    > Basic dataset that totals the number of opioid deaths in each state for each years, beginning in 1999, up until 2014.  
    
- [**Summary File of Connecticut Medicare**](https://www.kaggle.com/cms/medicare-part-d-opioid-prescriber-summary-file)  
    > Data containing information on speciifc counties within the State of CT, explaning the rampant metrics of opioid prescriptions being prescribed each year, along with the number of drug-related overdoses in the same year

  
## Research Questions
* #### **How likely  a prescriber is going to prescribe an opioids medicine based on prescribed medicine per year?**  
    > Built a classification model which will learn from the prescribers who prescribed opioids, to predict the likelihood of a prescriber to prescribe opioids.  
* ####  **What states should we look out for when it comes to opioid overdose?**   
    > Performing random forest regression with different visualizations.  
* #### **Where are the most rampant areas of Opioid Prescribing Rates in Connecticut?**   
    > By performing thorough exploratory data analysis on data that provided geographical information (Connecticut) we were able to focus our initial understanding of the Opioid Drug and related Death Problem on specific areas of the State of Connecticut
* #### **Can we predict the number of state level deaths caused by opioid related overdoses?**   
    > Beginning with the prescriber dataset, we summarized this into a Pandas GroupBy Dataframe for each state, summing the total of each type of opioid that was described (and removing columns like Gender, Credentials and Opioid prescriber).  We then combined this dataset with the overdoses dataset, using the state as index, allowing us to view the total sums of the types of drugs each state prescribes and the total number of deaths each state has due to opioids.  From here, a series of Random Forest Regression models were developed to predict the total number of deaths due to Opioid overdoses
## Technologies

* **Python**
    > Data Manipulation (Pandas, Numpy)  
    > Data Visualization (Matplotlib, Seaborn)  
    > Machine Learning (Sklearn)
* **Tableau**
    > Numerous visualizations developed using this software
* **Jupyter Notebook** 
* **Git**
* **HTML**
* **Google Colab**

  
## Methods Used

### Machine Learning
* **Prescription Dataset**
    > Logistic Regression  
    > Gradient Boosting Classifier  
    > Random Forest Classifier   
    > Gaussian Naive Bayes  
    > Decision Tree Classifier  
    > Adaboost Classifier  
    > Voting Classifier (Soft and Hard voting)
* **Opioid Overdose Dataset**
    > Random Forest Regression
    > Support Vector Regression
* **Self Created Dataset**
    > Random Forest Regression with extensive GridSearchCV
### Data Cleaning
Extensive amounts of the data was cleaned to ensure that no missing observations were preseent, along with encoding certain varaibles like gender and speciality for a couple of our datasets

### Data Visualization
Tableau and Python (respective visualization libraries) were used extnsively to perform exploratory data analysis and to answer some of the posed research questions above



  
## Master Notebook

Please refer to [DSC540_GROUP 12_OPIOID OVERDOSES STUDY_MASTER NOTEBOOK.ipynb](https://github.com/jordanrbickelhaupt/Op/blob/main/DSC540_GROUP%2012_OPIOID%20OVERDOSES%20STUDY_MASTER%20NOTEBOOK.ipynb) to view this project in its entirety, along with our reseults and further discussion sections.
## Feedback
If you wish to contact anyone regarding this project for any comments, questions or concerns, please email Yianni Mercer at YJMercer@gmail.com
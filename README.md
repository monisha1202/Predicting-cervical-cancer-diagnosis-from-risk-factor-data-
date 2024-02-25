## Background 

According to World Health Organization, cervical cancer is the fourth most frequent cancer that have high mortality rate which affects women all around the world especially in low and middle-income countries.
Almost all cervical cancers are caused by human papillomavirus (HPV). HPV usually causes no symptoms so it can go undetected in many cases. For most women, HPV will go away on its own; however, if it does not, there is a chance that over time it may cause cervical cancer. Previous research has linked the following factors as risky [@risk_factor_research]:

- Having HIV
- Smoking
- Prolonged usage of birth control pills
- Having given birth to 3 or more children
- Having multiple sexual partners.
 
__Diagnosis__
A Pap test is used for initial screening. If cervical cancer is suspected,doctor may use the following methods to confirm presence of cancer[@diagnosis_research]:

- Biopsy
- Hinselmann test that examins the cells on an instrument called colposcope.
- Schiller's test
- Cervical cytology


## Business Understanding

The goal of this project is to examine how cervical cancer risk factors can predict cervical cancer diagnosis. Specifically, I will attempt to use patient data on cervical cancer risk factors to train machine learning models to predict a patient's cervical cancer diagnosis. The machine learning models developed in this report will use data on cervical cancer risk factors to predict whether a patient is likely to be diagnosed with cervical cancer. The goal is to build classification models that could alert doctors to patients with a high risk of cervical cancer, who may need more frequent screenings or other interventions. 


## Data Acquisition

- The dataset used in this project is the cervical cancer risk factor extracted from UCI Machine Learning Repository[@data_source]

- The dataset was collected at ”Hospital Universitario de Caracas” in Caracas, Venezuela which consists of demographic information, habits, and historic medical records of 858 patients with 32 attributes and 4 target classes (Hinselmann, Schiller, Cytology and Biopsy)

Age-sex-GAD7-PHQ9-GLAD

# Code for paper "Age and sex-related variability in the presentation of generalized anxiety and depression symptoms" published in Depression and Anxiety (2021). 
## Authors: Katherine N. Thompson, Christopher Hübel, Rosa Cheesman ... Gerome Breen, Thalia C. Eley. 
### https://doi.org/10.1002/da.23213

All code written by Katherine N. Thompson and Christopher Hübel.  

Analyses were conducted in R Studio version 4.0.2.  

Data used were from the Genetic Links to Anxiety and Depression (GLAD) Study (https://gladstudy.org.uk/)

The analysis script includes the following components:

1. Data preparation and descriptive statistics for the GLAD sample

2. Factor analyses
  
    a) Exploratory factor analyses: 1-6 factors run for 15 and 16 item model. 

    b) Confirmatory factor analyses: confirmation of 4 factor model in entire data set. 

3. Regression analyses with age and sex:
  
    a) Logistic regression analyses for individual symptoms (symptom_binary ~ age/10 + sex + PHQ.total.score + GAD.total.score)

    b) Linear regression analyses for factor scores (factor ~ age/10 + sex + PHQ.total.score + GAD.total.score)
  
4. Post hoc sensitivity analyses conducted:

    a) All factor analyses and regression models re-computed whilst stratifying based on completion during COVID: individuals that participated during the COVID-19 pandemic were excluded at three intervals.
    
    - 31st January 2020 (first UK case; N=2456)
    
    - 1st March 2020 (higher awareness; N= 1222)
    
    - 23rd March 2020 (first UK lockdown; N=342)
    
    
    b) Regression analyses were recomputed including highest education level (as a proxy for socioeconomic status) in the model. 
    
**Full paper reference:**
Thompson, K. N., Hübel, C.,Cheesman, R., Adey, B. N., Armour, C., Davies, M. R., Hotopf, M., Jones, I. R., Kalsi, G., McIntosh, A. M., Monssen, D., Peel,A. J., Rogers, H. C., Skelton, M., Smith, D. J., Walters, J. T. R., Breen, G., & Eley, T. C. (2021). Age and sex-related variability in the presentation of generalized anxiety and depression symptoms. Depression and Anxiety, 1–12. https://doi.org/10.1002/da.23213

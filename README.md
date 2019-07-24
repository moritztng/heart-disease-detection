# Heart Disease Detection
Detecting the presence of a heart disease in a patient

## The Problem
### Input
The Cleveland database consists of 13 features that a related to the condition of the heart.

        age: age in years
        sex: (1 = male; 0 = female)
        cp: chest pain type (4 values)
        trestbps: resting blood pressure
        chol: serum cholestoral in mg/dl
        fbs: fasting blood sugar > 120 mg/dl
        restecg: resting electrocardiographic results (values 0,1,2)
        thalach: maximum heart rate achieved
        exang: exercise induced angina
        oldpeak: ST depression induced by exercise relative to rest
        slope: the slope of the peak exercise ST segment
        ca: number of major vessels (0-3) colored by flourosopy
        thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
### Output
Given these 13 features, the goal is to predict if a heart disease is present (the 14th variable of the database).

## Motivation
This year my father had a heart attack. He was lucky that a cardiologist was present at the hospital. Hence, the heart attack was diagnosed correctly pretty fast and he was operated on quickly. However, normally the cardiologist would not have been there at this time and consequently the diagnosis would have taken far longer. It was clear to me that this task has to be automated by a machine learning algorithm. So I did a quick research and found the Cleveland database on Kaggle. My goal is to predict the presence of a heart disease given the features of the database. Let's go!

## The Data
https://archive.ics.uci.edu/ml/datasets/Heart+Disease
### Context
This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to this date. The "target" field refers to the presence of heart disease in the patient.(1: No heart disease ; 0: Heart disease)

### Attribute Information:
> 1. age
> 2. sex
> 3. chest pain type (4 values)
> 4. resting blood pressure
> 5. serum cholestoral in mg/dl
> 6. fasting blood sugar > 120 mg/dl
> 7. resting electrocardiographic results (values 0,1,2)
> 8. maximum heart rate achieved
> 9. exercise induced angina
> 10. oldpeak = ST depression induced by exercise relative to rest
> 11. the slope of the peak exercise ST segment
> 12. number of major vessels (0-3) colored by flourosopy
> 13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

The names and social security numbers of the patients were recently removed from the database, replaced with dummy values. One file has been "processed", that one containing the Cleveland database. All four unprocessed files also exist in this directory.

To see Test Costs (donated by Peter Turney), please see the folder "Costs"
Acknowledgements

### Creators:
1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D. 

## Author
This project was all done by myself. 

## License
The project is licensed under the MIT License. 

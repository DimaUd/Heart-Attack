# Heart-Attack
Supervised Learning by  Heart Attack Classifications

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e5/Diagram_of_the_human_heart_%28cropped%29.svg/611px-Diagram_of_the_human_heart_%28cropped%29.svg.png)

Heart.csv - is data from  https://archive.ics.uci.edu/ml/datasets/Heart+Disease 


# About The Dataset
###   Age : Age of the patient
###   Sex : Sex of the patient (1 = male, 0 = female)
###   exang: exercise induced angina (1 = yes; 0 = no)
###   ca: number of major vessels (0-3)
###   cp : Chest Pain type chest pain type
###   Value 1: typical angina
###   Value 2: atypical angina
###   Value 3: non-anginal pain
###   Value 4: asymptomatic
###   trtbps : resting blood pressure (in mm Hg)
###   chol : cholestoral in mg/dl fetched via BMI sensor
###   fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
###   rest_ecg : resting electrocardiographic results
###   Value 0: normal
###   Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
###   Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
###   thalach : maximum heart rate achieved
###   target : 0 = less chance of heart attack, 1 = more chance of heart attack


============================================================================
#### 
Important issues for my opinion when applying KNN  algorithm:
- Mixed data types (categorical and numerical)
  so the issue is how we can make in right way data preperation, how we can get from our data all information in the right way
  some sources about this:
  # 
 Evaluation of k‑nearest neighbour classifer performance for heterogeneous data sets <br />
 https://link.springer.com/content/pdf/10.1007/s42452-019-1356-9.pdf:<br />
 The data is first divided into pure numerical and pure binary features,<br />
 specifc distances are then applied  to the numerical and binary features,<br />
 and the result of the two distances is assembled into one single distance using a weighted average to form the combined distance value.<br />
 

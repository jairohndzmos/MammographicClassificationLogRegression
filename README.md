# **Mammographic Mass Classification Log Regression Approach**
# Introduction

Discrimination of benign and malignant mammographic masses based on some attributes, Building a ML model  using scikit-learn's class  LogisticRegression

# Dataset

6 Attributes in total (1 goal field, 1 non-predictive, 4 predictive attributes)  
  
- BI-RADS assessment: 1 to 5 (ordinal)
- Age: patient's age in years (integer)  
- Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)  
- Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)  
- Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)  
- Severity: benign=0 or malignant=1 (binominal, goal field!)*

### Source
"Mammographic masses" public dataset from the UCI repository has been used. (source: [https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass](https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass))

Matthias Elter  
Fraunhofer Institute for Integrated Circuits (IIS)  
Image Processing and Medical Engineering Department (BMT)  
Am Wolfsmantel 33  
91058 Erlangen, Germany  
matthias.elter@iis.fraunhofer.de  
(49) 9131-7767327  
  
Prof. Dr. Rüdiger Schulz-Wendtland  
Institute of Radiology, Gynaecological Radiology, University Erlangen-Nuremberg  
Universitätsstraße 21-23  
91054 Erlangen, Germany




## Results

Metrics shows some good results, as the following confusion matrix suggest

![alt text](https://i.imgur.com/5xucvaE.png)

There some others metrics supporting remarkable accuracy

##   Improvements

Seeking improve model accuracy, some tunning parameters or alternative techniques for supervised classification might helped in order to achieve it

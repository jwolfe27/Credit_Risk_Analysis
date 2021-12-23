<h1 align="center"> Credit Risk Analysis</h1>
<p align="center">
  <img src="https://user-images.githubusercontent.com/89044350/147165124-b9fa0e7f-323e-45d7-af0f-60259654e1f3.jpg")
       >
  </p>

<h1 align="center"> Project Overview</h1>
Utilizing a dataset provided by LendingClub, machine learning models were built using Python to establish which model proves to be the best when predicting credit risks

### Methods Used:
- Oversampling:
  - Utilizing RandomOverSampler & SMOTE

- Undersampling:
  - Utilizing ClusterCentroids
 
- Combination of Oversampling & Undersampling:
  - Utilizing SMOTEENN

- Comparing BalancedRandomClassifier and EasyEnsembleClassifier

### Toolbox:
- Dataset provided by LendingClub 
- Python Programming Language
- Jupyter Notebook (mlenv)

<h1 align="center"> Results of Analysis</h1>


<h2 align="center"> RandomOverSampler Model</h2>
<p align="center">
  <img src="https://user-images.githubusercontent.com/89044350/147165998-7fe0a5ba-c493-4b27-b66d-f29e2ad9108c.JPG")
       >
  </p>

As shown in the above image:
1. Balance Accuracy Score = 64%
2. High Risk Precision = 1%, Recall = 69%, F1 = 2%
3. Low Risk Precision = 100%, Recall = 59%, F1 = 74%



<h2 align="center"> Oversampling SMOTE Model</h2>
<p align="center">
  <img src="https://user-images.githubusercontent.com/89044350/147166638-0389a1d4-f215-45da-86c7-d358d4f26786.JPG")
       >
  </p>
  
As shown in the above image:
1. Balance Accuracy Score = 66%
2. High Risk Precision = 1%, Recall = 63%, F1 = 2%
3. Low Risk Precision = 100%, Recall = 69%, F1 = 82%



<h2 align="center"> Undersampling ClusterCentroids</h2>
<p align="center">
  <img src="https://user-images.githubusercontent.com/89044350/147167004-a455c945-5c87-444a-9f34-a1851a4ac179.JPG")
       >
  </p>
  
As shown in the above image:
1. Balanced Accuracy Score = 54%
2. High Risk Precision = 1%, Recall = 69%, F1 = 1%
3. Low Risk Precision = 100%, Recall = 40%, F1 = 57%



<h2 align="center"> Combination Sampling SMOTEENN</h2>
<p align="center">
  <img src="https://user-images.githubusercontent.com/89044350/147167661-796a3ead-08b1-45c3-9e10-229e9f2cfc99.JPG")
       >
  </p>
  
As shown in the above image:
1. Balanced Accuracy Score = 64%
2. High Risk Precision = 1%, Recall = 70%, F1 = 2%
3. Low Risk Precision = 100%, Recall = 57%, F1 = 73%



<h2 align="center"> Balanced Random Forest Classifier</h2>
<p align="center">
  <img src="https://user-images.githubusercontent.com/89044350/147167897-d3767e32-fd41-46a6-b021-39edd08876cf.JPG")
       >
  </p>
  
As shown in the above image:
1. Balanced Accuracy Score = 79%
2. High Risk Precision = 4%, Recall = 67%, F1 = 7%
3. Low Risk Precision = 100%, Recall = 91%, F1 = 95%



<h2 align="center"> Easy Ensemble Classifier</h2>
<p align="center">
  <img src="https://user-images.githubusercontent.com/89044350/147168095-cf6e2615-ef56-4822-b7e6-dbef4cd81eea.JPG")
       >
  </p>
  
As shown in the above image:
1. Balanced Accuracy Score = 93%
2. High Risk Precision = 7%, Recall = 91%, F1 = 14%
3. Low Risk Precision = 100%, Recall = 94%, F1 = 97%



<h1 align="center"> Summary of Analysis</h1>
All models used to perform credit risk analysis are weak when determining if a credit risk is high or not. The best option is the Easy Ensemble Classifier model with a Recall of 91%, detecting almost all "high risk" credit. Having said that, with a low precision a lot of low risk credits could be falsely identified as high risk which could hurt a banks revenues by missing out on those business opportunities.  It is tough to recommend any of these machine learning models to a bank due to their low precision percentages.











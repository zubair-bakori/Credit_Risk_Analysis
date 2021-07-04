# Credit_Risk_Analysis

## Overview of the Analysis:

  The purpose of this analysis is to addrees a credit card risk challenge that would be faced by Bakori Community Bank. By their nature credit card transactions present an           unbalanced classification problem. For this reason we used 6 (six) ML models in order to as accurately as possible predict risky situations and avoid them. The models addressed   oversampling, undersampling and bias reduction issues associated with the data.
  
##  Results:

  The balanced accuracy, precision and recall scores obtained for each of the six models are given below. The three combined give a very good picture of performance of the   model   and could be compared one against the other in order to select which model to use:
  
### Oversampling

   - Naive Random Oversampling: Accuracy = 64.3%; Precision = 99% and Recall = 75%.
    <img width="740" alt="Naive_Random" src="https://user-images.githubusercontent.com/79673198/124400815-59ff4f80-dcf3-11eb-8f43-cff6eaa564a6.png">
   - SMOTE Oversampling: Accuracy = 66.3%; Precision = 99% and Recall = 69%.
   <img width="753" alt="SMOTE" src="https://user-images.githubusercontent.com/79673198/124400837-7b603b80-dcf3-11eb-9727-d01e0926ede1.png">  

### Undersampling
   - ClusterCentroids = Accuracy = 66.3%; Precision = 99% and Recall = 40%
   <img width="740" alt="ClusterCentriods" src="https://user-images.githubusercontent.com/79673198/124400854-93d05600-dcf3-11eb-9b03-d7c9c3d79f1d.png">

### Over/Undersampling
   - SMOTEENN: Accuracy = 54.4%; Precision = 99% and Recall = 57%
   <img width="746" alt="SMOTEENN" src="https://user-images.githubusercontent.com/79673198/124401013-aa2ae180-dcf4-11eb-9f3f-49362bb426fc.png">

### Bias Reduction
   - BalancedRandomForestClassifier: Accuracy = 78.8%; Precision = 99% and Recall = 93%
   <img width="765" alt="Balanced_Random" src="https://user-images.githubusercontent.com/79673198/124400914-f45f9300-dcf3-11eb-8456-6f41f15a3c31.png">
   
   -  AdaBoost EasyEnsambleClassifier: Accuracy = 93.1.3%; Precision = 99% and Recall = 94%
   <img width="732" alt="Easy_Ensamble" src="https://user-images.githubusercontent.com/79673198/124400937-283ab880-dcf4-11eb-8e9f-10ef86ee8d9c.png">


##  Summary:
  We would recommend using the AdaBoost EasyEnsambleClassifier because it ggave the highest combination of the accuracy, precision and recall scores. 
  

        

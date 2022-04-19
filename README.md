# Credit Risk Analysis

## Background
The purpose of the analysis was to use machine learning to predict credit card risk. Using a dataset from LendingClub, several algorithms (i.e., oversampling, SMOTE oversampling, undersampling, combination sampling) and machine learning models (i.e. Balanced Random Forests, Easy Ensemble) to predict credit risk. Performance of the models was then evaluated.

## Results
### Oversampling
![oversampling](https://user-images.githubusercontent.com/96216947/163718567-170413ad-5840-4faf-afb9-c3b4d3067186.JPG)
#### - Balanced accuracy: 65.5%
#### - Precision: 1% (High Risk), 100% (Low Risk)
#### - Recall: 64% (High Risk), 67% (Low Risk)

### SMOTE Oversampling
![SMOTE_oversampling](https://user-images.githubusercontent.com/96216947/163718596-d0d47da6-b611-41b2-97b7-2d7299a32849.JPG)
#### - Balanced accuracy: 63.1%
#### - Precision: 1% (High Risk), 100% (Low Risk)
#### - Recall: 61% (High Risk), 65% (Low Risk)

### Undersampling
![undersampling](https://user-images.githubusercontent.com/96216947/163718615-8d4a7abb-397e-4eb7-84f2-5a96a5ae090d.JPG)
#### - Balanced accuracy: 51.0%
#### - Precision: 1% (High Risk), 100% (Low Risk)
#### - Recall: 59% (High Risk), 43% (Low Risk)

### Combination (Over and Under) Sampling
![over_undersampling](https://user-images.githubusercontent.com/96216947/163718656-289fccbb-bc05-4d15-91d8-6b4a98f3bbf2.JPG)
#### - Balanced accuracy: 65.7%
#### - Precision: 1% (High Risk), 100% (Low Risk)
#### - Recall: 71% (High Risk), 60% (Low Risk)

### Balanced Random Forest Classifier
![balanced_random_forest](https://user-images.githubusercontent.com/96216947/163718708-34af4b34-cf98-4006-901e-4767200a8354.JPG)
#### - Balanced accuracy: 78.4%
#### - Precision: 3% (High Risk), 100% (Low Risk)
#### - Recall: 68% (High Risk), 89% (Low Risk)

### Easy Ensemble AdaBoost Classifier
![easy_ensemble](https://user-images.githubusercontent.com/96216947/163718713-ae1912e4-8c46-42d6-9039-8796ed1e29f4.JPG)
#### - Balanced accuracy: 92.5%
#### - Precision: 7% (High Risk), 100% (Low Risk)
#### - Recall: 91% (High Risk), 94% (Low Risk)

### Summary
Overall, the ensemble classifiers were the most effective models as they were the most accurate, precise, and sensitive models. The Easy Ensemble AdaBoost Classifier was the superior model in all categories. Despite the success of the model, it is not recommended to predict credit risk as the precision is very low. The low precision will likely result in good candidates for loans being turned away; however, this may be desireable if a limited number of loans are availble and equity is not a concern.

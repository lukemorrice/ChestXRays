# ChestXRays

Using Deep Learning to classify chest x-rays of patients with pneumonia.
I created two models: one using a Convolutional Neural Network with MaxPooling and dropout, and a second using Transfer Learning, using ResNet V2 50 trained on ImageNet.
I didn't expect the latter to perform well, it was more of a test. However, the former CNN produced an accuracy of ~89%.

## Data Source
Downloaded from Kaggle: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

## Notes on the data
Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.
For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

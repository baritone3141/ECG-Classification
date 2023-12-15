# ECG-Classification
This is a project I worked on for the course project component of CENG 6000N (Deep Learning for Chemical and Biological Engineering) in the Hong Kong University of Science and Technology.
IMPORTANT: Please download the dataset separately from the link provided below!
## Motivation
Cardiovascular (heart) diseases are a leading cause of death worldwide (one of the top 10 according to various sources). Common heart diseases include myocardial infarction, dysrhythmia, cardiomyopathy, etc. For the diagnosis of heart diseases, an electrocardiogram (ECG) is useful for doctors' timely diagnoses. It will be useful and helpful to automate the analysis of ECG, especially when there is a shortage of personnel.
## Objective
The main objective of this project is to classify the type of Electrocardiogram (ECG) from a given dataset. The dataset used was the Physionet MIT-BIH Arrhythmia Dataset, [available here](https://www.physionet.org/content/mitdb/1.0.0/). This dataset was preprocessed by Shayan Fazeli on [Kaggle](https://www.kaggle.com/datasets/shayanfazeli/heartbeat) so that the ECG can be represented graphically.
There are 5 main classes of ECG, namely, N, S, V, F, and Q. Each of the classes is a specific annotation that represents stages of a heartbeat. The diagram below provides the representation of each class.
| Category | Annotations |
| -------- | ----------- |
| N | Normal, left/right bundle branch block, atrial escape, or nodal escape |
| S | atrial premature, aberrant atrial premature, nodal premature, or supra-ventricular premature |
| V | Premature ventricular contraction or ventricular escape |
| F | Fusion of ventricular and normal |
| Q | Paced, Fusion of paced and normal, or Unclassifiable |

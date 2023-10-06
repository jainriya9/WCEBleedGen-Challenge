# Auto-WCEBleedGen-Challenge
The objective of Auto-WCEBleedGen-Challenge is to provide opportunity for the development, testing and evaluation of Artificial Intelligence (AI) models to detect and classify the Bleeding and Non-Bleeding frames extracted from Wirless Capsule Endoscopy (WCE) videos and further detect the bleeding region in that frame.

# Machine Learning Dataset for Computer Vision
The dataset for the Auto-WCEBleedGen-Challenge consists of Training Dataset, Test Datset 1 and Test Dataset 2.
Training Dataset: It consists of Annotations and Images for both Bleeding and Non-Bleeding frames along with Bounding boxes for the Bleeding frames. The Training Data is divided in 80:20 as training and validation dataset.
Testing Dataset: -Test Dataset 1 contains 49 frames collected randomly from seven different patient's data.
                 -Test Dataset 2: contains 515 frames collected from twenty-three different patient's data. 
                 
## Overview
The repository consists of the Machine Learning Model using Computer Vision to detect detect and classify the Bleeding and Non-Bleeding frames and detect the bleeding region from the provided dataset. The model is built using Kaggle. 
TRAINING PHASE: In this phase, the training dataset is divided into training and validation sets. The model capable of classifying frames and detecting bleeding regions is developed. The model, its weights, and relevant files are stored, and its performance is evaluated using metrics for both classification and detection. Evaluation metrics for Classification- Accuracy, Recall, F1-Score and evaluation metrics for Detection- Average Precision, Mean-Average Precision, Intersection over Union (IoU). An interpretability plot is generated to understand the model's decision-making.
TESTING PHASE: The model created using training dataset is applied on testing dataset 1 and 2 to predict the frames in them. Evaluation of the model is done for both classification and detection as done for when training data was used. An interpretability plot is generated to gain insights into the model's performance on unseen data. 

### Key Features

 

## Data Samples



## Usage



## Test Dataset 1


## Test Dataset 2


## Excel sheet



## Model Evaluation

[!page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/e3960ed9672b089682ebfdd390510a6e07e1323d/Evaluation_Metrices.png)






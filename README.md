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



## Best Images of Test Dataset and Test Dataset 2

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/cdd2b511710bdb31a26344401918343677a88493/BestImages/best1.png" alt="Image 1" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/4f7b27dde47fea2857a3d48ecce38ce6d8ffab2b/BestImages/best2.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/50f381eb0d5a1a384be78ae8f05fbd13217955ad/BestImages/best3.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/a6c5bb69d162307edc3d5c4d7bc3174fe8b4a54a/BestImages/best4.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/8ebb9084c03f8edf925473cf3871cdcd41e414a2/BestImages/best5.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/700733a4b1a6943c04be78a9a014b3b1a85c282c/images/bbox_A0010.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/2f2283ce410aafb49ef0cc413435a5ec0423ee30/images/bbox_A0011.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/fecc6b9600de863e0028bd62bc59d305aafbfb11/images/bbox_A0016.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/7637a19da636ba16941c673e257173aea6a5aacf/images/bbox_A0021.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/0991e8f01d55f2d30ff744de428fbd5431c19514/BestImages/best10.png" alt="Image 2" width="250" height="250">
  
</div>

## Excel sheet

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/35a8dc144b49e435ccba2ba8e045af2a8a3696dc/excelimg.png)



## Model Evaluation

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/e3960ed9672b089682ebfdd390510a6e07e1323d/Evaluation_Metrices.png)






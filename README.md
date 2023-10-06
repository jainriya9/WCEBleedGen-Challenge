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


## Model Evaluation

<p align="center">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/d9e4452caa3072871bfb904251ad253e9f88a7f5/Evaluation_Metrices.png" alt="Page">
</p>

## Best Images of Validation Dataset

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/fc8e176e7457c1e8709d029ca8ad21775aee4286/images/A0000.png" alt="Image 1" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/fc8e176e7457c1e8709d029ca8ad21775aee4286/images/A0003.png" alt="Image 1" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/fc8e176e7457c1e8709d029ca8ad21775aee4286/images/A0005.png" alt="Image 1" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/fc8e176e7457c1e8709d029ca8ad21775aee4286/images/A0008.png" alt="Image 1" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/fc8e176e7457c1e8709d029ca8ad21775aee4286/images/A0009.png" alt="Image 1" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/fc8e176e7457c1e8709d029ca8ad21775aee4286/images/A0025.png" alt="Image 1" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/fc8e176e7457c1e8709d029ca8ad21775aee4286/images/A0030.png" alt="Image 1" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/fc8e176e7457c1e8709d029ca8ad21775aee4286/images/A0046.png" alt="Image 1" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/fc8e176e7457c1e8709d029ca8ad21775aee4286/images/A0049.png" alt="Image 1" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/10c5a3925b15fd9e97dde0f7be76d35778034269/images/bbox_A0001.png" alt="Image 1" width="250" height="250">

  </div>




## Best Images of Test Dataset and Test Dataset 2

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/cdd2b511710bdb31a26344401918343677a88493/BestImages/best1.png" alt="Image 1" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/4f7b27dde47fea2857a3d48ecce38ce6d8ffab2b/BestImages/best2.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/50f381eb0d5a1a384be78ae8f05fbd13217955ad/BestImages/best3.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/a6c5bb69d162307edc3d5c4d7bc3174fe8b4a54a/BestImages/best4.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/8ebb9084c03f8edf925473cf3871cdcd41e414a2/BestImages/best5.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/700733a4b1a6943c04be78a9a014b3b1a85c282c/images/bbox_A0010.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/2805010036cf42f8b9acff53e9ae2b859365d12e/images/bbox_A0047.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/fecc6b9600de863e0028bd62bc59d305aafbfb11/images/bbox_A0016.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/2de25a2453d920603a6311e6168105c4ac6ccb92/images/bbox_A0031.png" alt="Image 2" width="250" height="250">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/ffc8e2ab673b852bb45ac75ac6197f3d6e4d665e/images/bbox_A0042.png" alt="Image 2" width="250" height="250">
  
</div>

## Excel sheet

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/d9e4452caa3072871bfb904251ad253e9f88a7f5/excelimages/excelimg.png" alt="Image 1" width="300" height="400">
  <img src="https://github.com/jainriya9/WCEBleedGen-Challenge/blob/d9e4452caa3072871bfb904251ad253e9f88a7f5/excelimages/excelimg2.png" alt="Image 1" width="300" height="400">

  </div>

## Motivation behind the Project

## Contributing
Contributions are welcome!! If you have any suggestions, improvements or bug fixes, feel free to open an issue or submit a pull request. 

## License
Made by Team- MedTech Marvels











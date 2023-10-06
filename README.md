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

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/cdd2b511710bdb31a26344401918343677a88493/BestImages/best1.png)

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/4f7b27dde47fea2857a3d48ecce38ce6d8ffab2b/BestImages/best2.png)

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/50f381eb0d5a1a384be78ae8f05fbd13217955ad/BestImages/best3.png)

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/a6c5bb69d162307edc3d5c4d7bc3174fe8b4a54a/BestImages/best4.png)

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/8ebb9084c03f8edf925473cf3871cdcd41e414a2/BestImages/best5.png)

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/6962664cf1d77f39b0eef3791c4ebefc5364fa37/BestImages/best6.png)

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/00d87d5849eea07a9c419db5b3f33557a74605c3/BestImages/best7.png)

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/efb61bd973117125b3b7ada3409a51fd06df6284/BestImages/best8.png)

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/6ed8da86d74e69e43fb4f02c3435a27039d06ed1/BestImages/best9.png)

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/0991e8f01d55f2d30ff744de428fbd5431c19514/BestImages/best10.png)














## Excel sheet

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/35a8dc144b49e435ccba2ba8e045af2a8a3696dc/excelimg.png)



## Model Evaluation

![page](https://github.com/jainriya9/WCEBleedGen-Challenge/blob/e3960ed9672b089682ebfdd390510a6e07e1323d/Evaluation_Metrices.png)






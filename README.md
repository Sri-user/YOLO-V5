# YOLO-V5 on colab to Localize and Classify Pneumonia Images
Using the Object detection model YOLO-V5 from Ultralytics to localize and classify custom images

This repository contains the implementation of YOLO-V5 in colab to detect and classify the Pneumonia and Normal Images

Data used for this model is from the following link (https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data)

Yolo_v5_Data_Preparation.ipynb - This file has all the necessary steps to convert our dataset into a format suitable for YOLO-V5 Implementation

We have to clone the git repository of YOLO-V5 https://github.com/ultralytics/yolov5

YOLO_V5_Training.ipynb - This file contains the operations and steps which has to be done to run the training for YOLO-V5 on your images

Finally YOLO_V5_Inference.ipynb - Here we predict and validate the model results on our saved weights from the training

-------------------------------------------------------------------------------------------------------------------------------------------
# In the future i am planning to add Indian Rupee Detection and Classification using YOLO-V5

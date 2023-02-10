# OCR_resnet

## Project Description ##

This project is a Optical Character Recognition task.<br>
This task is to recognize Korean from a selected dataset by useing EAST model.

## File Description ##

+ model.py

  code for constructing EAST model
  
 + loss.py
 
  code for defining the loss function for training
  
+ east_dataset.py

  code for construcing a dataset class for training model
  
+ dataset.py

  code for constructing a dataset class that provides images and text bounding boxes

+ train.py

  code for implementing model training
  
+ inference.py

  code for conducting model inference process
  
+ detect.py

  code for constructing inference and detection functions
  
+ deteval.py

  code for constructing functions for DetEval
  
+ convert_mlt.py

  code for transfer ICDAR dataset images into ufo format
  
+ requirements.txt

  requirements for implementation

+ /eval_dataset

  folder for evaluation image dataset
  

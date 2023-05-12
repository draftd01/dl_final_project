# dl_final_project
DL Final Project (Medical Image Segmentation)

# Project Description
## Project Title
Medical Image Detecting in Different Models
## Team Members
Daniel Drafta and Dania Elsheikh
## Goal/Objective
The goal of this project is to run different image segmentation models on pancreas medical images to detect tumors and compare accuracies of each model, focusing mainly on false negative rates, as those will be most important when detecting medical issues such as tumors or cancer. Having a high false negative rate will lead to unnecessary death that could have been avoided. We want to see which model is best for this task, as well as she how optimizing the parameters will change the 
## Challenges
One challenge includes working with a large data set and having to build the model from scratch. Because we will be working with three large models, changing parameters multiple times, this might take a while and have a high computational cost. 
 
## Approach/Technique
Different models will be used. The first model will be a not pretrained model. The second will be a pretrained version of the model
Compare model metrics of a pre-trained and not pre-trained Mask R-CNN model with a ResNet-50-FPN backbone
## Implementation Details
We will be using google colab’s GPU to train the models as this would be faster than training them the our devices’ CPUs
## References
https://github.com/JunMa11/SegLoss
https://github.com/pytorch/vision/tree/main/references/detection

# Code decription
The repo contains 2 ipynb: Daniel's project code that contains the code to train the not pretrained model while Dania's project code contains the code to train the pretrained model on our dataset. 
Daniel's code contains both of the evaluations

# How to run 
All the code was run through colab. It would not possible directly from this repo without downloading the necessary zips from the referenced github repos and adjusting the paths in the notebook. However, results from the cells that we ran can be viewed with running any code by opening the ipynb file. 

## Example from top few lines of ipynb file
![image](https://github.com/draftd01/dl_final_project/assets/60448623/e8a75dba-45eb-4037-9e1e-5b7f38f86be1)

# Results
Our final model metric results can be viewed in the last few cells of the daniel_project_code.ipynb, which include average accuracy, false negative rate, recall, and precision across the defined test set.
![image](https://github.com/draftd01/dl_final_project/assets/60448623/bc488500-b95a-4a57-9c89-2603fba05f29)
![image](https://github.com/draftd01/dl_final_project/assets/60448623/3ea1c83c-5d09-454f-a689-d2861d01edac)


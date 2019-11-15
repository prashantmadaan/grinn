																# GRINN : Garment Recognition In Neural Networks
GRINN is a neural network based recognition system which is used to regognize/classify the type of garment. 

## Use Case
The model is specifically trained for the laundry scenarios where clothes from a customer's bag are checked for stains on the table. The camera above the table takes the video of the table as the clothes are being checked and the GRINN system recognises what kind of clothes for a particular system. The ultimate goal is to record the number of clothes in each category for a customer. 

## Current Progress
We have completed the following milestones in our project : 
1. Exploring the problem domain with the stakeholders and deciding on the problem statement. 
2. Creating a training dataset video with personal cothing articles. 
3. Extracting the images out of the video. 
4. Deciding on categories and annotating the images accordingly. 
5. Pre-Processing images with techniques like image dialtion and region of interest extraction. 
6. Running State of the art models like resnet and vgg16 on the data and observe results. 


Next Steps:
We plan to find ways to generalise our model. One of the ideas is to use the categories from the fashion-net dataset and training our model on it. Also, the results from image pre-processing are not promising. We will explore training a segmentation model to segment the clothes from the surrondings to make the predictions more accurate. 


# **Build a Traffic Sign Recognition Program** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<img src="test_videos_output/img1.png" width="480" alt="Combined Image" />

Overview
---

In this project, I will use what I've learned about deep neural networks and convolutional neural networks to classify traffic signs. I will train and validate a model so it can classify traffic sign images using the German Traffic Sign Dataset. After the model is trained, I will then try out my model on images of German traffic signs that I find on the web.

To meet specifications, the project will require submitting three files:

- the Ipython notebook with the code  
- the code exported as an html file  
- a writeup report either as a markdown or pdf file  


The Project goals / steps
---
The goals / steps of this project are the following:
- Load the data set
- Explore, summarize and visualize the data set
- Design, train and test a model architecture
- Use the model to make predictions on new images
- Analyze the softmax probabilities of the new images
- Summarize the results with a written report


The Project Rubrics
---

1. Files Submitted  
(1)Submission Files.  
 [Ipython notebook with code](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/P2.ipynb)  
 [HTML output of the code](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/P2.ipynb)  
 [A writeup report](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/Writeup_of_Lesson8.pdf)
 
2. Dataset Exploration  
(1)Dataset Summary  
The submission includes a basic summary of the data set.
 [Pictures of Calibration](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/output_images/1_Calibration)  
(2)Exploratory Visualization  
The submission includes an exploratory visualization on the dataset. 
 [Pictures of Calibration](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/output_images/1_Calibration)  

3. Design and Test a Model Architecture   
(1)Preprocessing    
The submission describes the preprocessing techniques used and why these techniques were chosen.  
 [Distortion corrected images](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/output_images/2_Undistortion\Camera)   
(2)Model Architecture     
The submission provides details of the characteristics and qualities of the architecture, including the type of model used, the number of layers, and the size of each layer. Visualizations emphasizing particular qualities of the architecture are encouraged.  
 [Distortion corrected images](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/output_images/2_Undistortion\Camera)   
(3)Model Training      
The submission describes how the model was trained by discussing what optimizer was used, batch size, number of epochs and values for hyperparameters. 
 [Distortion corrected images](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/output_images/2_Undistortion\Camera)   
(4)Solution Approach    
The submission describes the approach to finding a solution. Accuracy on the validation set is 0.93 or greater.
 [Distortion corrected images](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/output_images/2_Undistortion\Camera) 

4. Test a Model on New Images  
(1)Acquiring New Images  
The submission includes five new German Traffic signs found on the web, and the images are visualized. Discussion is made as to particular qualities of the images or traffic signs in the images that are of interest, such as whether they would be difficult for the model to classify.     
 [Video: project_video_output.mp4](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/test_videos_output)   
(2)Performance on New Images  
The submission documents the performance of the model when tested on the captured images. The performance on the new images is compared to the accuracy results of the test set.    
 [Video: project_video_output.mp4](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/test_videos_output)  
 (3)Model Certainty - Softmax Probabilities  
The top five softmax probabilities of the predictions on the captured images are outputted. The submission discusses how certain or uncertain the model is of its predictions.  
 [Video: project_video_output.mp4](https://github.com/kkumazaki/Self-Drivig-Car_Project2_Advanced-Lane-Finding/tree/master/test_videos_output)  
  
   *: Please refer the writeup report for details!



---
layout: archive
title: "Publications"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
* Abhijit Baul*, Nian Wang, Choyi Zhang, Leslie Ying, Ukash Nakarmi, “SELF-LEARNED KERNEL LOW RANK APPROACH TO ACCELERATED HIGH RESOLUTION 3D DIFFUSION MRI”, Under Review. <b> <a href="https://drive.google.com/file/d/1cZMwD9qnPEN7KL3jXZ0UgjKqIiQAFWOU/view?usp=sharing">Paper Link</a> </b>

  * <b>Overview</b>:
The reconstruction of MRI from undersampled data is ill-posed and results in aliased images. Similar to low rank and sparse methods, that reconstruct images from umdersampled k-space data, the Kernel Low Rank (KLR) also maps the data into a low dimensional embedding but unlike in low rank and sparse techniques, KLR applies a nonlinear transformation to define the new representation space and enforces low rankness in the kernel space. Our main contributions are : 1) Developed a Kernel Low Rank method
that do not require low-resolution images, 2) Acquired High Resolution ground truth data with several diffusion directions
and investigated the effect of i) undersampling in k-space only and ii) undersampling in both k-space and diffusion direction
for meniscus dMRI, 3) Studied the efficiency of Kernel-lowrank technique in meniscus diffusion MRI. 

<img src="https://github.com/abhijit-buet/abhijit-buet.github.io/blob/master/_pages/web_1.jpg" class="centerImage" width="360" height = "256" >




* Abhijit Baul*, Jingru Zhang, Lingtao Wu, Hongkai Yu, Weidong Kuang, <b>"Learning to Detect Pedestrian Flow in Traffic
Intersections from Synthetic Data" </b>, 24th IEEE International Conference on Intelligent Transportation Systems (ITSC 2021), <b>Accepted</b> (h5 index - 49). <b> <a href="https://drive.google.com/file/d/12JTaBG-rgahMRnsL6DuV1MeA8U7kuP4p/view?usp=sharing">Paper Link</a> </b>



<b>Overview</b>:

<h6>
 The goal of this research project was to detect pedestrian flow at the traffic intersection. As there was no available dataset to accomplish the task, we have created a synthetic pedestrian dataset using GTA V video game. 
 Then we performed domain adaptaion using Cycle GAN, translating the synthetic images to photo-realistic images. In the end, we finetuned our PedestrianNet using a small amount of real data.
 <h1> Dataset
  <h6>
   Our Synthetic Traffic-intersection Pedestrian Dataset will be released soon.
<h1> Proposed Framework  
 <h6> 
  <img src="https://github.com/abhijit-buet/Images/blob/main/Summary.PNG" class="centerImage" width="360" height = "256">
   
   
   Our proposed PedestrianNet is a two branch CNN network where we have used AlexNet as feature extractor.
   We required two branch as the input consists of image frames and their corresponding optical flow.
   
   <h1> PedestrianFlowNet  
  <h6>
     <img src="https://github.com/abhijit-buet/Images/blob/main/AlexNet.PNG" class="centerImage" width="360" height = "256">
    
 <h1> Result
  <h6>
    
   Here, we have tried to detect pedestrian flow in three different direction - from left to right, from right to left and combined number of pedestrian. We have compared our result with YOLO V3 as a human detector. Mean Absolute Error(MAE) and Mean Square Error(MSE) were used as evaluation metric.
   
   <img src="https://github.com/abhijit-buet/Images/blob/main/Capture.PNG" class="centerImage" width="360" height = "256"> </h6>




* W. Kuang, Abhijit Baul*,<b> “A Real-time Attendance System Using Deep-learning Face Recognition”</b>,
ASEE Virtual Annual Conference Content Access, June, 2020. <b> <a href="https://peer.asee.org/a-real-time-attendance-system-using-deep-learning-face-recognition">Paper Link</a> </b>
   
  * <b>Overview</b>: Here, we have collected a face dataset from the students, Used that dataset to train a Face detection architecture, then used that to take attendance.

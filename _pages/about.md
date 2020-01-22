---
permalink: /about/
title: "About"
---

# Me
I am Lu Yu(俞露), a Master's student at UC Berkeley, majoring in Computer Science and Electronic Engineering advised by Prof. Alexandre M. Bayen. My research interest lies in optimization, computer vision (object detection; inpainting; generative model), reinforcement learning.

# Research Experiences

* ##Inpainting Model with Texture-Aware Decoder Guided by Image Segmentation
Research Assistant under Professor Kurt Keutzer at UC Berkeley
	* Designed and implemented an inpainting pipeline for street view images using Pytorch
	* Our inpainting pipeline includes two-branch information encoders: a content encoder and a context encoder, followed by a texture-aware decoder
	* The pipeline performs better than the state of the art in both quantitive and qualitative metrics with big holes inpainting

* ##Pixel Learning with Deep-RL for Mixed Autonomy Traffic
Research Assistant under Professor Alexandre M. Bayen at UC Berkeley
	* Main contributor to building a real-world robotics testbed for testing reinforcement learning algorithms developed in simulation, mainly responsible for the computer vision part
	* Designed and implemented a pipeline in both Python and C++ to track intelligent cars accurately in real time using K-means clustering and extended Kalman filter
	* The tracking of the coordinate and velocity is robust with low latency and obtained accuracy of 100%

* ##Hessian AWare Quantization of Neural Networks with Mixed-Precision
Research Assistant under Professor Kurt Keutzer at UC Berkeley
	* Based on the loss landscape for quantized models to analyze the Hessian matrix of each layer for the quantization scheme in Python
	* Implemented the mixed-precision quantization based on the Hessian information: the layer with a higher top eigenvalue of the Hessian matrix was assigned with more bits when being quantized
	* Conducted a comprehensive survey for the current quantization schemes including LQ-Net, PACT, HAQ, DoReFa Net and so on

# Professional Experience
* ##Fabu America
	* Improved automotive obstacle detection accuracy by applying and combining several existing frameworks such as Cascade RCNN and PVANet; Reduced the computational cost and lightened the network’s redundancy by incorporating inception structure and modified C.ReLU
	* Solved the problem of unbalanced dataset, by using the synthetic minority over-sampling method
	* Improved the obstacle detection accuracy by over 2%, and reduced both the training and detection latencies

* ##Alibaba-Zhejiang University Joint Research Institute of Frontier Technologies
	* Designed and implemented a SLAM system in C++ , for an intelligent car to achieve automatic navigation
	* Compared the performances of different traditional feature matching methods, including ORB and FAST
	* Implemented a VGG encoder to reduce the dimension of the images and to extract the corners from the images
	* Used a VGG convolutional neural network to calculate the homography matrix from the corners detections


# Visual_perception
I just implemented some assignments done for the course of Visual Perception during my Masters. It includes

## Augmented Reality with Homographies
This assignment contains the implementation of object recognition and robust model fitting using RANSAC for homography estimation. The goal of this assignment is to locate a given reference object in another image of a scene containing various objects. This task has applications in augmented reality and robotics, where a robot with a camera needs to recognize and locate a specific object in its environment.

## Corner Detection & Feature Tracking
In this assignment, I have implemented a custom Harris corner detector from scratch. Then utilized this detector to track keypoints in a sequence of images, specifically the first 80 frames from the KITTI Visual Odometry dataset. The main goals of this assignment were as follows:
Harris Corner Detector Implementation
Keypoint Tracking with Patch Templates
Keypoint Tracking with SIFT Descriptors

## Epipolar Geometry & 8-Point Algorithm
In this exercise, I implemented the well-known 8-Point Algorithm to estimate the fundamental matrix from correspondences, allowing me to recover essential information about the geometry of the scene and camera. This algorithm is widely adopted in computer vision and photogrammetry.

## Kohonen Network
The ultimate aim will be to automatically detect patients and healthy subjects (controls) using data from markers placed on the subjects. This exercise contains the implementation of training and testing the kohonen Network. The instructor has provided with 3 files, the ‘healthy.mat’ file contains data from healthy subjects and the ‘patient.mat’ contains patient data. Each line corresponds to the data (time series) coming from one subject.  The time series is made up of the displacements of markers placed on the joints of subjects. There are ten subjects in each file. Of course, the same markers are used for all subjects. I do not have to adjust anything in each time series as the information from each marker has already been put in the correct position in the time series.

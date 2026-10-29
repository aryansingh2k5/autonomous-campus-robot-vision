# Autonomous Campus Robot Vision

A computer vision project focused on building an **object detection pipeline for autonomous service robots** operating in a university campus environment.

The goal of this project is to enable a robot to detect and classify surrounding objects such as **humans, bicycles, cars, and stray animals** for safe navigation and obstacle avoidance.

## Overview

This project uses **YOLO (You Only Look Once)** with **OpenCV** to perform real-time object detection on campus scene images.

The detection system identifies multiple objects in a frame and draws **bounding boxes with class labels**, simulating the perception layer of an autonomous campus robot.

## Features

* real-time object detection
* multi-object classification
* bounding box visualization
* label prediction
* performance evaluation
* campus scene analysis

## Objects Detected

* Humans / Pedestrians
* Bicycles
* Cars
* Stray animals (dogs / cats)

## Tech Stack

* Python
* OpenCV
* YOLO
* NumPy
* Matplotlib
* scikit-learn

## Workflow

1. Load campus scene images
2. Preprocess images
3. Run YOLO inference
4. Detect objects
5. Draw bounding boxes
6. Evaluate performance using:

   * Precision
   * Recall
   * F1-score

## Why I built this

I wanted to explore how autonomous robots perceive their surroundings using computer vision and how real-time detection can be applied in navigation and safety systems.

This project helped me understand the role of object detection in **robotic perception and obstacle-aware navigation**.

## Future Improvements

* fine-tune on campus-specific dataset
* integrate video stream / live camera
* real-time robot navigation simulation
* combine with depth estimation / LiDAR
* improve small-object detection

## Applications

* service robots
* delivery robots
* autonomous campus navigation
* smart surveillance
* robotic safety systems

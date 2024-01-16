# CaDOd Project: Enhanced Object Detection in Computer Vision

## Project Overview

The CaDOd Project is an ambitious initiative in computer vision, focusing on the advanced detection of cats and dogs within images. Utilizing cutting-edge deep learning techniques, this project spans four progressive phases, each building on the previous to create a sophisticated object detection system.

## Phases Breakdown

- **Phase 1: Project Proposal** - Establishes the foundation including data selection, evaluation metrics, baseline models, and development pipelines.
- **Phase 2: EDA and Baseline Pipeline** - Involves Exploratory Data Analysis and establishing baseline models using SKLearn, including feature engineering and hyperparameter tuning.
- **Phase 3: HomeGrown and PyTorch Deep Learning** - Implements homegrown models with extended loss functions and constructs PyTorch pipelines for classification and regression tasks.
- **Phase 4: Enhanced Object Detection and Model Refinement** - Focuses on refining the multi-task model using EfficientDet (D0-D7) for cats and dogs detection, and exploring YoloV8 and Fully Convolutional Neural Network (FCN) for single-object detection.

## Key Features

- Integration of various loss functions like BCE, MSE, and regularization.
- Advanced model optimization using Intersection over Union (IoU) and EfficientDet architectures.
- Comparative analysis of EfficientDet D0 and D7 models.
- Experiments with YoloV8 and a FCN for diverse detection challenges.
- Real-time training visualization using Tensorboard.

## Data Description

The project uses a subset of Open Images V6, containing 12,966 images of dogs and cats. Image bounding boxes are detailed in `cadod.csv`, encompassing various attributes like coordinates, object classes, and box origin.

## Results and Discussion

The project showcases a range of models with varied performance metrics. Key highlights include:

- YoloV8 showing promising results in classification accuracy.
- PyTorch Regression and EfficientDet-D7 emerging as effective for bounding box prediction.
- Challenges faced due to hardware limitations, impacting model optimization.

## Future Work

Future directions include leveraging GPU capabilities for training, conducting extensive hyperparameter tuning, and developing homegrown models to compete with established architectures.

## Repository Content

- Jupyter notebooks for each project phase.
- Data files including images and annotations.
- Model training and evaluation scripts.
- Visual results and Tensorboard logs.

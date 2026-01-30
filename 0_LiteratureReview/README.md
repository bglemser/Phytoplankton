# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: Convolutional neural networks and vision transformers for Plankton Classification

  - **[Link](https://www.sciencedirect.com/science/article/pii/S157495412500281X)**
  - **Objective**:
  -  Study tries out ensembles combining different Convolutional Neural Network (CNN) models and transformer architectures to see if they enhange plankton recognition
  -  Can different optimization algorithms result in more robust and efficient classification across various plankton datasets?
  - **Methods**:
  - fine-tuning of established neural network architectures, all initialized with ImageNet pre-trained weights
  - exploring multiple Adam-based optimizers
  - **Outcomes**:
  - successfully built a deep learning methodology based on Faster R-CNN, a two-stage detector,
  - one-stage detectors are not suitable for microscopy phytoplankton images
  - **Relation to the Project**:
  - Investigated many of the CNN architectures we used
  - using phytoplankton datasets
  - But images could hold several species, so object detection and then classification was used --> we only need classification
    

- **Source 2**: PlanktonFlow : hands-on deep-learning classification of plankton images for biologists

  - **[Link](https://www.biorxiv.org/content/10.1101/2025.09.19.677346v1.full)**
  - **Objective**:
  - creating and end-to-end fully automated deep learning pipeline for biologists to use in plankton classification
  - **Methods**:
  - highly imbalanced datase --> used transformations (horizontal flipping, vertical flipping, 90-degree rotation, brightness and contrast adjustment, and hue/saturation modulation)
  - choose ResNet (He et al., 2016), DenseNet(Huang et al., 2018), EfficientNet (Tan and Le, 2020) and YOLOv11 (Khanam and Hussain, 2024) to compare against each other
  - all models initialized with ImageNet-pretrained weights
  - simple finde tuning was not enough as only mayjor classes profited
  - tried out different loss functions
  -  hyperparameter optimization
  - **Outcomes**:
  - the best overall performance was achieved by EfficientNet-B5, while both ResNet and DenseNet achieved comparable results within a 1-2% margin
  - **Relation to the Project**:
  - -we tried out ResNet and EfficientNet and also found that EfficientNet performed best

- **Source 3**: [Title of Source 3]

  - **[Link]()**
  - **Objective**:
  - **Methods**:
  - **Outcomes**:
  - **Relation to the Project**:

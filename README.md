# Wildlife Classification Project
Overview
This project involves building an object classification model to identify four wildlife species in Africa: buffalos, elephants, rhinos, and zebras. We leverage the VGG16 pretrained model, a deep convolutional neural network, to classify these animals.

Data Augmentation
Due to a limited number of training images, we use data augmentation techniques to increase the dataset size and reduce the risk of overfitting.

Model
Pretrained Model: VGG16, with weights from ImageNet, is used for this project. No additional trainable parameters are added to the pretrained model.
Testing and Evaluation
The model is evaluated using a test dataset, achieving an accuracy of 96%. Depending on the data quality, accuracy could potentially reach up to 98%.

Pipeline and Results
The pipeline, including data augmentation, model configuration, and evaluation, is detailed in the project documentation. Metrics and results demonstrate the model's effectiveness in wildlife classification.

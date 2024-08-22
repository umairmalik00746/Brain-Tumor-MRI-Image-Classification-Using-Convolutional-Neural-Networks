# Brain Tumor MRI Image Classification Using Convolutional Neural Networks
## Project Overview
### This is a project done as part of the MSc Data Science course at the University of Hertfordshire to classify brain tumors with MR images. In this project, the purpose is to create deep learning models that are capable of predicting MRI images that can be classified into four types: glioma, meningioma, pituitary tumors, and no tumor. We are using Convolutional Neural Networks (CNNs) in this project to improve the accuracy and time of brain tumor diagnosis.
## Motivation
#### Brain tumors are one of the most dangerous and deadly cancers, which can improved based on early diagnosis789. Very often, executing traditional procedures of recognizing brain tumors with the use of MRI could be slow and are not free from human error. In this project, we hope to mitigate these challenges by creating automatic deep-learning classification models, with the possibility of increasing diagnostic performance and automatizing radiologists' workflows.
## Dataset
### The number of images is 7023 MRI image data is classified into four classes:
### •	Glioma
### •	Meningioma
### •	Pituitary tumors
### •	No tumor
### This is a collection of three initial datasets Figshare, SARTAJ, and Br35H to provide adequate representation in brain MRI scans and was used for the creation of the dataset.
## Models Developed
### In this study, three models have been developed and assessed:
### 1.	Model 1: Custom CNN
### o	Architecture: A Light CNN with 32 filters in the first layer and 64 in the second, passed into fully connected layers.
### o	Performance: Tested on the dataset and scored 80.63% accuracy with a test loss of 0.97.
## 2.	Model 2: Advanced Custom CNN
### o	Architecture: A larger CNN having complex layers that detect more deep features from the input images.
### o	Performance: The performance of the model was tested at 77.04% and a loss of 0.72.
## 3.	Model 3: Pre-trained VGG-16 with Fine-Tuning
### o	Architecture: A VGG-16 model pre-trained on ImageNet, fine-tuned for the brain tumor classification task.
### o	Performance: Achieved the highest test accuracy of 89.47% and a test loss of 0.30, demonstrating superior feature extraction and generalization capabilities.
## Results
### •	Model 1 (Custom CNN): Test accuracy: 80.63%, Test loss: 0.97.
### •	Model 2 (Advanced Custom CNN): Test accuracy: 77.04%, Test loss: 0.72.
### •	Model 3 (VGG-16 Fine-Tuned): Test accuracy: 89.47%, Test loss: 0.30.
### We can see that the fine-tuned VGG-16 model gave the best results, being better than both other custom-built models which prove how convenient pre-trained architectures are to use for these complex images classification tasks.
## Future Work
### •	Data Augmentation and Expansion: Use some advanced augmentation techniques to train our model on a larger dataset, which can help make your model generalize better.
### •	Advanced Architectures: Experiment with more sophisticated architectures like ResNet or DenseNet to enhance feature extraction and classification performance.
### •	Hyperparameter Optimization: Utilize techniques such as Bayesian optimization or grid search to fine-tune model parameters for better performance.
## Acknowledgements
### This project was part of the MSc Data Science program at the University of Hertfordshire under the supervision of Khaas Wiersema Special thanks to the creators of these datasets and the open-source community who provided us with all tools and technologies that enabled this end-to-end project.


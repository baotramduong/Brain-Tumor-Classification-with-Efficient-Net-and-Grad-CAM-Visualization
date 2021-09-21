# Brain Tumor Classification with Efficient Net Convolutional Neural Network (CNNs) and Grad-CAM Visualization

## Blog

[Medium Blog](https://baotramduong.medium.com/explainable-ai-brain-tumor-classification-with-efficientnet-and-gradient-weighted-class-activation-24c57ae6175d)

## Introduction

In this project we will build and train an Efficient Net model and apply it to the Brain Tumor MRI Dataset to classify tumors: glioma_tumor, meningioma_tumor, pituitary_tumor, and no_tumor.

In addition, we will also use a technique known as Gradient-Weighted Class Activation Mapping (Grad-CAM) to visualize the regions of the inputs and help us explain how our CNN models think and make decision.

## Data Source

The data set which we are going to use has 3,285 images of brain MRI scans Which are categorized in four different classes namely glioma_tumor, meningioma_tumor, pituitary_tumor, and no_tumor. 

The dataset can be accessed on Kaggle Brain Tumor MRI Dataset or you can clone the dataset from  this [github repository](https://github.com/Ashish-Arya-CS/Coursera-Content).

## Exploratory Data Analysis

<img src = '../main/Data & Images/brain_mri.png' />

## Modeling

### Model Evaluation

<img src = '../main/Data & Images/acc_loss_curve.png' />

<img src = '../main/Data & Images/cm.png' />

<img src = '../main/Data & Images/classification_report.png' />

## Prediction

<img src = '../main/Data & Images/prediction.png' />

## Grad-CAM

### Glioma Tumor

<img src = '../main/Data & Images/glioma_tumor.png' />

### Meningioma Tumor

<img src = '../main/Data & Images/meningioma_tumor.png' />

### No Tumor

<img src = '../main/Data & Images/no_tumor.png' />

### Pituitary Tumor

<img src = '../main/Data & Images/pituitary_tumor.png' />

## Reference

Agarwal, V. (2020, May 23). Complete architectural details of all efficientnet models. Medium. Retrieved September 19, 2021, from https://towardsdatascience.com/complete-architectural-details-of-all-efficientnet-models-5fd5b736142.

Arya, A. (n.d.). Brain tumor classification using Keras [MOOC]. Coursera. https://www.coursera.org/projects/brain-tumor-classification-using-keras-jbek2?courseSlug=brain-tumor-classification-using-keras-jbek2&showOnboardingModal=check.

Kermany, D. S., Goldbaum, M., Cai, W., Valentim, C., Liang, H., Baxter, S. L., McKeown, A., Yang, G., Wu, X., Yan, F., Dong, J., Prasadha, M. K., Pei, J., Ting, M., Zhu, J., Li, C., Hewett, S., Dong, J., Ziyar, I., Shi, A., … Zhang, K. (2018). Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning. Cell, 172(5), 1122–1131.e9. https://doi.org/10.1016/j.cell.2018.02.010.

Quick brain tumor facts. National Brain Tumor Society. (2021, March 22). Retrieved September 20, 2021, from https://braintumor.org/brain-tumor-information/brain-tumor-facts/.

Siddhartha. (2019, June 5). CAM visualization OF EFFIECIENT. Machine Leaning Blog. Retrieved September 20, 2021, from https://sidml.github.io/efficientnet-gradcam-comparison-to-other-models/.

Tan, M.; Le, Q.. (2019). EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks. <i>Proceedings of the 36th International Conference on Machine Learning</i>, in <i>Proceedings of Machine Learning Research</i> 97:6105–6114 Available from https://proceedings.mlr.press/v97/tan19a.html.

Rosebrock, A. (2020, March 9). Grad-CAM: Visualize Class Activation Maps with Keras, TensorFlow, and Deep Learning. PyImageSearch. Retrieved September 10, 2021, from https://www.pyimagesearch.com/2020/03/09/grad-cam-visualize-class-activation-maps-with-keras-tensorflow-and-deep-learning/.


# CALTECH-101-Dataset-
The CALTECH-101 dataset is a dataset of 101 object categories with 40 to 800 images per class.  Most images have approximately 50 images per class.

* The goal of the dataset is to train a model capable of predicting the target class.

* Prior to the resurgence of neural networks and deep learning, the state-of-the-art accuracy on was only ~65%.

* However, by using Convolutional Neural Networks, it’s been possible to achieve 90%+ accuracy (as He et al. demonstrated in their 2014 paper, Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition).

-- Today we are going to implement a simple yet effective CNN that is capable of achieving 96%+ accuracy, on a 4-class subset of the dataset:

   * Faces: 436 images
   
   * Leopards: 201 images
   
   * Motorbikes: 799 images
   
   * Airplanes: 801 images

*  The reason we are using a subset of the dataset is so you can easily follow along with this example and train the network from scratch, even if you do not have a GPU.


^^TO download the dataset , use:
                  http://www.vision.caltech.edu/Image_Datasets/Caltech101/101_ObjectCategories.tar.gz
                  
                  *after downloading the dataset extract the dataset using zip extractor.

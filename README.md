# CIFAR-10_Classification
CIFAR-10 Classification using custom CNN
Dataset: CIFAR-19

Tech Stack:

Python

TensorFlow

Keras

Streamlit

Data Preprocessing:

Initial train dataset of 50000 images is split into a training set of 40000 images and a validation set of 10000 images in order to train the model.
Image augmentation applied on training set: width shift, shear shift,height shift, brightness shift, rotation, zoom, pixel intensity variation using channel_shift, fill_mode, pixel value normalization using rescale and cutout
Rescale applied on both the validation and test datasets for pixel normalization.
Input size is taken as 32x32 for all the images in a batch size of 32.

Workflow:

<img width="449" height="2132" alt="image" src="https://github.com/user-attachments/assets/0cb98a45-361c-404c-9c37-51913cb10dfa" />


Results:

Test Accuracy: 84.45%

Recall: 84.45%

Precision: 84.33%

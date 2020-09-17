# Covid Detection with XRay Images

Project summary: This project is a classification project on X-ray and CT images. This project is build to detect whether the patient is covid positive or not. A common Dataset has build by merging to datasets for this project . One dataset contains all types of Covid cases images (COVID-19, SARS, MARS, ARDS) and another dataset contains Non covid X-ray images (Normal, Pneumonia)

In this project I have only used 2 types of images.
1. Normal Cases
2. Covid Cases

- Dependencies:
	- Tensorflow 2.x
	- Keras 2.x
	- matplotlib
	- seaborn
	- numpy
	- pandas

- Class Activation Maps(CAM):
Class Activation Maps for a particular category indicates the discriminative region used by CNN to identify the category. CAM is one of the most popular visualization among CNN visualization. More about Class Activation Maps: https://towardsdatascience.com/demystifying-convolutional-neural-networks-using-class-activation-maps-fe94eda4cef1
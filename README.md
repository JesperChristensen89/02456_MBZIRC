# A Deep Learning Approach to classifying, locating and separating different sized wrenches for MBZIRC 2017
This repo represents the solution to our project in 02456 Deep Learning. 
The project has been carried out by team members:
* Bjarke Vad Pedersen
* Servet Coskun
* Jesper Haahr Christensen
## Data
Only the resized raw data is available at this repo due to size restrictions. For the work, the data has been further processed depended on the model worked on. E.g. augmentations, cropping, other sizes and sorting into folders representing the label.
Different pre-processing scripts are located under /preprocessing.

## Classification
Under /Keras_Classification is many of our classification models represented. This includes both buttom-up models and transfer learning models. 

## Object detection
Under /Tensorflow_object_detection is files and data used for object detection located. Not all files are present due to size limitation on github. This includes the saved models after finishing training and the TF .record files used for training.

## Final model
The final model is tested in the test_model notebook (under object detection), which has already been run for viewers purpose. It cannot be re-run at this location due to dependencies on TF API plus missing files.

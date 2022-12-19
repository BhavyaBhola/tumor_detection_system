# Tumor detection system

The following repository contains a easy to use Brain Tumor detection 
system where the user can just enter the image and the model will be able 
to tell whether the person has a tumor or not and also tells out of 3 types of tumor
which one it is if present. The types of brain tumor that the system can tell apart are-
glioma_tumor , meningioma_tumor , pituitary_tumor

## Installation

Install all the necessary libraries

```bash
  
  pip install opencv-contrib-python==4.6.0.66
  pip install scikit-learn==1.1.2
  pip install pandas==1.4.3
  pip install numpy==1.22.4
  pip install tensorflow==2.10.0

```

## Run Locally

Clone the project

```bash
  git clone repo link
```

Go to the project directory

```bash
  cd tumor_detection_system
```
check t_cv_mobilenet.ipynb for the source code of the model 



## Deployment

To use the model in any android or ios application use the .tflite file
present in the folder and incorporte it in your code. The model takes an image of 
size 224 x 224 x 3 
## Running Tests

To test the model you can use the code in the testing.ipynb and change the 
image accordingly in img variable the output will be a numpy array which is labeled 
in t_cv_mobilenet.ipynb you can use it can determine which label has the highest probablity.

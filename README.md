# Dog Breed Classifier
This project has been a part of my Udacity Data Science Nanodegree. You can read the write up of this project on Medium https://medium.com/@henrydashwood/a-dog-detector-and-breed-classifier-4feb99e1f852

# Motivation
The model in this repo takes an image and determines whether a human or dog is present. It then makes a prediction about what breed the dog is or what dog breed the human most resembles.

# Files
bottleneck_features - A folder for pretrained models which can be downloaded from link in notebook

dog_app.ipynb - A jupyter notebook in which the code can be found

extract_bottleneck_features.py - Some functions to process the pretrained models

haarcascades - A folder containing the filters we will use in the human face detector

images - A folder to place any images on which you would like to test the model

README.md - This ReadMe

requirements - A folder containing the necessary dependencies

saved_models - A folder in which to save any models you train

# Results

**Dog Detector Sample Performance**

|     | True | Predicted |
| --- | ---  |    ---    |
|Human| 100  |    100    |
| Dog |  0   |    11     |

**Human Detector Sample Performance**

|     | True | Predicted |
| --- | ---  |    ---    |
|Human| 100  |    100    |
| Dog |  0   |    11     |

**Breed Predictor Test Performance**

From scratch: 3.7%

With transfer learning: 84%

# Libraries
These libraries are listed in requirements.txt

```
opencv-python==3.2.0.6
h5py==2.6.0
matplotlib==2.0.0
numpy==1.12.0
scipy==0.18.1
tqdm==4.11.2
keras==2.0.2
scikit-learn==0.18.1
pillow==4.0.0
ipykernel==4.6.1
tensorflow==1.0.0
```

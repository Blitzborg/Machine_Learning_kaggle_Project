# Recognizing Faces in the Wild
This project is a part of the Machine Learning course in Nanyang Technological University. The Kaggle Competition chosen for the project can be found [here](https://www.kaggle.com/c/recognizing-faces-in-the-wild) 

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is was to determine whether two people are blood-related or not on the sole basis of facial images by designing a complex deep learning model. The data used for training and testing is provided by an image database called families in the wild. 

### Competition Organizers
* [Northeastern SMILE Lab](https://web.northeastern.edu/smilelab/)

## Submission Score 
Top 4% solution (18/528) on the public leaderboard

### Contributing Members
- [Pereddy Vijai Krishna Reddy](https://github.com/pvijaikr)
- [Atluri Sai Mona](https://github.com/alturisaimona)
- [Pinnepu Jaswanth](https://github.com/jaswanth001)

## Project Description
The proposed solution is a classifier using a VGGFace baseline CNN model in Keras with modified architecture to determine if two people are blood-related based solely on images of their faces. 

### Methods Used
* Deep Learning 
* Image Recognition
* Transfer Learning 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites

What things you need to install the software and how to install them

```

numpy
os
cv2
keras
keras_vggface
tensorflow
zipfile
tqdm
h5py
glob


```

# Usage : 
Install the above mentioned prequisites in an Integrated development environment that supports '.ipynb' files. Load the Model.ipynb file. Load the datasets from [here](https://www.kaggle.com/c/recognizing-faces-in-the-wild/data). Modify the directory path if required.
To obtain the same kaggle score as us, follow the following steps:
1. Change the Validation set families (val_families, Cell No: 5) from {F00, F01, F02, F03, F04, F05, F06, F07, F08, F09} after every run.
2. Uncomment the curmodel.load_weights() (Cell No: 9) after the first run.
3. Repeats steps 1 and 2 after changing the parameter 'monitor' of EarlyStopping from 'val_loss' to 'val_acc' and 'mode' from 'min' to 'max'.
4. After generating 20 models, uncomment the last Cell and run it. The CSVFinal.csv generated is the output file.


### Refernces :
[keras_vggface model](https://github.com/rcmalli/keras-vggface)

The following discussion threads were useful:
- https://www.kaggle.com/c/recognizing-faces-in-the-wild/discussion/103670
- https://www.kaggle.com/c/recognizing-faces-in-the-wild/discussion/104288

[The Reference Code](https://www.kaggle.com/mattemilio/smile-best-who-smile-last)

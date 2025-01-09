
### Exercise Gamification Artificial Intelligence Applications Course Project


## Description

 Developed a machine learning model to classify exercises from video data using LSTM architecture
 Processed and analyzed the Fit3D Video Dataset containing 245 videos across 7 exercise classes
Implemented video preprocessing and feature extraction using OpenCV and NumPy
 Built and trained the model using TensorFlow, achieving 87% classication accuracy
 Handled video sequences of 75 frames per video, with input resolution of 128x128 pixels


## Requirements
  - Python 3.9
  - Tensorow,numpy,Keras,OpenCV

## Dataset Installation
  ### Dataset Link: https://drive.google.com/drive/folders/13Y2X9EmLNipJtiN519jJLoIJhP_nszbg?usp=share_link
  - Please download  a folder named 'dataset' inside datasets and place it in the project directory.
	-model.h5 is in drive as well.

## Required Libraries
    - Create a virtual environment:
	```python3 -m venv venv```

	- Activate the virtual environment:
	```.\venv\Scripts\activate``` for Windows
	```source venv/bin/activate``` for MacOS and Linux

	- Install the required packages:
	```pip install -r requirements.txt```




# Project Details
## Dataset
  - Dataset: Fit3D Video Dataset
  - Number of Exercises (Classes): 7
  - Number of Videos each Class Containing: 35
  - Number of Total Videos: 245

## Model
  - Model Type: LSTM
  - Model Video Sequence Count: 75 Frames per Video
  - Trained Model Video Resolution: 128 x 128
  - Accuracy: %87

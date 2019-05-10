# Introduction
In this notebook, you will build a deep neural network that functions as part of an end-to-end machine translation pipeline. Your completed pipeline will accept English text as input and return the French translation.

# Setup

This project requires GPU acceleration to run efficiently. Support is available to use either of the following two methods for accessing GPU-enabled cloud computing resources.


## Amazon Web Services

Please refer to the Udacity instructions for setting up a GPU instance for this project, and refer to the project instructions in the classroom for setup. The recommended AMI should include compatible versions of all required software and libraries to complete the project. [link for AIND students](https://classroom.udacity.com/nanodegrees/nd889/parts/16cf5df5-73f0-4afa-93a9-de5974257236/modules/53b2a19e-4e29-4ae7-aaf2-33d195dbdeba/lessons/2df3b94c-4f09-476a-8397-e8841b147f84/project)

## Install
- Python 3
- NumPy
- TensorFlow 1.x
- Keras 2.x

"""
Clone the repository, and navigate to the downloaded folder.

git clone https://github.com/udacity/aind2-nlp-capstone

cd aind2-nlp-capstone

Create (and activate) a new environment with Python 3.5 and the numpy package.

conda create --name aind-nlp-capstone python=3.5 numpy
source activate aind-nlp-capstone
Install/Update TensorFlow.

pip install tensorflow==1.1 -U
Install/Update Keras.

pip install keras -U
Switch Keras backend to TensorFlow.

KERAS_BACKEND=tensorflow python -c "from keras import backend"
Start Jupyter: jupyter notebook --no-browser

Look at the output in the window, and find the line that looks like the following:
Copy/paste this URL into your browser when you connect for the first time to login with a token: 
http://0.0.0.0:8888/?token=3156e...
Copy and paste the complete URL into the address bar of a web browser (Firefox, Safari, Chrome, etc). Press Enter.

Click on machine_translation.ipynb. Follow the instructions in the notebook.

"""""""
Submission

# Submission
When you are ready to submit your project, do the following steps:
1. Ensure you pass all points on the [rubric](https://review.udacity.com/#!/rubrics/1004/view).
2. Submit the following in a zip file:
  - `helper.py`
  - `machine_translation.ipynb`
  - `machine_translation.html`

## Converting to HTML

There are several ways to generate an HTML copy of the notebook:

 - Running the last cell of the notebook will export an HTML copy

 - Navigating to **File -> Download as -> HTML (.html)** within the notebook

 - Using `nbconvert` from the command line

    $ pip install nbconvert
    $ nbconvert machine_translation.ipynb

# Ovenbird Call Recognizer Usage Readme

This recognizer was developed using the Tensorflow package in python by Chris Small and Elly Knight.  The recognizer output is a sigmoidal score for Ovenbird presence and the maximum decibel level for each ~2.75 second detection window of a recording.

## Running the model
Recordings must be run through the Ovenbird detection model by using a python environment, either locally or via Google Colab.  The notebook and models on this git can be downloaded to a local machine in order to run via Jupyter Notebooks, or to Google Drive where they can be run in the Google Colab environment.

### Running notebook Locally
If you wish to run the model on your local machine you can download all three parts of the model ('oven-model-22022017.index', 'oven-model-22022017.meta', and 'oven-model-22022017.data-00000-of-00001') and the notebook ('OVEN-22022017.ipynb') to your local drive and run the notebook as a Jupyter notebook in a local python environment of your choice.  You'll need to have the model files and notebook all in the same parent file for the code to find the model, though the recordings can be located elsewhere on your machine, the directory will be defined in the notebook.

### Google Colab 
If you want to run the model using Google Colab rather than a python environment on your own computer then you can open the notebook directly in Colab from the Github repository or using the URL of the notebook in the 



you can download the model ('oven-model-22022017.index', 'oven-model-22022017.meta', and 'oven-model-22022017.data-00000-of-00001') files and notebook ('OVEN-22022017.ipynb') to your Google Drive and run it as a Colab Notebook.  You'll need to save your model and script in the same 

every ~2.75 seconds

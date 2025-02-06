# Dog Breed Classification

This application predicts the breed of a dog based on an uploaded image using a trained deep learning model.

## Features

- Predicts dog breeds from images.
- Easy-to-use interface powered by **Streamlit**.
- Currently supports three dog breeds:
  - Scottish Deerhound
  - Maltese Dog
  - Bernese Mountain Dog

## Installation Guide

### Step 1: Setting Up Your Environment
1. Make sure you have **Anaconda** installed. 
2. Open the **Anaconda Prompt**.

### Step 2: Installing Dependencies
Navigate to the project directory in your terminal:
cd "your_working_directory"

### Step 3: Generate the requirements.txt file
pipreqs

### Step 4: Install streamlit
pip install streamlit

### Step 5: Running the application
streamlit run main_app.py

## File Descriptions
1. main_app.py: The main application script that runs the Streamlit interface and loads the model.
2. dog_breed.h5: Pre-trained deep learning model used for predictions.
3. requirements.txt: File containing the required Python packages.
4. kaggle.json: Kaggle API credentials for downloading datasets (if applicable).
5. Dog_Breed_Prediction.ipynb: Jupyter notebook containing the training code and analysis.
6. test_image_1.png: Sample image for testing the application.

## Notes
1. Ensure the dog_breed.h5 model file is in the same directory as main_app.py.
2. Supported image format for uploads: .png.
3. If you encounter any issues, verify your Python and library versions match those in requirements.txt.

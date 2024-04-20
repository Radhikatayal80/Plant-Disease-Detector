# Plant Disease Detection System

This repository contains code for a Plant Disease Detection System. The system is built using a trained model to identify plant diseases. Follow the instructions below to set up and run the code on your local machine.

## Download the Model

1. Download the `model.h5` file from the following link: [Download model.h5](https://drive.google.com/file/d/1zh9hOME2bmThyUtBD0vpvbSjPlH0TsaC/view?usp=drive_link)
2. Place the `model.h5` file into the `Plant-Disease-Detection-main-Streamlit` folder.

## Setting Up the Environment

### Step 1: Install Anaconda and Open Anaconda Prompt as Administrator

Download Anaconda from [here](https://www.anaconda.com/products/distribution).

Right-click on the Anaconda Prompt and select "Run as administrator".

### Step 2: Create a Virtual Environment

Use the following command to create a virtual environment:
```bash
conda create -n env_name
```
Replace `env_name` with the desired name of your environment.

### Step 3: Activate the Environment

Use the following command to activate the virtual environment:
```bash
conda activate env_name
```
Replace `env_name` with the name of your environment.

### Step 4: Navigate to the File Location

Use the following command to navigate to the location where you have cloned or downloaded this repository:
```bash
cd file_location
```
Replace `file_location` with the path to the location of the downloaded repository.

### Step 5: Install Requirements

Use the following command to install the necessary requirements:
```bash
pip install -r requirements.txt
```

### Step 6: Run the Code

Use the following command to run the code:
```bash
streamlit run app.py
```

The application should now be running locally on your machine.



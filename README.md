# Radiology Assistant - Chest X-ray Classification with Convolutional Neural Networks (CNN)

⚠️ ***Disclaimer:*** This application is a student project created for educational purposes. It is not FDA-approved and should not be used for medical diagnosis or treatment.

## Project Overview
This project implements a Convolutional Neural Network (CNN) model to classify chest X-ray images as either Normal or Abnormal. The application is designed to assist radiologists by automating preliminary assessments, improving workflow efficiency, and supporting diagnostic decisions.

The project was developed in both PyCharm (local Jupyter environment) and Google Colab (cloud-based) to provide maximum flexibility for execution, testing, and demonstration.

I have included my final write-up on the project. The objective of which was to go through as if proposing the system to a company and following the project descriptions through to completion.
## Requirements

Colab Notebook:  
- Requires Google Account
- All dependencies install automatically via notebook cells

Local Execution:  
- Python 3.10  
- Install required libraries:  
`pip install tensorflow pandas matplotlib seaborn opencv-python scikit-learn`

## Getting Started  
- Google Colab (Chest_Xray_Prediction.ipynb)


Use this for demonstrating model predictions without needing to train a model from scratch

1. Open the Colab notebook here: [🔗 Chest_Xray_Prediction.ipynb (Google Colab)](https://colab.research.google.com/drive/1Y8xJwmfZpLytTJrVoGGl_VgwKCnZXF7z?usp=sharing)
2. When prompted, upload:
   - The model file: `cnn_xray_model.h5`
   - A sample chest X-ray image (e.g., `sample_image.png`)
3. The notebook will:
   - Load the image
   - Predict if it is **Normal** or **Abnormal**
   - Display the image and probability score

- Local Execution (PyCharm_Model_Training)

Use this to train, evaluate, and test the model from start to finish.

    Open PyCharm_Model_Training.ipynb in Jupyter Notebook (PyCharm or another IDE).

    Place the NIH Chest X-ray dataset in the correct path (instructions inside the notebook).

    Run all cells to:

        Preprocess the dataset

        Train and evaluate the CNN

        Save the trained model

        Test predictions using predict_new_image()

## Features

- Image preprocessing (rescaling, grayscale, normalization)

- CNN architecture optimized for medical imaging

- Interactive prediction with confidence scores

- Compatible with both cloud and local environments

## Security & Compliance

- Uses de-identified NIH Chest X-ray dataset (HIPAA-compliant)

- No personal health information (PHI) is stored or processed

- All image handling is local or session-based

## Dataset
The dataset that was used can be found at NIH Chest X-ray Dataset: https://www.kaggle.com/datasets/nih-chest-xrays/data

## Author

Bradley Pfahl, BS RT(R)(MR)
Radiologic Technologist | Computer Science Capstone Student
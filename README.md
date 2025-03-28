# DeepLearning_StrawberryClassification

## Overview
DeepLearning_StrawberryClassification is a deep learning project that utilizes a fine-tuned ResNet50 model to accurately classify images as either "strawberry" or "non-strawberry." The project integrates robust data augmentation techniques and provides comprehensive evaluation metrics. An interactive Gradio interface is included to allow for real-time image predictions.

## Features
- **Pre-trained Model:**  
  Uses a fine-tuned ResNet50 architecture with additional custom dense layers for improved classification performance.
- **Data Augmentation:**  
  Incorporates random cropping, rotation, contrast adjustment, and brightness modifications to enhance model generalization.
- **Comprehensive Evaluation:**  
  Offers detailed performance metrics including accuracy, F1 score, precision, recall, and a full classification report.
- **Interactive Prediction Interface:**  
  Features a Gradio-powered web interface for uploading images and viewing predictions in real time.
- **Modular Design:**  
  Code is organized in a Jupyter Notebook (`StrawberryClassification.ipynb`) for ease of experimentation and reproducibility.

## Repository Structure
DeepLearning_StrawberryClassification/ ├── StrawberryClassification.ipynb # Jupyter Notebook containing the complete project code ├── README.md # Project documentation ├── requirements.txt # Python dependencies required for the project └── data/ # (Optional) Folder to store dataset if downloaded locally

## Installation
### Prerequisites
- **Python:** Version 3.6 or higher is recommended.
- **Git:** To clone the repository.

### Steps
1. **Clone the Repository:**

   git clone https://github.com/xangelcoded/DeepLearning_StrawberryClassification.git
   cd DeepLearning_StrawberryClassification
Install Dependencies: Install all required packages using pip:


pip install -r requirements.txt
Usage
Running the Notebook
Open StrawberryClassification.ipynb in Jupyter Notebook or JupyterLab.

Execute the cells sequentially to:

Download and preprocess the dataset.

Build, train, and evaluate the model.

Launch the Gradio interface for real-time predictions.

Using the Gradio Interface
Once the notebook is executed, a Gradio web interface will launch.

Use the interface to upload images and instantly view the model's predictions along with confidence scores.

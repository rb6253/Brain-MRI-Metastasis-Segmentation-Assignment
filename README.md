Brain MRI Metastasis Segmentation
Overview
This repository contains the implementation of a deep learning project focused on brain MRI metastasis segmentation using Nested U-Net and Attention U-Net architectures. The primary objective is to accurately detect and segment metastatic lesions in brain MRI scans, enhancing diagnostic capabilities in medical imaging.

Features
Model Implementations:
Nested U-Net (U-Net++)
Attention U-Net
Data Preprocessing:
CLAHE (Contrast Limited Adaptive Histogram Equalization) for image enhancement
Normalization and augmentation techniques for robust training
Evaluation Metrics:
DICE Score for assessing segmentation accuracy
Web Application:
Built with FastAPI for backend services
Streamlit UI for user-friendly image upload and visualization of segmentation results
Dataset
The project utilizes a Brain MRI dataset containing images and corresponding segmentation masks, which can be downloaded here. The dataset is split into 80% training and 20% testing sets for model training and evaluation.

Installation
To run this project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/brain-mri-segmentation.git
Navigate to the project directory:

bash
Copy code
cd brain-mri-segmentation
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Start the FastAPI backend:

bash
Copy code
uvicorn app:app --reload
Run the Streamlit UI:

bash
Copy code
streamlit run ui.py
Upload a brain MRI image through the Streamlit interface to see the segmentation results.

Documentation
Refer to the README.md file for detailed instructions on setting up and running the project, explanations of the model architectures, challenges encountered, and the clinical implications of accurate brain metastasis segmentation.

Results
The models' performance is evaluated based on DICE scores, with comparative analysis included in the documentation. The best performing model is showcased through the web application for real-time predictions.

Contributions
Contributions are welcome! Please feel free to submit a pull request or raise an issue for any suggestions or improvements.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

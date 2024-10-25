# BreatheAI - **AI in Medical Imaging: Classifying Respiratory Diseases from X-Rays** 🤖💡

Welcome to **BreatheAI**! This project is designed to assist healthcare professionals and patients by leveraging AI to classify various respiratory diseases from chest X-rays. With cutting-edge machine learning models, BreatheAI can help detect and differentiate conditions like **Viral Pneumonia**, **Bacterial Pneumonia**, **Tuberculosis**, **Viral Pneumonia**,**Lung Opacity**,**COVID-19**  and potentially more. Our aim is to provide **accurate, interpretable results** that support quicker and more effective diagnoses.

---

## Table of Contents 📚

- [Key Features](#key-features-🚀)
- [How It Works](#how-it-works-🔍)
- [Visual Workflow](#visual-workflow-🖼️)
- [Example Output](#example-output-📊)
- [Future Work](#future-work-🚀)

---

## Key Features 🚀

- **Multiclass Classification**: Detects and classifies multiple respiratory diseases, including **Viral Pneumonia**, **Bacterial Pneumonia**, **Tuberculosis**, **Viral Pneumonia**,**Lung Opacity**,**COVID-19** .
- **Role-Based Results**: Tailored results for both doctors (detailed) and patients (simplified).
- **Grad-CAM Heatmaps**: Provides interpretability for doctors by highlighting critical areas in X-rays.
- **User-Friendly Interface**: Simple upload system for easy interaction and quick results.

---

## How It Works 🔍

The **BreatheAI** process is designed to be intuitive and quick! Here's what happens step-by-step:

| Step | Description | Image |
|------|-------------|-------|
| 1.   | **Image Upload**: A user uploads a chest X-ray image. | ![Upload Image](https://github.com/fatma2123456/BreatheAI-Website/blob/main/images/website_20241025_184029_0000.png) |
| 2.   | **AI-Powered Analysis**: The model analyzes the image and classifies the detected disease (Viral Pneumonia, Bacterial Pneumonia, Tuberculosis, Viral Pneumonia,Lung Opacity,COVID-19). | ![AI Analysis](https://github.com/fatma2123456/BreatheAI-Website/blob/main/images/website3_20241025_184058_0000.png) |



## Role-Based Results
The output from **BreatheAI** is designed with both doctors and patients in mind.

| Role     | Results Description                                       | Image                         |
|----------|----------------------------------------------------------|-------------------------------|
| **Doctor** |  -Detailed classification.<br> -Grad-CAM heatmap visualization.<br> -That visually highlights important regions of the X-ray. | ![Doctor Results](https://github.com/fatma2123456/BreatheAI-Website/blob/main/images/gradcam_20241025_184120_0000.png) | 
| **Patient** |  -Simplified classification.<br> -Basic disease information.<br>-The detected disease is presented  | ![Patient Results](https://github.com/fatma2123456/BreatheAI-Website/blob/main/images/patient_20241025_184127_0000.png) | 

---


## Visual Workflow 🖼️

Here's a quick overview of how **BreatheAI** works from start to finish:


1. **Upload X-ray Image**: Users start by uploading a chest X-ray image.
2. **Model Classification**: The AI model analyzes the image and classifies any detected respiratory diseases.
3. **Grad-CAM**: If the user is a doctor, the system generates a heatmap to highlight the key regions of the X-ray that informed the AI's decision.
4. **Results Based on Role**:
   - **Doctor**: Detailed classification with heatmap.
   - **Patient**: Simplified classification with next steps.
     
----
## View the Model Build with VGG19 🛠️

If you're interested in the model build and architecture used in **BreatheAI**, particularly the **VGG19** model, please check out the following resources:

- **VGG19 Model**: The VGG19 architecture is implemented in our project for the effective classification of respiratory diseases from chest X-rays.
- **Model Code**: You can find the VGG19 implementation in `model.py`. This file contains the architecture and the necessary code to train the model.
- **Repository**: For more information, visit our GitHub repository: [CLASSIFYING RESPIRATORY DISEASES FROM X-RAYS](https://github.com/fatma2123456/CLASSIFYING-RESPIRATORY-DISEASES-FROM-X-RAYS).

Feel free to explore the code, and let us know if you have any questions or feedback! Your insights are invaluable to us. 🙏


---
## Future Work 🚀

We have exciting plans for **BreatheAI** to enhance its capabilities and user experience:

1. **Pre-Trained Models for Chest X-Rays**:
   - We aim to add models like **CheXNet** to analyze chest X-rays more effectively and improve respiratory disease detection.

2. **Medical Chatbot**:
   - A chatbot will be integrated to provide health tips and help patients manage symptoms while they await a doctor's diagnosis.

3. **User Accounts**:
   - We'll introduce accounts for patients, doctors, and organizations, allowing personalized services and doctor recommendations.

Stay tuned for these exciting new features! 🙌

---

## Setup and Installation 🛠️

To get **BreatheAI** running on your machine, follow these steps:

### Requirements:

- Python 
- Flask
- TensorFlow/Keras
- OpenCV
- Dependencies listed in <a href="https://github.com/fatma2123456/BreatheAI-Website/blob/main/requirements.txt">requirements.txt</a>


### Installation Instructions:

Let’s get the magic started!✨

```bush
1. Clone the Repository
git clone https://github.com/yourusername/BreatheAI.git
cd BreatheAI

2. Install the Required Dependencies
pip install -r requirements.txt

3. Run the Flask Application
flask run

4. Access the Web Interface
http://127.0.0.1:5000

---

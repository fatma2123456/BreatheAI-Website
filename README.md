# BreatheAI - **AI in Medical Imaging: Classifying Respiratory Diseases from X-Rays** 🤖💡

Welcome to **BreatheAI**! This project is designed to assist healthcare professionals and patients by leveraging AI to classify various respiratory diseases from chest X-rays. With cutting-edge machine learning models, BreatheAI can help detect and differentiate conditions like **Viral Pneumonia**, **Bacterial Pneumonia**, **Tuberculosis**, **Viral Pneumonia**,**Lung Opacity**,**COVID-19**  and potentially more. Our aim is to provide **accurate, interpretable results** that support quicker and more effective diagnoses.

---

## Table of Contents 📚

- [Key Features](#key-features-🚀)
- [How It Works](#how-it-works-🔍)
- [Visual Workflow](#visual-workflow-🖼️)
- [Project Structure](#project-structure-🏗️)
- [Example Output](#example-output-📊)
- [Future Work](#future-work-🚀)
- [License](#license-📄)

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

```pyhon
1. Clone the Repository
git clone https://github.com/yourusername/BreatheAI.git
cd BreatheAI

2. Install the Required Dependencies
pip install -r requirements.txt

3. Run the Flask Application
flask run

4. Access the Web Interface
http://127.0.0.1:5000

----

## Project Structure 🏗️

Here's a breakdown of the project structure:

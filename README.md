# Real-Time Object Detection Mobile Application

This project is a mobile application that performs real-time object detection using the device's camera. The app is built using TensorFlow Lite and is optimized for running on Android devices. 
It detects and localizes objects within the camera feed, providing a smooth and efficient user experience.

# Features

* **Real-Time Object Detection:** Detects objects in real time using the device's camera.
  
* **On-Device Inference:** Runs entirely on the mobile device without the need for cloud processing.

* **Optimized for Mobile:** Utilizes TensorFlow Lite for efficient, low-latency object detection.

* **User-Friendly Interface:** Simple and intuitive UI for displaying detected objects.

# Getting Started

## Prerequisites

* Android Studio installed on your machine.

* Android device (or emulator) running Android 13.0 (Tiramisu) or higher.

* Basic knowledge of Android development and machine learning.

## Intstallation

1. Clone the Repository

```
git clone https://github.com/Quiirky-codes/Object-Detection-Application.git
cd object-detection-app
```

2. Open the Project in Android Studio
   
    * Launch Android Studio and select "Open an existing project."
    
    * Navigate to the cloned repository and open the project.

3. Build the Project
   
     * Sync the project with Gradle files.
   
     * Build the project to ensure all dependencies are installed.

5. Run the Application
   
     * Connect your Android device or start an emulator.
   
     * Click on the "Run" button in Android Studio to install and launch the app on your device.

# Model

The TensorFlow Lite model (detect.tflite) used in this application is located in the app/src/main/assets directory. 
The model was trained using TensorFlow and then converted to TensorFlow Lite for mobile deployment.

# Usage

* **Object Detection:** Launch the app, and it will start detecting objects in real time using the device's camera. Detected objects will be highlighted with bounding boxes and labeled accordingly.

* **Settings:** Customize detection settings, such as the minimum confidence threshold, through the app's settings menu.

# Methodology

1. **Data Collection & Preparation:** Images were collected and annotated with bounding boxes for the objects of interest.

2. **Model Training:** The model was trained using TensorFlow, leveraging a pre-trained SSD MobileNet model.

3. **Model Conversion:** The trained model was converted to TensorFlow Lite format (.tflite) for deployment on mobile devices.

4. **App Development:** The mobile application was developed using Android Studio, with the integration of TensorFlow Lite for real-time object detection.

# Results

The application successfully detects and localizes multiple objects in real time with minimal latency. 
It has been tested on various Android devices and performs efficiently across different environments.

![WhatsApp Image 2024-08-26 at 23 09 26_1ea975ad](https://github.com/user-attachments/assets/6d47fa23-53cf-4f63-bb04-35666dde4dd9)


![WhatsApp Image 2024-08-26 at 23 13 19_93599ec3](https://github.com/user-attachments/assets/a6613c68-baec-463f-a99d-e9724cc95997)



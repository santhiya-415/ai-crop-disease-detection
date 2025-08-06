 AI-Driven Crop Disease Detection and Alert System

This project uses an **ESP32-CAM**, **Deep Learning (TResNet)**, and **Twilio SMS API** to detect rice crop diseases from leaf images and send pesticide suggestions via SMS to farmers.

 Technologies Used
 
  ESP32-CAM (C++)
  Python, Flask, TensorFlow, OpenCV
  Google Colab (model deployment)
  Ngrok (secure image upload)
  Twilio API (SMS alerts)

 How It Works
1. ESP32-CAM captures leaf image
2. Sends it to Flask server via Ngrok
3. Deep Learning model (TResNet) classifies image
4. If disease is detected → SMS alert sent to farmer



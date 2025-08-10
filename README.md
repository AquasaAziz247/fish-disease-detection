# Fish Disease Detection & Treatment
## 📌 Overview
This project detects diseased fish from underwater images or videos using a **CNN classifier**.  
Healthy and diseased fish are classified into two categories for quick intervention.

---

## 🛠️ Tech Stack
- Python, OpenCV
- TensorFlow / Keras (CNN Model)
- Google Colab
- Raspberry Pi (for deployment)

---

## 📂 Dataset
- Custom dataset with **healthy** and **diseased** fish images.
- Labeled using **Roboflow** / **LabelImg**.

---

## 🚀 Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fish-disease-detection.git
   cd fish-disease-detection
2.Open Fish_Disease_Detection.ipynb in Google Colab.

3.Install dependencies:

````python
!pip install tensorflow opencv-python
````

4.Train the model:

````python
model.fit(train_data, epochs=20, validation_data=val_data)
````

5.Run inference:

````python
model.predict(test_image)
````

##📸 Example Results
Healthy Fish → ✅

Diseased Fish → 🚨 Alert for treatment

##🤖 Deployment
Model can be deployed on Raspberry Pi to monitor aquaculture tanks in real-time.

## 📊 Results
- Test Accuracy: **XX%**
- Example Predictions:
  ![Prediction Example](example.png)

## 📜 License
MIT License
   

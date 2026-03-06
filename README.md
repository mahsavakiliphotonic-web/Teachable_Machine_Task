
# 🤖 My Personal AI Object Detector

### 🌟 Project Overview

I used Teachable Machine to train a custom image classification model. The goal of this project was to teach a computer to distinguish between 4 objects like scissors, bottles, paper and empty option using real-time webcam data.

### 🚀 Try It Live!

You can test this model yourself using your own webcam. No setup required:
👉 [Click Here to Launch Model](https://teachablemachine.withgoogle.com/models/6gm-QzRHF/)

### 📸 Proof of Concept

Below is a visual representation of the AI identifying objects with high confidence:

| Scissors | Bottle | Paper | Empty |
| :---: | :---: | :---: | :---: |
| <img src="<img width="122" height="248" alt="image" src="https://github.com/user-attachments/assets/fa39046e-a1ab-4f78-a674-f8129aed2537" />" height="250"> | <img src="آدرس_عکس_بطری" height="250"> | <img src="آدرس_عکس_کاغذ" height="250"> | <img src="آدرس_عکس_خالی" height="250"> |

<img width="122" height="248" alt="image" src="https://github.com/user-attachments/assets/fa39046e-a1ab-4f78-a674-f8129aed2537" />
<img width="112" height="238" alt="image" src="https://github.com/user-attachments/assets/d8f96efa-c059-4cb4-baab-05ff7a8fee8f" />
<img width="112" height="238" alt="image" src="https://github.com/user-attachments/assets/80ea7c6f-c9af-4fac-bb7f-4a340b8dc5b0" />
<img width="155" height="270" alt="image" src="https://github.com/user-attachments/assets/1ea8042d-5734-444e-a271-cde261e8da0a" />

### 🧠 How it Works

Images were collected using a webcam. During the data collection process, the lighting and place conditions were intentionally varied to make the dataset more diverse and improve the model’s ability to recognize objects in different environments.

**Scissors**: When I showed the scissors to the webcam, the AI model identified it with high confidence

**Bottle**: Identifies when a bottle is shown to the camera.

**Empty**: Identifies when I cover the camera with cloth.

**Paper**: When I placed the paper in front of the webcam, the model classified it accurately


### 🛠️ Tools Used

**Teachable Machine** - Utilized for gathering webcam data, providing labels, and training the classification model.

**GitHub** - I used GitHub to store my files and share the project with others

**TensorFlow.js** - The framework that allows this model to run directly in your browser.

### 📝 Reflection

**1. Why this project is Supervised Learning?**
This project is an example of Supervised Learning because I provided the model with labeled training data. I created the classes myself and assigned names to each category (for example: Scissors, Paper, Bottle, Empty). The AI learned by matching the visual patterns in the images to the labels I gave it. Without my labels, the model would not know what each object represents.

**2.What happens if I hold two objects at once?**
When I hold two objects at the same time, the model becomes confused. It usually picks only one of the objects, even if both are visible. This happens because the model was trained to classify one object per image, not multiple objects at once. Since it cannot output two labels, it chooses the one that looks most similar to the training examples. This shows a limitation of simple image‑classification models.

<img width="766" height="388" alt="image" src="https://github.com/user-attachments/assets/f0fe20be-7507-4202-b26b-a49b0366db19" />


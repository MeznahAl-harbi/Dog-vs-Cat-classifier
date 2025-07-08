
# 🧠 Image Classifier – Dog vs Cat (Teachable Machine)

This is a simple image classification project using a model trained with [Teachable Machine by Google](https://teachablemachine.withgoogle.com/).  
The model can distinguish between two classes: **Dog** 🐶 and **Cat** 🐱.

---

## ✅ Project Steps

1. Collected and uploaded image data:
   - 50 images of dogs
   - 45 images of cats
2. Trained a model using Teachable Machine (Image Project - Standard).
3. Exported the model in **TensorFlow → Keras** format.
4. Wrote a Python script to:
   - Load the model
   - Accept an image input
   - Predict the image class
5. Ran predictions and saved the results.

---

## 🗂️ Project Files

- `predict_image.py` → Python script to make predictions.
- `keras_model.h5` → Trained model file.
- `labels.txt` → List of class labels (Dog, Cat).
- `test_images/` → Folder containing test images.
- `screenshot.png` → Output example screenshot.
- `README.md` ← (this file 😊)

---
## 🧪 How to Run

To test the model on any image, provide the image file path as an argument when running the script:

```bash
python predict_image.py <path_to_image>

Example:
python predict_image.py test_images/dog1.jpeg


## 🔍 Sample Output

![Screenshot 1](screenshot1.png)
![Screenshot 2](screenshot2.png)

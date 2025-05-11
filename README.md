# 🌿 Crop Health Monitoring

##🎯 Objective
Crop Health Monitoring leverages computer vision and deep learning to automate the detection of crop diseases from leaf images. This project supports early diagnosis, improving agricultural productivity and reducing the need for manual inspection.

##🧬 How It Works
Image Validation: Ensures uploaded images are valid leaf samples.

Preprocessing: Applies resizing, normalization, and data augmentation.

Model Prediction: A trained deep learning model classifies the crop as healthy or diseased.

Output Display:

Predicted class (e.g., Healthy, Rust, Scab)

Model accuracy and loss plots

Confusion matrix and classification report

##🔬 Model Insights
CNN Architecture: Used to extract spatial patterns in leaf textures.

Training Details:

Dataset: Leaf images (custom or sourced)

Optimizer: Adam

Loss: Categorical Crossentropy

Evaluation:

Accuracy, precision, recall, and F1-score

Real-time inference using uploaded images

##🛠️ Tech Stack
Python

TensorFlow / Keras

OpenCV

scikit-learn

Matplotlib & Seaborn

##📁 Project Structure
Final_model1.ipynb: Model training and evaluation notebook

final_model1.py: Script for prediction using trained model

##📈 Output Examples
Accuracy vs. Epoch graph

Loss vs. Epoch graph

Sample image predictions with class labels

##🌐 Use Cases
Smart Farming: Early detection of crop diseases in the field.

Agricultural Support: Assists agronomists and farmers with remote diagnosis.

Educational Tool: Helps students understand plant pathology via AI.

Agro-Tech Startups: Integrates with mobile or drone-based applications.

##📦 Future Enhancements
Integration with mobile apps for field use

Expand to multi-crop, multi-disease classification

Real-time inference via cloud APIs

Geo-tagged disease detection and alerts

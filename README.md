🧠 Brain Tumor Detection using Hybrid Deep Learning
📌 Overview

This project presents a hybrid multi-stage deep learning framework for automated brain tumor detection and analysis using MRI images. The system combines autoencoder-based feature extraction, CNN-based classification, Grad-CAM visualization, and tumor severity estimation to provide accurate, interpretable, and clinically useful results.

🎯 Key Features
✅ Multi-class tumor classification (Glioma, Meningioma, Pituitary, No Tumor)
✅ Autoencoder-based feature extraction for noise reduction
✅ CNN model for accurate classification
✅ Grad-CAM visualization for interpretability
✅ Tumor localization using threshold-based masking
✅ Tumor area calculation & severity analysis
✅ Comprehensive diagnostic output
🧠 Model Architecture

The system follows a multi-stage pipeline:

Image Preprocessing
Feature Extraction (Autoencoder)
Classification (CNN)
Visualization (Grad-CAM)
Tumor Localization & Severity Analysis
📂 Dataset
Source: Kaggle Brain Tumor MRI Dataset
Classes:
🧬 Glioma Tumor
🧬 Meningioma Tumor
🧬 Pituitary Tumor
✅ No Tumor
⚙️ Technologies Used
🐍 Python
🤖 TensorFlow / Keras
🔢 NumPy
📊 Pandas
🖼️ OpenCV
📈 Matplotlib
📉 Scikit-learn
🔄 Workflow
📥 Data Collection & Preprocessing
🔀 Data Splitting (Training & Testing)
🧠 Autoencoder Feature Extraction
🔍 CNN Model Training & Classification
📊 Model Evaluation
🔥 Grad-CAM Visualization
🎯 Tumor Masking & Severity Analysis
📤 Final Prediction Output
📊 Results
🎯 Achieved ~89% accuracy
✅ Strong performance in No Tumor & Pituitary classes
⚠️ Minor confusion between Glioma & Meningioma
🔍 Grad-CAM improves model interpretability
📸 Sample Outputs
🖼️ MRI Image Input
🔥 Grad-CAM Heatmap
🎯 Tumor Mask
📊 Final Classification with Confidence Score
⚠️ Severity Level Output



METHODOLOGY OF THE PROJECT

<img width="1832" height="701" alt="image" src="https://github.com/user-attachments/assets/bf552bf3-1e43-46f6-9988-e1eb616a58a1" />
<br>

<img width="889" height="841" alt="image" src="https://github.com/user-attachments/assets/a65bde8b-0bbf-4313-8e3f-2156b18f425f" />
<br>

RESULTS OF THE WORKING MODEL

<br>
<img width="1078" height="506" alt="image" src="https://github.com/user-attachments/assets/2401a8ce-f0e5-4b4c-946d-7a8c385f5c7d" />
<br>
<img width="1137" height="538" alt="image" src="https://github.com/user-attachments/assets/20941a9f-38db-456f-a07f-d89332047a50" />
<br>
<img width="1229" height="549" alt="image" src="https://github.com/user-attachments/assets/c18e3fee-f8c5-476e-9872-cdf3f4036e15" />
<br>
<img width="1243" height="501" alt="image" src="https://github.com/user-attachments/assets/c3520baf-d818-4b31-9238-18024c505e31" />
<br>
<img width="1225" height="527" alt="image" src="https://github.com/user-attachments/assets/5916f18a-5672-45f7-8d5b-889b01be7b99" />
<br>
<img width="1229" height="404" alt="image" src="https://github.com/user-attachments/assets/d588934c-cefa-463c-b816-56e69eb74540" />
<br>
<img width="1167" height="556" alt="image" src="https://github.com/user-attachments/assets/237f38b3-cb82-4047-94dc-0c319896cc8c" />

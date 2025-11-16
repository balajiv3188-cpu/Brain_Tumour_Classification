# Brain_Tumour_Classification

#💡 Project Overview

This project demonstrates how deep learning can be applied in healthcare diagnostics.
By uploading a brain MRI image, the model predicts which tumor category the image belongs to.


#🔍 Tumor Categories:

1.Glioma
2.Meningioma
3.Pituitary
4.No Tumor

#🚀 How It Works

Upload a brain MRI image (JPG/PNG).
The image is preprocessed (resized, normalized).
The trained deep learning model predicts the tumor type.
The app displays:
Predicted class
Confidence score
Bar chart of probabilities

🧠 Model Information

Model Name: MobileNetV2_best.pkl
Input Size: 224x224 pixels
Framework: TensorFlow
Accuracy: ~95% (based on test dataset)

💻 How to Run the App

Clone or copy this project to your system.
Open in VS Code or any Python IDE.
Install the required libraries:
pip install streamlit tensorflow numpy pillow pickle-mixin

# 🫁Chest-X-Ray-Medical-Diagnosis with pytorch 

This project uses Deep Learning to classify Chest X-Ray images into two categories: Normal and Pneumonia. Built with PyTorch, it leverages transfer learning to provide high-accuracy medical image diagnostics.

Key Features:

Model: Uses DenseNet121 for high-accuracy image classification.

Explainable AI: Uses Grad-CAM to highlight the exact areas in the lungs causing the infection.

Visual Reports: Includes ROC Curves and Confusion Matrix to show model reliability.

Tools & Libraries:

Core: PyTorch, Torchvision

Data: Pandas, NumPy

Evaluation: Scikit-learn (Classification Report)

Visualization: Matplotlib, Seaborn

How it Works:

Data Loading: Images are resized and normalized for the model.

Training: The model learns from thousands of X-ray samples.

Inference: The model predicts if an image is Normal or has Pneumonia.

Visualization: 6 sample predictions are displayed to verify accuracy.

Results:
### Grad-CAM Interpretability



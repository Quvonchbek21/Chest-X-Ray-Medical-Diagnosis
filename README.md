## 🫁Chest-X-Ray-Medical-Diagnosis with pytorch 

<img width="1076" height="467" alt="Skrinshot 2026-03-25 125822" src="https://github.com/user-attachments/assets/4d4f5a9a-4c0d-421e-a9e8-050d93b0ed4b" />

<img width="1065" height="507" alt="Skrinshot 2026-03-25 125909" src="https://github.com/user-attachments/assets/adec75c8-875a-418c-b436-82b573bf6df8" />

<img width="893" height="548" alt="Skrinshot 2026-03-25 135239" src="https://github.com/user-attachments/assets/f4091055-3d9e-4076-ba31-3216f5211daf" />


This project uses Deep Learning to classify Chest X-Ray images into two categories: Normal and Pneumonia. Built with PyTorch, it leverages transfer learning to provide high-accuracy medical image diagnostics.

## Key Features:

Model: Uses DenseNet121 for high-accuracy image classification.

Explainable AI: Uses Grad-CAM to highlight the exact areas in the lungs causing the infection.

Visual Reports: Includes ROC Curves and Confusion Matrix to show model reliability.

## Tools & Libraries:

Core: PyTorch, Torchvision

Data: Pandas, NumPy

Evaluation: Scikit-learn (Classification Report)

Visualization: Matplotlib, Seaborn

## How it Works:

Data Loading: Images are resized and normalized for the model.

Training: The model learns from thousands of X-ray samples.

Inference: The model predicts if an image is Normal or has Pneumonia.

Visualization: 6 sample predictions are displayed to verify accuracy.

## Results:

<img width="530" height="440" alt="Skrinshot 2026-03-22 211631" src="https://github.com/user-attachments/assets/d9ff4ccf-0456-4894-aee7-d70aeff97337" />

<img width="532" height="520" alt="Skrinshot 2026-03-22 211609" src="https://github.com/user-attachments/assets/1e54b29e-a466-4a41-b05e-bae57209e45a" />

<img width="713" height="597" alt="Skrinshot 2026-03-22 211651" src="https://github.com/user-attachments/assets/aad1dcb1-d922-4d76-956a-81efa43ed8f5" />

<img width="769" height="596" alt="Skrinshot 2026-03-22 212438" src="https://github.com/user-attachments/assets/626e65bf-bfba-4b78-890b-5c172ff60d04" />

<img width="494" height="238" alt="Skrinshot 2026-03-22 211713" src="https://github.com/user-attachments/assets/10efc173-90e2-4405-bb44-011e38267f4e" />




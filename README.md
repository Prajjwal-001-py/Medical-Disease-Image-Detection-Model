Medical Image Classification for Disease Detection (Pneumonia)

🏥 Project Overview

This project focuses on the automated detection of Pneumonia from Chest X-ray images using Deep Learning. Developed as part of my AI/ML internship at Inlighnx, this model aims to assist healthcare professionals by providing a high-accuracy screening tool for medical imaging.

📊 Performance & Results

The model was trained and evaluated on the Kaggle Chest X-Ray dataset, achieving significant results that demonstrate its reliability:

Overall Accuracy: 90%

Pneumonia Recall: 94% (High recall is critical in a medical context to ensure fewer cases are missed)

Precision (Normal): 89%

🛠️ Technical Stack & Workflow

Frameworks: Python, TensorFlow, Keras, and OpenCV.

Architecture: Utilized DenseNet121 via Transfer Learning for robust feature extraction from medical images.

Preprocessing: Implemented advanced Data Augmentation (rotation, zoom, and horizontal flips) to improve model generalization.

Optimization: Employed EarlyStopping and ReduceLROnPlateau callbacks to prevent overfitting and ensure efficient convergence.

📂 Repository Structure

model.ipynb: Full source code for data preprocessing, model architecture, and training.

best_pneumonia_model.h5: The final trained model weights with the highest validation performance.

requirements.txt: Environment dependencies for reproducing the results.

🚀 About Me

I am Prajjwal Gautam, a B.Tech CSE student at Jabalpur Engineering College. I am passionate about Agentic AI and building practical, mind-driven automation solutions.

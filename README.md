🧠 Brain Tumor Detection CNN

🧠 Brain Tumor Detection CNN
Show Image
Show Image
Show Image
Deep learning model for detecting brain tumors in MRI images using Convolutional Neural Networks.
🚀 Quick Start
bash# Install dependencies
pip install tensorflow keras opencv-python numpy matplotlib scikit-learn

# Run training
python mri_image_classifier.py
📊 Dataset Structure
dataset/
├── tumor/          # MRI images with tumors
└── no_tumor/       # Normal MRI images
🏗️ Model Architecture

Input: 224×224×3 RGB images
Architecture: 4-layer CNN with batch normalization
Output: Binary classification (tumor/no tumor)
Optimizer: Adam
Accuracy: ~90%

💻 Usage
Training
python# Automatically handles data loading, training, and evaluation
python mri_image_classifier.py
Prediction
python# Single image prediction
resultado = predecir_tumor(model)

# Multiple images
resultados = analizar_multiples_imagenes()

# Test with dataset samples
probar_con_dataset_prueba(5)
📁 Files

mri_image_classifier.py - Main training script
modelo_tumor_cerebral.h5 - Trained model (generated after training)
README.md - This file

🔧 Configuration
pythonIMG_HEIGHT = 224
IMG_WIDTH = 224
BATCH_SIZE = 32
EPOCHS = 50
⚠️ Disclaimer
For educational purposes only. Not intended for medical diagnosis.
📄 License
MIT License - see LICENSE file for details.

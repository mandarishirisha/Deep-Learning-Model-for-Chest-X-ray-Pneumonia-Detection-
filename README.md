Deep Learning Model for Chest X-ray Pneumonia Detection

This project focuses on building and evaluating deep learning models to automatically detect Pneumonia from Chest X-ray images.
It compares multiple architectures — VGG19, ResNet50, DenseNet121, EfficientNetB3, and a custom CNN model — to identify which performs best for binary classification (Pneumonia vs Normal).

Models Implemented

VGG19

ResNet50

DenseNet121

EfficientNetB3

Custom CNN

📂 Dataset
The dataset used is the Chest X-Ray Images (Pneumonia) dataset available on Kaggle.
It contains:

train/ – training images

val/ – validation images

test/ – test images

Each folder has two subfolders:

PNEUMONIA/

NORMAL/

⚙️ Requirements

Make sure you have the following Python libraries installed:

pip install torch torchvision torchaudio

pip install matplotlib seaborn numpy pandas scikit-learn

pip install opencv-python tqdm

📊 Model Evaluation Metrics

For each model, the following metrics are computed:

Accuracy
AUC (Area Under ROC Curve)

Precision

Recall

F1 Score

False Positive Rate (FPR)

False Negative Rate (FNR)

📈 Visualizations

Training vs Validation Accuracy

ROC Curves for all models

Confusion Matrices

Model Comparison Charts (Accuracy, AUC, etc.)

Conclusion

The project demonstrates that transfer learning using modern architectures like EfficientNet or DenseNet achieves high accuracy and robust generalization in Pneumonia detection tasks.

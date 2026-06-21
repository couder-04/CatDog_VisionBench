Animal Classifier 🐱🐶

A comprehensive image classification project comparing traditional Machine Learning approaches with modern Deep Learning and Transformer-based architectures on the Cat vs Dog classification task.

Models Implemented

Traditional Machine Learning

* Logistic Regression
* Support Vector Machine (SVM)

Deep Learning

* Custom CNN
* ResNet34 (Transfer Learning)
* EfficientNet-B0 (Transfer Learning)

Vision Transformers

* ViT Base Patch16-224 (Fine-Tuning)

⸻

Dataset

The project uses a binary image classification dataset containing:

* Cats
* Dogs

Images are preprocessed and resized before training and evaluation.

⸻

Project Structure

Animal_Classifier/
│
├── dataset_analysis.ipynb
├── logistic_reg.ipynb
├── svm.ipynb
├── small-cnn-final.ipynb
├── resnet-34-ft.ipynb
├── efficient_net_B0_FT.ipynb
├── vit_base_patch_16_FT.ipynb
├── requirements.txt
├── cat.png
└── dog.jpeg

⸻

Techniques Used

* Data Analysis & Visualization
* Data Augmentation
* Transfer Learning
* Fine-Tuning
* Model Evaluation
* Confusion Matrix Analysis
* Precision, Recall & F1 Score
* Inference on Custom Images

⸻

Libraries

* PyTorch
* Torchvision
* Transformers (Hugging Face)
* Scikit-Learn
* NumPy
* Matplotlib
* Seaborn

⸻

Training Pipeline

1. Load and analyze dataset
2. Apply preprocessing and augmentation
3. Train multiple models
4. Evaluate performance
5. Compare results across architectures
6. Perform inference on unseen images

⸻

Sample Inference

Input Image → Preprocessing → Model Prediction → Cat / Dog Classification

⸻

Future Improvements

* MobileNetV3 benchmarking
* ConvNeXt implementation
* Swin Transformer experiments
* Hyperparameter optimization
* Model deployment using Streamlit/FastAPI

⸻

Author

Parth
IIT Patna — Computer Science & Engineering
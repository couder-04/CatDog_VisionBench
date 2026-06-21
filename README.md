🐱🐶 Animal Classifier: Classical ML to Vision Transformers

A comprehensive computer vision project that benchmarks traditional Machine Learning, Convolutional Neural Networks (CNNs), Transfer Learning, and Vision Transformers on the Cat vs Dog image classification task.

The objective is to compare model performance, training efficiency, and generalization across multiple generations of image classification architectures.

⸻

🚀 Models Evaluated

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

📊 Dataset

Binary image classification dataset containing:

* Cats
* Dogs

Images are resized, normalized, and augmented to improve model robustness and generalization.

⸻

🛠️ Key Techniques

* Exploratory Data Analysis (EDA)
* Data Augmentation
* Feature Extraction
* Transfer Learning
* Fine-Tuning Pretrained Models
* Hyperparameter Tuning
* Performance Benchmarking
* Custom Image Inference
* Confusion Matrix Analysis
* Precision, Recall, and F1-Score Evaluation

⸻

🏗️ Project Structure

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

⚙️ Technology Stack

* Python
* PyTorch
* Torchvision
* Hugging Face Transformers
* Scikit-Learn
* NumPy
* Matplotlib
* Seaborn

⸻

🔄 Training Pipeline

1. Dataset Analysis and Visualization
2. Image Preprocessing and Augmentation
3. Model Training
4. Fine-Tuning Pretrained Networks
5. Performance Evaluation
6. Comparative Benchmarking
7. Custom Image Inference

⸻

📈 Evaluation Metrics

Models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Training Time
* Inference Time

⸻

🔍 Sample Inference

Input Image
      ↓
Preprocessing
      ↓
Trained Model
      ↓
Cat / Dog Prediction
      ↓
Confidence Score

⸻

🎯 Future Enhancements

* MobileNetV3 Benchmarking
* ConvNeXt Implementation
* Swin Transformer Fine-Tuning
* Automated Hyperparameter Optimization
* Streamlit Web Application
* FastAPI Deployment
* Model Quantization & Optimization

⸻

👨‍💻 Author

Parth
B.Tech, Computer Science & Engineering
Indian Institute of Technology (IIT) Patna

⸻

⭐ If you found this project interesting, consider starring the repository.
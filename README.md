# comparison_of_ml_vs_dl_of_pneumonia-detection-and-severity-analysis
A medical imaging project that benchmarks five supervised ML models against a DenseNet121 transfer learning model for pneumonia detection using chest X-rays. Includes preprocessing, augmentation, performance comparison, and visualization to show the accuracy gap between classical ML and deep learning approaches.


# Pneumonia Detection: ML vs Deep Learning Comparison

This project implements a complete medical imaging pipeline for pneumonia detection and severity assessment using chest X-ray images. The workflow begins by training and evaluating five supervised machine learning models as baseline classifiers, followed by a transfer learning approach using DenseNet121 to significantly boost performance. The project highlights how modern deep CNN architectures outperform traditional ML models in medical image classification tasks.

## 🔍 Project Highlights
- Dataset: Chest X-ray images (NORMAL vs PNEUMONIA)
- Image preprocessing + CLAHE contrast enhancement
- Data augmentation for generalization
- Baseline ML classifiers (5 models)
- DenseNet121 transfer learning model
- Performance comparison & visualization
- Severity / involvement estimation
- Medical evaluation metrics

## 🧠 Models Used

### 🟩 **Machine Learning (Baseline)**
Five supervised models such as:
- SVM
- Random Forest
- Logistic Regression
- KNN
- Decision Tree  
(Used as benchmark)

### 🟦 **Deep Learning (Primary)**
- DenseNet121 (transfer learning)
- Fine-tuned for binary classification
- Achieved significantly higher accuracy

## 📈 Outputs & Evaluation
This project generates:
- Classification reports
- Confusion matrices
- Accuracy & loss curves
- Visual severity indicators
- Model comparison charts

## 🎯 Conclusion
DenseNet121 demonstrates superior performance and robustness compared to traditional ML models, emphasizing the importance of deep feature extraction for radiology-based diagnostics.

---

📌 *Developed as part of a medical AI project involving classification, visualization, and model benchmarking.*

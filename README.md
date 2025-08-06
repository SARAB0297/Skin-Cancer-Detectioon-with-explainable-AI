# 🧠 Skin Cancer Classification using DenseNet121 with Explainable AI (Grad-CAM & LIME)

This project presents a deep learning pipeline for **multiclass skin cancer classification** using the **HAM10000** dataset. We utilized the **DenseNet121** architecture, enhanced with **contrast preprocessing** and **data augmentation**, to build a high-performing and interpretable model. To ensure transparency in predictions, we integrated **Grad-CAM** and **LIME** for visual explainability.

---

## 📌 Objectives
- Train an accurate CNN model for classifying 7 types of skin lesions.
- Enhance dermoscopic images through contrast adjustment.
- Apply **Grad-CAM** and **LIME** to explain model predictions.
- Evaluate performance using metrics like accuracy, precision, recall, F1-score, and confusion matrix.

---

## 🗂 Dataset: HAM10000
**HAM10000** (*Human Against Machine with 10,000 training images*) is a benchmark dermoscopic image dataset for skin cancer research.

| **Class Label** | **Description**                                      | **Count** |
|-----------------|------------------------------------------------------|-----------|
| akiec           | Actinic Keratoses and Intraepithelial Carcinoma      | 327       |
| bcc             | Basal Cell Carcinoma                                 | 514       |
| bkl             | Benign Keratosis-like Lesions                        | 1,099     |
| df              | Dermatofibroma                                       | 115       |
| mel             | Melanoma                                             | 1,113     |
| nv              | Melanocytic Nevi                                     | 6,705     |
| vasc            | Vascular Lesions                                     | 142       |

---

## 🛠️ Technologies Used
- **Language:** Python 3.x  
- **Libraries:** TensorFlow, Keras, NumPy, Pandas, OpenCV, Matplotlib, Seaborn  
- **XAI:** Grad-CAM, LIME  
- **Evaluation:** scikit-learn  
- **Environment:** Kaggle Notebooks
- link: https://www.kaggle.com/code/sarabjeet1020/notebook4f8b35c6ba

---

## 🔍 Model Summary
- Pretrained **DenseNet121** with input size `224x224`
- Fine-tuned with **contrast-enhanced images**
- **EarlyStopping** and **ReduceLROnPlateau** callbacks
- Achieved **98.5% accuracy** on validation set

---

## 📊 Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- ROC Curve (class-wise)
- Grad-CAM & LIME visual overlays for interpretability

---

## 🔬 Explainability
- **Grad-CAM**: Highlights the discriminative image regions used by the CNN
- **LIME**: Provides local image segment importance around each prediction  


---

## 🔭 Future Scope
- Add **SHAP** for global model explanation
- Deploy as a mobile/web application
- Explore ensemble models and real-time dermoscopy input support

---

## 📷 Sample Visualizations

<insert Grad-CAM & LIME overlay images or link to folder>

---

## 🤝 Acknowledgements
This project was developed as part of the **ELC Summer Internship 2025** at **Thapar Institute of Engineering & Technology**.  
Special thanks to mentors for their guidance.

---

## 📌 License
This project is released under the [Apache2.0 License].

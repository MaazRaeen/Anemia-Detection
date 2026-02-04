# 🩺 Non-Invasive Anemia Detection Using Ocular Images and Deep Learning

## 📌 Project Overview
Anemia is a widespread health condition that traditionally requires invasive blood tests for diagnosis. These tests can be expensive, time-consuming, and difficult to access in rural or low-resource regions.

This project proposes a **non-invasive, AI-based anemia detection system** using ocular (eye) images, specifically focusing on the **palpebral conjunctiva**, whose color variations are closely associated with hemoglobin levels.

By leveraging **deep learning** and **ensemble learning techniques**, the system classifies individuals as **anemic** or **non-anemic** with improved accuracy and recall, making it suitable for early medical screening.

---

## 🎯 Objectives
- Develop a **non-invasive anemia detection system**
- Analyze **ocular images** instead of blood samples
- Improve detection accuracy using **deep learning models**
- Enhance reliability using **ensemble learning**
- Support **accessible healthcare** in rural and underserved areas

---

## 🧠 Methodology

### 1️⃣ Image Preprocessing
To improve model performance and robustness, the following preprocessing steps are applied:
- Image resizing  
- Normalization  
- Contrast enhancement using **CLAHE**  
- Data augmentation (rotation, flipping, zooming)

---

### 2️⃣ Deep Learning Models
The system uses **transfer learning** with three pre-trained CNN models:

- **VGG16**
- **DenseNet121**
- **InceptionV3**

Each model is fine-tuned to classify ocular images into:
- **Anemic**
- **Non-Anemic**

---

### 3️⃣ Ensemble Learning
To reduce false negatives and improve reliability, predictions from all three CNN models are combined using an **ensemble approach**.

This ensures:
- Higher accuracy
- Improved recall for anemic cases
- Better suitability for medical screening

---

## 📊 Results
- Improved classification accuracy compared to individual models
- Higher recall for detecting anemic patients
- Reduced false negatives
- Robust performance across different lighting and image conditions

---

## ✅ Key Highlights
- 🔬 Non-invasive anemia detection using eye images  
- 🧠 Deep learning with CNN and ensemble models  
- 📈 Improved recall for anemic cases  
- 🌍 Suitable for low-resource and rural healthcare  
- 📱 Potential for smartphone-based screening applications  

---

## 🛠️ Technologies Used
- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy, Pandas**
- **Matplotlib / Seaborn**

---

## 🚀 Future Scope
- Integration with mobile applications
- Multi-class anemia severity prediction
- Real-time detection using smartphone cameras
- Expansion to other non-invasive medical screening tasks

---

## 👨‍💻 Author
**Maaz**  
Engineering Student | Final Year Project  
**Sharda University**

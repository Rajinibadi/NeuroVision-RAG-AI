# 🧠 NeuroVision-RAG AI
### Brain Tumor Detection & Medical Knowledge Assistant using CNN + RAG

---

## 🚀 Project Overview

NeuroVision-RAG AI is a multimodal Artificial Intelligence system that combines **Computer Vision, Deep Learning, and Retrieval-Augmented Generation (RAG)** to analyze brain MRI images and generate intelligent medical explanations.

The system can:

- Detect potential **brain tumors from MRI scans** using a Convolutional Neural Network (CNN)
- Retrieve **relevant medical knowledge** using a RAG pipeline
- Generate **AI-based explanations** about the diagnosis
- Visualize **model attention** to understand predictions

This project demonstrates how **AI can assist healthcare professionals in medical image analysis and decision support systems.**

⚠️ **Disclaimer:** This project is for educational and research purposes only and should not replace professional medical diagnosis.

---

## 🧠 System Architecture

MRI Brain Scan  
↓  
CNN Feature Extraction (ResNet18)  
↓  
Tumor Classification  
↓  
Medical Knowledge Retrieval (RAG)  
↓  
AI Explanation Generation  

---

## 🔬 Technologies Used

- Python
- PyTorch
- Computer Vision
- Deep Learning
- CNN (ResNet18)
- FAISS
- Sentence Transformers
- Retrieval Augmented Generation (RAG)
- Gradio (for web interface)
- Matplotlib
- Seaborn

---

## ✨ Features

✔ Brain MRI tumor detection  
✔ AI-generated medical explanations  
✔ Medical knowledge retrieval system  
✔ Attention heatmap visualization  
✔ Interactive AI interface using Gradio  
✔ End-to-end pipeline from image → diagnosis → explanation


-

## ⚙️ Installation

Follow the steps below to set up the project locally.

### 1️⃣ Clone the Repository

git clone https://github.com/YOUR_USERNAME/NeuroVision-RAG-AI.git

### 2️⃣ Navigate to the Project Directory

cd NeuroVision-RAG-AI

### 3️⃣ Install Dependencies

pip install -r requirements.txt

---

## ▶️ Running the Project

1. Open the notebook **NeuroVision_RAG_AI.ipynb** in Google Colab or Jupyter Notebook.

2. Run all cells step-by-step.

3. Upload a **brain MRI image** when prompted.

4. The system will:

- Analyze the MRI scan using a CNN model  
- Detect whether a tumor is present  
- Retrieve related medical knowledge using RAG  
- Generate an AI-based explanation  

---

## 📊 Example Workflow

1️⃣ Upload MRI Image  

2️⃣ CNN extracts visual features from the MRI scan  

3️⃣ Model predicts **Tumor / No Tumor**  

4️⃣ RAG system retrieves relevant medical knowledge  

5️⃣ AI generates an explanation and recommendation  

---

## 🖼 Example Output

Prediction: **Tumor Detected**

Retrieved Knowledge:

Brain tumors are abnormal growths of cells in the brain. MRI scans are commonly used to detect tumors and determine their location and size.

AI Explanation:

The model analyzed the MRI image using a convolutional neural network trained on brain scan patterns. The detected abnormal region suggests a possible tumor presence.

Recommendation:

Consult a neurologist or medical professional for further diagnosis and treatment.

---

## 🌍 Real-World Applications

This system demonstrates how AI can support real-world medical systems:

• Radiology assistance tools  
• Medical decision support systems  
• Early tumor detection research  
• AI-assisted diagnosis platforms  
• Healthcare AI education tools  



## 📈 Skills Demonstrated

This project showcases several important AI/ML skills:

• Deep Learning Model Development  
• Computer Vision using CNNs  
• Retrieval Augmented Generation (RAG)  
• Medical Image Analysis  
• PyTorch Model Implementation  
• End-to-End AI System Development  

---

## 🔮 Future Improvements

Some potential upgrades for this project include:

• Training on a **large brain MRI dataset**  
• Adding **Vision Transformer (ViT)** models  
• Implementing **Grad-CAM tumor localization**  
• Integrating a **medical chatbot using LLMs**  
• Deploying as a **web application for hospitals**

---


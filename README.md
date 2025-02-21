# ✋ ASL Recognition with Convolutional Neural Networks  

## 📌 Project Overview  
This project focuses on **American Sign Language (ASL) recognition** using **Convolutional Neural Networks (CNNs) and transfer learning (VGG16)**. It classifies **36 ASL signs** (A-Z, 0-9) from images with **high accuracy**, making it a powerful tool for sign language translation applications.  

## 🚀 Features  
- ✅ **CNN-based ASL Classifier** – Custom **Convolutional Neural Network (CNN)** trained for ASL recognition.  
- ✅ **Transfer Learning with VGG16** – Pretrained model fine-tuned for higher accuracy.  
- ✅ **Dataset of 2,515 images** – Hand gestures representing ASL letters & numbers.  
- ✅ **Accuracy of 98.81%** – Improved model performance using deep learning.  
- ✅ **Potential Real-time Applications** – Can be deployed for **ASL-to-text translation**.  

## 📂 Repository Structure  
ASL-Recognition-with-Convolutional-Neural-Networks/  
│── README.md # Project Overview  
│── LICENSE # BSD 3-Clause License  
│── .gitignore # Ignore unnecessary files   
│  
├── data/  
│ └── asl_dataset/ # Dataset   
│  
├── notebooks/  
│ ├── ASL Recognition.ipynb # Jupyter Notebook with model training  
│ ├── ASL Recognition.html # html version of code  
│  
├── reports/  
│ ├── Sign Language Recognition Using Deep Learning.pdf # Final Project Report  
│ ├── Presentation Script.txt # Presentation Script  


## 💾 Dataset  
The dataset consists of **hand gesture images** representing **A-Z** and **0-9**, with **70 images per class**.  
**ASL Dataset Folder Structure:**  
asl_dataset/   
├── A/ (70 images)   
├── B/ (70 images)   
├── C/ (70 images)   
.  
.  
.   
├── 9/ (70 images)  

## 📊 Model Performance  
| Model  | Training Accuracy | Validation Accuracy | Test Accuracy |
|--------|-----------------|---------------------|--------------|
| **CNN**  | 99.80%  | 97.61%  | 96.83%  |
| **VGG16 (Transfer Learning)** | 100%  | 99.60%  | **98.81%**  |

✅ **VGG16 outperforms the CNN model**, reducing misclassification errors.  

## 🛠️ How to Run  
### **1️⃣ Install Dependencies**  

```bash
pip install tensorflow keras numpy pandas matplotlib seaborn splitfolders

```
### **2️⃣ Run the Notebook** 
- Open notebooks/ASL Recognition.ipynb in Jupyter Notebook.
- Run all cells to train and evaluate the ASL recognition model.

## 🔍 Future Enhancements
- Real-time ASL translation using OpenCV.
- Integrating the model into a mobile app for accessibility.
- Expanding dataset for better generalization.

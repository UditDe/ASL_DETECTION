# **🧪 Experimental Study: Sign Language Detection using Computer Vision** 🤟📷  

## **Objective**  
This experiment aims to develop a **Sign Language Detection** system using **Computer Vision** and a **custom Convolutional Neural Network (CNN)**. The study explores the feasibility of recognizing static sign language gestures without relying on pre-trained models like TensorFlow, focusing instead on a **pure PyTorch-based approach**.  

## **Hypothesis**  
A **custom-built CNN model** can effectively classify American Sign Language (ASL) gestures into **29 distinct classes** with high accuracy.  

---

## **🛠 Experimental Setup**  

### **Materials & Tools**  
- **Dataset**: ASL Alphabet Dataset ([Kaggle](https://www.kaggle.com/datasets/grassknoted/asl-alphabet))  
- **Programming Language**: Python 🐍  
- **Libraries**: PyTorch 🔥, OpenCV 👁, NumPy 📊, Matplotlib 📈  

### **Procedure**  
1️⃣ **Data Collection** – Import ASL images and preprocess them (resize, normalize, label encoding).  
2️⃣ **Model Architecture** – Design a **CNN** to extract hand gesture features and classify them.  
3️⃣ **Training** – Train the model using **CrossEntropyLoss** and **Adam optimizer**.  
4️⃣ **Evaluation** – Test model performance on a validation dataset.  
5️⃣ **Deployment** – Implement real-time detection using OpenCV.  

---

## **📊 Results & Observations**  
The CNN model successfully recognized **29 static ASL gestures**, demonstrating the potential of using **custom-built models** for sign language recognition.  

### **Findings:**  
✅ Model achieved **high accuracy** on training data.  
✅ **Real-time inference** was feasible using OpenCV.  
✅ **Limitations**: Struggled with lighting variations and complex backgrounds.  

---

## **📌 Conclusion**  
This experiment validates the **effectiveness of CNN-based models** for static sign language recognition. Future research can explore **dynamic sign recognition** and **deployment on mobile platforms**.  

### **Future Work & Improvements**  
🔹 Implement **data augmentation** for better generalization  
🔹 Develop a **mobile application** for real-world usage  
🔹 Expand to **dynamic sign language recognition**  

---

## **⚙️ Replicating the Experiment**  

### **Installation**  
```bash  
git clone https://github.com/UditDe/sign-language-detection.git  
cd sign-language-detection  
pip install -r requirements.txt  
```

### **Run the Experiment**  

#### **Step 1: Train the Model**  
```python  
python train.py  
```
#### **Step 2: Test the Model**  
```python  
python test.py  
```
#### **Step 3: Real-Time Sign Detection**  
```python  
python detect.py  
```

---

## **💡 Contributions & Further Research**  
This is an open research experiment. Contributions and discussions are welcome! Feel free to fork, modify, and improve. 🚀  

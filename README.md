# 🎭 Mood Classification with CNN

A deep learning project that classifies facial moods as **Happy 😊** or **Sad 😢** using a **Convolutional Neural Network (CNN)**.

Built with **TensorFlow/Keras** and deployed using **Gradio** for an interactive, real-time web interface — making it ideal for interviews, ML portfolios, and practical deep learning demonstrations.

Simple binary classification. Solid deep learning fundamentals. Clean deployment.

---

## 📸 Demo Preview

![demo](https://github.com/Tanmay1112004/mood-classification-cnn/blob/main/mood%20classifiction%20using%20Deep%20learnining%20-%20cnn/screenshots/Screenshot%202025-08-29%20224150.png)

![demo](https://github.com/Tanmay1112004/mood-classification-cnn/blob/main/mood%20classifiction%20using%20Deep%20learnining%20-%20cnn/screenshots/Screenshot%202025-08-29%20224426.png)


---

## 📌 Project Overview

This project demonstrates:

* End-to-end CNN training pipeline
* Data augmentation for improved generalization
* Early stopping & checkpointing
* Model persistence (`.h5` format)
* Real-time prediction with confidence scores
* ML model + UI integration

It showcases practical understanding of computer vision, model optimization, and deployment.

---

## ✨ Key Features

* CNN trained on custom Happy/Sad dataset
* Image augmentation (rotation, zoom, flipping)
* EarlyStopping & ModelCheckpoint callbacks
* Gradio-based interactive UI
* Confidence-based emoji predictions
* Clean, Colab-compatible workflow

---

## 🧠 Model Architecture

```
Input Image
   ↓
Conv2D → ReLU
   ↓
MaxPooling
   ↓
Conv2D → ReLU
   ↓
MaxPooling
   ↓
Conv2D → ReLU
   ↓
MaxPooling
   ↓
Flatten
   ↓
Dense (256) + Dropout (0.4)
   ↓
Dense (1, Sigmoid)
```

### Training Configuration

| Component         | Value               |
| ----------------- | ------------------- |
| Optimizer         | Adam                |
| Loss              | Binary Crossentropy |
| Metric            | Accuracy            |
| Output Activation | Sigmoid             |

The sigmoid layer outputs a probability between 0 and 1, enabling transparent confidence scoring.

---

## 📂 Project Structure

```id="m7kd9x"
mood-classification-cnn/
│
├── data/                        # Training & validation dataset (not included)
├── mood_classifier.ipynb        # Main notebook (Colab compatible)
├── best_mood_model.h5           # Saved trained model
└── README.md                    # Documentation
```

Structured for clarity and scalability.

---

## ⚡ How to Run

### Option 1: Google Colab (Recommended)

1️⃣ Upload `mood_classifier.ipynb`
2️⃣ Mount Google Drive
3️⃣ Train the CNN OR load `best_mood_model.h5`
4️⃣ Launch Gradio interface
5️⃣ Upload an image → Get prediction instantly

---

### Option 2: Local Setup

```bash
git clone https://github.com/Tanmay1112004/mood-classification-cnn.git
cd mood-classification-cnn
pip install -r requirements.txt
```

Or manually install:

```bash
pip install tensorflow gradio pillow numpy
```

---

## 📊 Model Performance

* Training accuracy improves consistently with augmentation
* Dropout reduces overfitting
* EarlyStopping prevents unnecessary epochs
* Confidence score provides prediction transparency

Example Output:

* 😊 Happy — 92% Confidence
* 😢 Sad — 87% Confidence

---

## 🎯 What This Project Demonstrates

* CNN fundamentals
* Binary image classification
* Model regularization techniques
* Callback usage (EarlyStopping, Checkpointing)
* ML-to-Web deployment pipeline
* Explainable confidence scoring

This project is strong for:

* Deep Learning internships
* Computer Vision roles
* Entry-level ML positions
* Portfolio demonstrations

---

## 🔮 Future Enhancements

* Multi-class emotion detection (Happy, Sad, Angry, Neutral, etc.)
* Transfer learning (MobileNet, ResNet)
* Real-time webcam prediction
* REST API deployment (FastAPI)
* Docker containerization

---

## 📌 Requirements

* Python 3.10+
* TensorFlow 2.x
* Gradio
* Pillow
* NumPy

---

## 📜 License

MIT License

---

### 👨‍💻 Author

**Tanmay**

Open to opportunities in:

* Deep Learning
* Computer Vision
* AI/ML Engineering
* Applied AI Development

---


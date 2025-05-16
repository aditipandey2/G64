
# 🎙️ Voice Shield: AI-Powered Deepfake Audio Defense

**Final Year Major Project**  
**B.Tech in Computer Science & Engineering**  
**Jaypee University of Information Technology, Waknaghat**  

**Team Members:**  
- Isha (211293)  
- Aditi Pandey (211326)  
**Supervisor:** Dr. Ruchi Verma (Assistant Professor, SG)  

## 🧠 Project Description

Deepfake audio has emerged as a critical threat in the field of cybersecurity, enabling impersonation, fraud, and misinformation at scale. "Voice Shield" is an interpretable and lightweight detection system designed to distinguish between genuine and synthetic audio using advanced machine learning techniques.

We use MFCC-based feature extraction and models like SVM, XGBoost, and CNN to identify deepfakes efficiently and accurately. Unlike complex black-box systems, Voice Shield is optimized for transparency, scalability, and real-time applicability.

## 📁 Folder Structure

```
voice-shield/
├── code            # Trained models
├── data/                    # Audio samples and features
├── G64.pdf              # Final Report
│── G64.pptx             # Presentation
│── proposal.pdf         # Project Proposal
└── README.md
```

## 💻 Source Code

- **Preprocessing**: PyDub & LibROSA for denoising, normalization, and segmentation.
- **Feature Extraction**: MFCC, Spectral Centroid, ZCR, Spectral Bandwidth, Spectral Contrast.
- **Dimensionality Reduction**: PCA to improve speed and efficiency.
- **Models**: SVM (primary), CNN, XGBoost.
- **Front-End**: React.js interface for user interaction.
- **Back-End**: Flask-based REST API for inference and communication.

## 📜 Documentation

- 📄 [Final Report - G64.pdf](./documentation/G64.pdf)  
- 📊 [Presentation - G64.pptx](./documentation/G64.pptx)  
- 📝 [Project Proposal - proposal.pdf](./documentation/proposal.pdf)  

## ⚙️ Installation Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/voice-shield.git
   cd voice-shield
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

3. **Install Python Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Start Flask Backend**
   ```bash
   python app.py
   ```

5. **Start React Frontend**
   ```bash
   cd src/frontend
   npm install
   npm run dev
   ```

## 🎥 Video Demonstration

Watch a 5-minute walkthrough here:  
🔗 [Loom Video Demo](https://www.loom.com/share/70c2e4323be14bb5a3594d2f2389bd6c?sid=307cb41e-b3e5-4b6f-9ab0-8ad56d0fc049)

## 🧪 Testing & Evaluation

- 📊 Metrics Used: Accuracy, Precision, Recall, F1-Score, Equal Error Rate (EER)
- 📈 Tools: Scikit-learn, TensorBoard
- 🧪 Benchmark Dataset: ASVSpoof 2019 Logical Access

## ✅ Features

- Real-time deepfake detection
- Modular and scalable architecture
- Interpretable decisions via SHAP/LIME (planned)
- Lightweight ML models for mobile/IoT integration
- Easy front-end interaction for uploading `.wav` files

## 🚀 Future Scope

- Real-time detection in phone calls and live meetings
- Multilingual & regional accent support
- Audio-visual deepfake detection (voice + face sync)
- Enhanced transparency with XAI methods (SHAP, LIME)

## 📌 Additional Components

- ✅ GitHub Issues and Project Board for tracking tasks
- 🧪 Unit tests for feature extraction and inference pipeline
- 📂 Cleanly organized repo for future contributions

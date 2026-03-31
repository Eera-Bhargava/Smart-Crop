# SmartCrop – AI-Powered Crop Disease & Nutrient Detection

## Overview
SmartCrop is an AI-powered agricultural diagnostic system that analyzes plant leaf images to detect crop diseases and nutrient deficiencies in real time. The system is designed to provide instant, actionable insights to farmers, enabling early intervention and reducing crop losses.

---

## Problem Statement
Crop diseases and nutrient deficiencies often go undetected until significant damage has occurred, leading to:

- Up to 40% reduction in crop yield
- High dependency on manual inspection and expert intervention
- Increased pesticide usage and environmental damage
- Financial instability for farmers, especially in rural areas

---

## Solution
SmartCrop transforms a smartphone or laptop into a **crop health diagnostic tool** by:

- Allowing users to upload leaf images
- Running AI-based classification models
- Providing instant diagnosis with confidence scores and severity levels
- Delivering actionable recommendations for treatment

---

## System Workflow

1. User uploads plant leaf image  
2. Image preprocessing (resizing to 224x224, normalization)  
3. Model inference using deep learning  
4. Output:
   - Crop name
   - Disease type
   - Severity level
   - Confidence score  

---

## AI Model

- Model: **MobileNetV2 (Transfer Learning)**
- Dataset: PlantVillage dataset (38 disease classes)
- Why MobileNetV2:
  - Lightweight and fast
  - Suitable for mobile/edge deployment
  - High accuracy with low computational cost

---

## System Architecture

- Frontend: HTML, CSS, JavaScript  
- Backend: Python (Flask)  
- ML Serving: FastAPI  
- Model: TensorFlow / Keras  
- Libraries: NumPy, Pillow  

---

## Key Features

- Real-time image-based disease detection  
- Confidence score for prediction reliability  
- Severity analysis (Low / Medium / High)  
- Low-connectivity compatible (local server deployment)  
- User-friendly interface for non-technical users  

---

## Demo

(Add screenshots here)

OR

[Demo Video Link]

---

## Results

- Accurate classification of crop diseases across multiple classes  
- Fast inference suitable for real-time usage  
- Improved early detection capability compared to manual inspection  

---

## Future Scope

- Integration of nutrient deficiency detection  
- Mobile app deployment for farmers  
- Edge AI device for on-field usage  
- Regional language support  
- Recommendation engine for treatment solutions  

---

## My Contribution

- Designed and implemented the end-to-end AI pipeline  
- Trained and optimized MobileNetV2 model using transfer learning  
- Built backend system for image processing and inference  
- Developed user workflow for real-time diagnosis  
- Contributed to system architecture and deployment strategy  

---

## How to Run

```bash
git clone https://github.com/your-username/smartcrop
cd smartcrop
pip install -r requirements.txt
python app.py

# Deepshield-Federated-AI-Against-Deepfakes
Federated Learning based Deepfake Detection for Images, Audio &amp; Video


# 🧠 Federated Learning for Deepfake Detection 

This is our major project for detecting deepfakes using **Federated Learning (FL)**.  
We are focusing on:
- 🖼️ Image Deepfake Detection
- 🔊 Audio Deepfake Detection
- 🎥 Video Deepfake Detection

## 👥 Team Members
- Manushree N
- panuganti Mugdha
- Prathibha
- Prisha Mehta

## 🔧 Tech Stack
- Python, TensorFlow / PyTorch
- Google Colab
- Federated Learning (Flower / PySyft)
- Deep Learning (CNN, RNN, etc.)

## 📁 Project Structure

deepfake-detection-fl/
├── images/                     
│   ├── dataset/                
│   ├── models/                 
│   └── notebooks/              

├── audio/                      
│   ├── dataset/                
│   ├── models/                 
│   └── notebooks/              

├── video/                      
│   ├── dataset/                
│   ├── frame_extraction/       
│   ├── models/                 
│   └── notebooks/              

├── federated_learning/         
│   ├── image_fl.py             
│   ├── audio_fl.py             
│   ├── video_fl.py             
│   └── server_client_config/   

├── utils/                      
│   ├── preprocessing.py        
│   ├── metrics.py              
│   └── logger.py               

├── models/                     
│   ├── best_model_image.h5     
│   ├── best_model_audio.pth    
│   └── best_model_video.pth    

├── results/                    
│   ├── image_results.png       
│   ├── audio_results.png       
│   └── report.pdf              

├── dashboard/                 # 🖥️ Streamlit/Flask UI for demo
│   ├── app.py                  
│   ├── components/             
│   └── templates/              

├── tests/                     # 🧪 Unit tests for ML pipeline
│   ├── test_model_accuracy.py 
│   └── test_preprocessing.py  

├── requirements.txt            # ✅ Python libraries
├── .gitignore                  # 🚫 Ignore checkpoints, logs, .DS_Store etc.
├── README.md                   # 📘 Project intro, setup, usage, team
└── LICENSE                     # 📝 MIT or Apache 2.0 license

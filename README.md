# Parkinsons-Detection_ByVOICE  

## Introduction  

Parkinson’s disease (PD) is a progressive neurological disorder that affects motor functions and speech. Early detection is crucial for effective medical intervention and improving patient quality of life. However, manual diagnosis based on clinical evaluations can be subjective and time-consuming.  

This project develops an **automated Parkinson’s detection system** using both **Machine Learning (ML)** and **Deep Learning (DL)** techniques. It leverages a rich set of **voice-based features**, including jitter, shimmer, SNR, HNR, LPC, LPCC, and GFCC, as well as spectrogram representations for CNN-based learning. The system provides a comparative evaluation of ML and DL models.  

This work was carried out as part of a **summer internship** under the guidance of professors from **Birla Institute of Technology (BIT) Mesra, Ranchi**.  

---

## Features  

- **Automated detection of Parkinson’s disease** from voice recordings  

### Feature extraction using:  
- Jitter, Shimmer  
- SNR, HNR  
- Energy-based features (mean, std)  
- LPC (1–12)  
- LPCC (1–12)  
- GFCC (1–13)  
- Spectrogram-based features for CNN  

### Machine Learning models:  
- Support Vector Machine (SVM)  
- Random Forest (RF)  

### Deep Learning models:  
- Convolutional Neural Networks (CNNs)  
- LSTM / CNN-LSTM hybrid for temporal modeling  

### Evaluation metrics:  
- Accuracy  
- Precision  
- Recall  
- F1-score  

- **Comparative analysis** between ML and DL methods for Parkinson’s detection  

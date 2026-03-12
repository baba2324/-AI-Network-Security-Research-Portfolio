🚀# 🚀 JoonYong Lee | Security & Edge AI Engineer
Building anomaly detection systems from Industrial AI to Cybersecurity and In-Vehicle Security.

🇰🇷 **Korean Version** (#korean-version)  
🇺🇸 **English Version** (#english-version)

---

# 🇰🇷 Korean Version

## 💡 About Me

저는 1학년 겨울방학 동안 순천향대학교 SW중심대학 사업단과 브레인웍스가 공동 설계한  
산업 AI 전문가 양성과정(2주, 60시간)을 통해 이상 탐지(Anomaly Detection) 기술을 학습했습니다.

이 과정에서 산업 데이터 기반 이상 탐지 기술을 바탕으로 현재는 산업 데이터 분석에서 출발하여  
사이버 보안과 차량 보안 영역까지 확장하는 연구를 진행하고 있습니다.

특히 다음과 같은 데이터 환경에서 연구를 진행했습니다.

- 산업 공정 데이터
- 네트워크 보안 로그
- 차량 CAN 통신 데이터

이를 기반으로 실시간 이상 탐지 모델을 설계하고  
Edge 환경에서도 동작 가능한 수준까지 최적화했습니다.

---

# 1️⃣ 산업 AI 전문가 과정 (BrainWorks)

### Semiconductor Process Anomaly Detection

Soonchunhyang University Industrial AI Expert Program

제조 공정 시계열 데이터를 활용하여 공정 이상을 탐지하는  
**LSTM Autoencoder 기반 모델**을 구축했습니다.

### Key Tech

- Time Series Analysis
- LSTM Autoencoder
- PyTorch

### Performance

- Recall: 0.93
- Precision: 0.89
- F1 Score: 0.91
- Accuracy: 94%

  <img width="719" height="560" alt="Semiconductor Anomaly Detection" src="https://github.com/user-attachments/assets/16fecddb-0540-4a33-bb34-ff6235679390">

### Troubleshooting

초기 모델에서 이상 데이터를 정상으로 인식하는 과적합 문제가 발생했습니다.  
이를 해결하기 위해 **L1 Regularization**을 적용하여 학습을 안정화했습니다.

---

# 2️⃣ Undergraduate Research

## Network Security Log Anomaly Detection

산업 AI 이상 탐지 기술을 네트워크 보안 로그 데이터로 확장 적용하여  
모델의 **도메인 전이(Domain Transfer)** 가능성을 검증했습니다.

### Research Focus

- Industrial AI → Cybersecurity Domain Transfer
- High-dimensional security log processing
- Robust anomaly detection

- <img width="1189" height="1190" alt="17730397607457093785105491626063" src="https://github.com/user-attachments/assets/06f2ae0a-6acb-47b3-81af-2151c7e4ae7c" />


### Key Challenges

- Memory Explosion → PCA 차원 축소
- Feature Dimension Mismatch → Zero Padding
- 데이터 불균형 문제 대응

---

# 🛡️ AI-Powered Real-Time Network Defense System

이 프로젝트는 머신러닝을 활용하여  
네트워크 트래픽을 **실시간으로 감시하고 보호하는 보안 시스템**입니다.

### Key Features

- Real-time Monitoring (0.1s packet analysis)
- ML-based intrusion detection
- Low resource usage (CPU/RAM <1%)
- One-click deployment

### Technology Stack

Language
- Python

Libraries
- Scikit-learn
- Pandas
- Scapy

Model
- Random Forest Classifier

---

# 🏆 3️⃣ AI-Car-Hacking-Detection (IDS)

### In-Vehicle CAN Bus Intrusion Detection

Korea University **HCRL Car-Hacking Dataset**을 활용하여  
차량 내부 CAN 통신 공격을 탐지하는 딥러닝 기반 IDS를 구축했습니다.

### Attack Types

- DoS
- Fuzzy
- Spoofing

### Performance

- Recall: 1.00
- Precision: 0.95
- F1 Score: 0.97
- Accuracy: 96%

500,000건 이상의 차량 통신 데이터를 대상으로 실험을 수행했습니다.


<img width="556" height="431" alt="17730396190463788999305869072441" src="https://github.com/user-attachments/assets/cee0ee65-cc93-48d3-aa91-81d8519a91fa" />



### Edge Optimization

실제 차량 환경을 고려하여 초경량 모델 구조를 설계했습니다.

MLP Architecture

```
16 → 8 → 1
```

Optimization

- Int8 Quantization
- Model Size: 0.0077MB (~7KB)

저사양 MCU 환경에서도 실행 가능한 IDS 모델 구조입니다.

---

# 🇺🇸 English Version

## About Me

I am an engineer exploring anomaly detection across multiple domains including industrial data, cybersecurity, and automotive security.

During my freshman winter break, I completed a **60-hour Industrial AI Specialist Training Program** jointly designed by the Soonchunhyang University SW-Centered Program and BrainWorks.

Building on anomaly detection techniques learned from industrial datasets, I am expanding this research toward:

- Network security log analysis
- Real-time AI network defense systems
- Automotive CAN bus intrusion detection

---

## Industrial AI Anomaly Detection

Semiconductor Process Anomaly Detection

Performance

- Accuracy: 94%
- Recall: 0.93
- F1 Score: 0.91

- 
  <img width="719" height="560" alt="Semiconductor Anomaly Detection" src="https://github.com/user-attachments/assets/16fecddb-0540-4a33-bb34-ff6235679390">

Model

- LSTM Autoencoder
- Time-series anomaly detection

---

## AI Car Hacking Detection

Dataset

Korea University HCRL Car-Hacking Dataset

Performance

- Recall: 1.00
- Accuracy: 96%
- F1 Score: 0.97

- 
<img width="556" height="431" alt="17730396190463788999305869072441" src="https://github.com/user-attachments/assets/cee0ee65-cc93-48d3-aa91-81d8519a91fa" />


Edge Optimization

- Quantized Int8 model
- Model size ~7KB
- Lightweight MLP architecture (16-8-1)

---

## Tech Stack

AI / ML

- PyTorch
- TensorFlow
- Scikit-learn
- TensorFlow Lite

Security

- CAN Protocol
- Intrusion Detection Systems
- Network Security Logs

Programming

- Python
- C / C++

## 📫 Contact & Links
- **GitHub:** [https://github.com/baba2324](https://github.com/baba2324)  
- **Research Interest:** AI Security | Industrial AI | Automotive Cybersecurity

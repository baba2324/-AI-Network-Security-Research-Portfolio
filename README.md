# 🚀 JoonYong Lee | Security & Edge AI Engineer
Building anomaly detection systems from Industrial AI to Cybersecurity and In-Vehicle Security.

🇰🇷 **Korean Version** (#korean-version)  
🇺🇸 **English Version** (#english-version)

---

# 🇰🇷 Korean Version

## 💡 About Me

저는 1학년 겨울방학 동안 순천향대학교 SW중심대학 사업단과 브레인웍스가 공동 설계한  
**산업 AI 전문가 양성과정 (2주, 60시간)** 을 통해 이상 탐지(Anomaly Detection) 기술을 학습했습니다.

이 과정에서 산업 데이터 기반 이상 탐지 기술을 바탕으로  
현재는 **산업 데이터 분석에서 출발하여 사이버 보안과 차량 보안 영역까지 확장하는 연구**를 진행하고 있습니다.

특히 다음과 같은 데이터 환경에서 연구를 진행했습니다.

- 산업 공정 데이터
- 네트워크 보안 로그
- 차량 CAN 통신 데이터

이를 기반으로 **실시간 이상 탐지 모델을 설계하고 Edge 환경에서도 동작 가능한 수준까지 최적화했습니다.**

---

# 1️⃣ 산업 AI 전문가 과정 (BrainWorks)

## Semiconductor Process Anomaly Detection

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

![Semiconductor Anomaly Detection]
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

![Network Log Graph] <img width="1189" height="1190" alt="17730397607457093785105491626063" src="https://github.com/user-attachments/assets/06f2ae0a-6acb-47b3-81af-2151c7e4ae7c" />



### Key Challenges

- Memory Explosion → PCA 차원 축소
- Feature Dimension Mismatch → Zero Padding
- 데이터 불균형 문제 대응

---

# 🛡️ AI-Powered Real-Time Network Defense System

**실시간 네트워크 보안 감시 체계 구축**

기존의 자동차 보안 연구를 넘어  
실제 PC 환경에서 작동하는 **실시간 지능형 방어 시스템**을 구축했습니다.

### 🚀 Key Features

**Real-time Monitoring**

- 0.1초 단위 패킷 분석
- 실시간 네트워크 트래픽 감시

**ML-based Detection**

- Random Forest 기반 침입 탐지 엔진
- 비정상 접속 및 공격 시도 탐지

**Edge Optimization**

- CPU / RAM 점유율 **1% 미만**
- 24시간 백그라운드 실행 가능

**One-click Deployment**

- 바탕화면 바로가기 실행
- 자동 실행 배치 스크립트

### 🛠 Technical Stack

Language
- Python

Libraries
- Scikit-learn
- Scapy
- Pandas

Deployment
- Desktop Integrated Defense System

---

# 🏆 3️⃣ AI-Car-Hacking-Detection (IDS)

## In-Vehicle CAN Bus Intrusion Detection

Korea University **HCRL Car-Hacking Dataset**을 활용하여  
차량 내부 CAN 통신 공격을 탐지하는 **딥러닝 기반 IDS**를 구축했습니다.

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

![Car Hacking Detection]

<img width="556" height="431" alt="17733483773706326758692551498192" src="https://github.com/user-attachments/assets/754169d4-8c65-40d6-b045-cf663377b0f5" />

## Edge Optimization

실제 차량 환경을 고려하여 **초경량 모델 구조**를 설계했습니다.

### Lightweight MLP Architecture

    16 → 8 → 1

### Optimization

- Int8 Quantization
- Model Size: **~7KB**

저사양 **MCU 환경에서도 실행 가능한 IDS 모델 구조 입니다**

### Optimization

- Int8 Quantization
- Model Size: **~7KB**

저사양 **MCU 환경에서도 실행 가능한 IDS 모델 구조**입니다.

---

# 🇺🇸 English Version

## About Me

I am an engineer exploring anomaly detection across multiple domains including **industrial data, cybersecurity, and automotive security.**

During my freshman winter break, I completed a **60-hour Industrial AI Specialist Training Program** jointly designed by the Soonchunhyang University SW-Centered Program and BrainWorks.

Building on anomaly detection techniques learned from industrial datasets, I expanded the research toward:

- Network security log analysis
- Real-time AI network defense systems
- Automotive CAN bus intrusion detection

---

# Industrial AI Anomaly Detection

## Semiconductor Process Anomaly Detection

### Performance

- Accuracy: 94%
- Recall: 0.93
- F1 Score: 0.91

![Semiconductor Anomaly Detection]
<img width="719" height="560" alt="Semiconductor Anomaly Detection" src="https://github.com/user-attachments/assets/16fecddb-0540-4a33-bb34-ff6235679390">

### Model

- LSTM Autoencoder
- Time-series anomaly detection

---

# Network Security Log Anomaly Detection

Applying anomaly detection techniques from **industrial AI to cybersecurity logs.**

### Research Focus

- Industrial AI → Cybersecurity Domain Transfer
- High-dimensional security log analysis
- Robust anomaly detection

![Network Security Graph]
<img width="1189" height="1190" alt="17730397607457093785105491626063" src="https://github.com/user-attachments/assets/06f2ae0a-6acb-47b3-81af-2151c7e4ae7c" />


---

# AI-Powered Real-Time Network Defense System

A **real-time intelligent intrusion detection system** operating directly on PC environments.

### Key Features

**Real-time Packet Monitoring**

- Packet analysis every **0.1 seconds**

**ML-based Intrusion Detection**

- Random Forest model for attack classification

**Edge Optimization**

- CPU/RAM usage **below 1%**

**One-click Deployment**

- Desktop shortcut execution

---

# AI Car Hacking Detection

Dataset  
Korea University **HCRL Car-Hacking Dataset**

### Performance

- Recall: 1.00
- Accuracy: 96%
- F1 Score: 0.97

![Car Hacking Detection] 
<img width="556" height="431" alt="17733483773706326758692551498192" src="https://github.com/user-attachments/assets/754169d4-8c65-40d6-b045-cf663377b0f5" />

## Edge Optimization

### Lightweight MLP Architecture

16 → 8 → 1

### Optimization

- Quantized Int8 model
- Model size **~7KB**

Designed for **low-resource embedded vehicle environments.**

---

# Tech Stack

### AI / ML

- PyTorch
- TensorFlow
- Scikit-learn
- TensorFlow Lite

### Security

- CAN Protocol
- Intrusion Detection Systems
- Network Security Logs

### Programming

- Python
- C / C++

---

# 📫 Contact & Links

**GitHub**  
https://github.com/baba2324

**Research Interest**  
AI Security | Industrial AI | Automotive Cybersecurity

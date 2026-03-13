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

## 🛡️ [NEW] AI-Powered Real-Time Network Defense System
**실시간 네트워크 보안 감시 체계 구축**

기존의 자동차 보안 연구를 넘어, 실제 PC 환경에서 작동하는 **실시간 지능형 방어 시스템**을 추가로 구축하였습니다.

### 🚀 Key Features
* **Real-time Monitoring:** 0.1s packet analysis (실시간 패킷 분석 및 탐지)
* **ML-based Detection:** Random Forest 기반의 고성능 침입 탐지 엔진 적용
* **Edge Optimization:** CPU/RAM 점유율 1% 미만의 저전력/고효율 설계
* **One-click Deployment:** 사용자 편의를 위한 바탕화면 원클릭 가동 시스템

### 🛠️ Technical Stack
* **Language:** Python
* **Library:** Scikit-learn, Scapy, Pandas
* **Deployment:** Desktop Integrated Defense System


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


<img width="556" height="431" alt="17733483773706326758692551498192" src="https://github.com/user-attachments/assets/754169d4-8c65-40d6-b045-cf663377b0f5" />




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

# [Core Tech] AI Deep Learning Integrated Security System
## AI 딥러닝 기반 실시간 통합 보안 시스템

### 💻 핵심 기술 (Core Technologies)

* **Real-time Traffic Analysis (실시간 트래픽 분석)**
    * 파이썬을 활용하여 네트워크 패킷을 실시간 모니터링하고 위협 요소를 즉각 식별합니다.
* **Deep Learning Model Integration (AI 모델 통합)**
    * `Keras/TensorFlow` 기반의 딥러닝 모델(`agent_defender`)을 연동하여 지능형 침입 탐지 시스템(IDS)을 구현했습니다.
* **Multi-Process Automation (멀티 프로세스 자동화)**
    * 배치 스크립트(`.bat`)를 통해 여러 보안 엔진을 동시에 기동하고 시스템 권한을 자동으로 제어합니다.

### 🚀 차별점 (Key Differentiators)
1. **Intelligence:** 단순 규칙 기반이 아닌 AI 학습 모델에 의한 패턴 인식 탐지.
2. **Stability:** 경로 인식 오류 및 권한 충돌 문제를 해결한 안정적인 시스템 환경 설계.

# [Core Tech] Windows Environment System Infrastructure Automation
## 윈도우 인프라 최적화 및 업무 자동화 시스템

### 💻 핵심 기술 (Core Technologies)

* **Process Lifecycle Management (프로세스 관리)**
    * 시스템 자원 효율화를 위한 백그라운드 프로세스 제어 및 최적화 기술.
* **Automated Deployment (자동화 배포)**
    * 환경 설정 및 종속성 문제를 원클릭으로 해결하는 자동 실행 스크립트 개발.
* **Troubleshooting (문제 해결 및 대응)**
    * 시스템 런타임 오류(Permission, Path error) 분석 및 권한 최적화 가이드 수립.

### 🚀 차별점 (Key Differentiators)
1. **Efficiency:** 복잡한 수동 작업을 자동화하여 시스템 관리 효율성 200% 증대.
2. **Reliability:** 다양한 윈도우 환경에서도 즉시 구동 가능한 이식성 확보.

# [Core Tech] Software IP Protection & Version Control
## 소프트웨어 지식재산권 보호 및 버전 관리

### 💻 핵심 기술 (Core Technologies)

* **Git-based Version Control (형상 관리)**
    * `GitHub Private Repository`를 활용하여 핵심 소스 코드의 형상 관리 및 보안 유지.
* **License Compliance (라이선스 준수)**
    * 소프트웨어 저작권 보호를 위한 라이선스 정책 적용 및 독자적 기술 자산화.
* **Security Asset Management (보안 자산 관리)**
    * 비공개 업로드와 접근 권한 제어를 통한 핵심 알고리즘 유출 방지.

### 🚀 차별점 (Key Differentiators)
1. **Professionalism:** 전문적인 버전 관리 도구를 사용한 체계적인 기술 축적.
2. **Protection:** 독자 개발한 알고리즘의 보안성을 강화한 프라이빗 자산 운영.

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

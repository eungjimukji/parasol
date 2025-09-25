# 파라솔(Parasol)
### (KDT Training Final Project)
---
<p align="center">
  <img width="300" height="600" alt="App logo" src="https://github.com/user-attachments/assets/96badb1a-0213-40f4-9ae9-52af149d9266" />
</p>

<p align="center">
  소중한 동행을 더 오래 이어주는 파라솔
</p>
<p align="center">
  <strong>Multi-Modal Digital Biomarker 기반 Parkinson's Disease(파킨슨병)의 초기 감별 AI 솔루션</strong>
</p>

<h2>🍀 Our Team</h2>

<table align="center">
  <tr>
    <th style="padding: 10px; font-size: 16px;">💡 이성현</th>
    <th style="padding: 10px; font-size: 16px;">💡 이은지</th>
    <th style="padding: 10px; font-size: 16px;">📊 신우철</th>
    <th style="padding: 10px; font-size: 16px;">📱 윤현수</th>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; font-size: 14px;"><strong>챗봇 구현 &<br> 솔루션 기획</strong></td>
    <td align="center" style="padding: 10px; font-size: 14px;"><strong>UI&UX 디자인 <br>& 솔루션 기획</strong></td>
    <td align="center" style="padding: 10px; font-size: 14px;"><strong>AI 모델링 & <br>데이터 분석</strong></td>
    <td align="center" style="padding: 10px; font-size: 14px;"><strong>앱 개발 & <br>AWS Architect</strong></td>
  </tr>
</table>


## ⚙️ 기술 스택

<table>
  <tr>
    <th align="left">개발 환경</th>
    <td>
      <img src="https://img.shields.io/badge/Python-3.9.7-3776AB?logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/Flutter-3.32.8-02569B?logo=flutter"/>
      <img src="https://img.shields.io/badge/Dart-3.8.1-0175C2?logo=dart"/>
      <img src="https://img.shields.io/badge/Android_Studio-Narwhal_3-3DDC84?logo=androidstudio"/>
    </td>
  </tr>
  <tr>
    <th align="left">백엔드</th>
    <td>
      <img src="https://img.shields.io/badge/python--multipart-0.0.9-4a4a4a"/>
      <img src="https://img.shields.io/badge/Pydantic-2.7.4-005571?logo=pydantic"/>
    </td>
  </tr>
  <tr>
    <th align="left">Data Preprocessing / ML</th>
    <td>
      <!-- Server side (requirements.txt) -->
      <img src="https://img.shields.io/badge/Pandas-2.2.2-150458?logo=pandas&logoColor=white"/>
      <img src="https://img.shields.io/badge/NumPy-1.26.4-013243?logo=numpy&logoColor=white"/>
      <img src="https://img.shields.io/badge/SciPy-1.13.1-8CAAE6?logo=scipy&logoColor=white"/>
      <img src="https://img.shields.io/badge/scikit--learn-1.5.1-F7931E?logo=scikitlearn"/>
      <img src="https://img.shields.io/badge/PyTorch-2.3.1-ee4c2c?logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/librosa-0.10.2.post1-1A1A1A"/>
      <img src="https://img.shields.io/badge/SoundFile-0.12.1-1A1A1A"/>
      <!-- Lambda (PROJECT_REQUIREMENTS.md) -->
      <img src="https://img.shields.io/badge/PyTorch(Lambda)-2.1.0-ee4c2c?logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/torchaudio-2.1.0-1A1A1A"/>
      <img src="https://img.shields.io/badge/librosa(Lambda)-0.10.1-1A1A1A"/>
      <img src="https://img.shields.io/badge/SoundFile(Lambda)-1.0.0-1A1A1A"/>
      <img src="https://img.shields.io/badge/scikit--learn(Lambda)-1.3.0-F7931E?logo=scikitlearn"/>
    </td>
  </tr>
  <tr>
    <th align="left">클라우드 / DB</th>
    <td>
      <img src="https://img.shields.io/badge/Firebase_Admin-6.5.0-FFCA28?logo=firebase"/>
      <img src="https://img.shields.io/badge/boto3-%3E%3D1.34.0-232F3E?logo=awslambda&logoColor=white"/>
      <img src="https://img.shields.io/badge/botocore-%3E%3D1.34.0-232F3E?logo=amazonaws&logoColor=white"/>
      <img src="https://img.shields.io/badge/Requests-%3E%3D2.31.0-4A4A4A"/>
    </td>
  </tr>
  <tr>
  <th align="left">컴퓨터 비전</th>
    <td>
      <img src="https://img.shields.io/badge/OpenCV(headless)-4.9.0.80-5C3EE8?logo=opencv&logoColor=white"/>
      <img src="https://img.shields.io/badge/MediaPipe-0.10.7-1A73E8?logo=google&logoColor=white"/>
      <!-- Lambda alt versions -->
      <img src="https://img.shields.io/badge/OpenCV(headless)(Lambda)-4.8.1.78-5C3EE8?logo=opencv&logoColor=white"/>
      <img src="https://img.shields.io/badge/Pillow-%3E%3D10.0.1-1A1A1A"/>
    </td>
  </tr>
</table>

## ✨ 프로젝트 주요 기능

### 🔍 주요 바이오마커
> 특발성 파킨슨병(PD), 비정형 파킨슨병(PSP, MSA), 정상(HC)을 구분할 수 있는 마커 입니다.<br>
> 시선 추적(PSP), 손가락 부딪치기(PD), 소리내기(MSA) 기준으로 탐색할 수 있어요.
<div align="center">

<table>
  <tr>
    <th align="center">시선 추적</th>
    <th align="center">손가락 부딪치기</th>
    <th align="center">소리내기</th>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/53fb25bf-cd5c-4f9b-9227-1fe31160ecc9" width="200"/>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/30e747c4-f72d-4be8-b7ef-9aec7a950128" width="200"/>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/ee3ddd03-e118-434d-997f-890023787297" width="200"/>
    </td>
  </tr>
</table>

</div>

### 🧪 결과 보고서 & 아파닥
> 모든 측정 결과를 고려한 결과 보고서를 제공 받고<br>
> RAG(Retrieval-Augmented Generation)기반 파킨슨병(비정형 파킨슨병) 특화 챗봇과 함께 해보세요!
<div align="center">

<table>
  <tr>
    <th align="center">최종 위험도 보고서</th>
    <th align="center">아파닥</th>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/2f0aba69-e079-4607-9970-8fb5d26cfdee" width="200"/>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/8f96d860-7ba2-4e8e-8db3-a09397b0dd8d" width="200"/>
    </td>
  </tr>
</table>

</div>

## ☁️AWS Cloud Architecture
<p align="center">
  <img width="700" height="862" alt="architecture-diagram" src="https://github.com/user-attachments/assets/cb17e6c7-6a5b-4731-bf0e-38564dcc1af6" />
</p>

> App에서 제공하는 모든 핵심 기능은 **AWS cloud platform** 을 사용했습니다.  
 - 시선 추적, 손가락 부딪치기, 음성 분석 데이터 수집은 **AWS Lambda**를 활용했습니다.
 - 로그인, 데이터 저장, 모델 적용은 **AWS SQS**를 통해 수행합니다.
 - 수집된 데이터(음성, 손가락 부딪치기, 시선 추적) 및 결과 보고서는 **DynamoDB**에 저장되어 관리됩니다.
   
> 앱은 **Flutter + Dart**로 개발되어 사용자 인터페이스를 담당합니다.

## 🔧 파킨슨 멀티모달 파이프라인
<p align="center">
  <img width="700" height="862" alt="architecture-diagram" src="https://github.com/user-attachments/assets/f8f5bbda-2f2f-4a24-a2b2-cb33c6f9ffe8" />
</p>

> 파킨슨병의 정확한 분류를 위해 **3개의 핵심 Feature를 모두 고려하여 분류**합니다.  
 - 시선 추적, 손가락 부딪치기 데이터 수집 및 추출에는 **Mediapipe** 라이브러리를 활용했습니다.
 - 음성 분석 모델은 3개의 Machine Learning 모델 구조를 병합한 Multi-Branch Model 구조입니다.

## 🛠️ We Work

### 👀 수직 안구 운동 모델 구현 (Vertical Oculomotor)
> PSP 조기 감별 핵심 바이오마커: **수직 속도 저하**와 **수직 이동 범위 감소**

<p align="center">
  <img src="docs/img/eye_pipeline.png" alt="Vertical eye movement pipeline" width="720">
</p>

**입력**
- 스마트폰 전면 카메라 동영상(.mp4), 정면 자세에서 **상↔하** 시선 전환 5회

**처리 파이프라인**
1) MediaPipe Face Mesh → **홍채 좌표(LEFT/RIGHT IRIS)** 추출  
2) 눈높이 정규화: `v_offset_norm = (iy - cy) / eye_height`  
3) 잡음 정리(Q1~Q3 IQR 클리핑, blinks 제외), 윈도잉  
4) 핵심 지표 계산  
   - **수직 peak-to-peak 범위 (vPP)**: vertical peak-to-peak  
   - **평균 수직 속도 (deg/s)**, **평균 수평 속도 (deg/s)**  
   - **blink rate**, **latency(ms)**  
5) 룰+모델 혼합 판정  
   - `vPP < θ_vpp` 또는 `mean_v_deg < θ_v` → PSP 의심  
   - 보조 분류기(로지스틱/LightGBM): [vPP, v_deg, h_deg, latency, blink] → (HC vs PSP)

---

### ✋ 손가락 부딪치기 모델 구현 (Finger Tapping)
> 브래디키네시아 정량화: **속도, 진폭, 리듬 안정성, 감쇠(decrement), 주저/중단**

<p align="center">
  <img src="docs/img/finger_pipeline.png" alt="Finger tapping pipeline" width="720">
</p>

**입력**
- 스마트폰 후면/전면 카메라 동영상, **엄지-검지 탭 10회** (좌/우 손 각각)

**특징 추출 (MediaPipe Hands)**
- 거리 시계열 `d(t) = ||thumb_tip - index_tip||`
- 파생 지표:
  - **Amplitude(mean/var, slopes, decrement)**  
  - **Velocity(mean/var, slopes)**  
  - **Frequency(taps/s), Peaks(count)**  
  - **Halts & Hesitations(#)**  
  - **Rhythm stability(Period var)**  

**모델**
- 전처리: 표준화(StandardScaler) + 범주형(손/측) 원-핫
- 학습: LightGBM / AdaBoost / CNN-GRU(시계열)
- 출력:
  - (1) **이진/다중 분류**: HC vs PD (or UPDRS 0–3+)  
  - (2) **스코어 회귀**: 예측 UPDRS(3.4) 점수

---

### 🔊 음성 모델 구현
- CNN + BiGRU + MLP를 결합한 **Multi-Branch Model**로 구현했습니다.  
- **CNN Branch**: 시간-주파수 영역의 스펙트로그램 패턴을 학습  
- **BiGRU Branch**: 발성 주기의 흐름을 양방향으로 요약해 시계열적 특성을 포착  
- **MLP Branch**: 피치, 에너지 등 요약 통계적 특성을 보완적으로 활용  
- 세 가지 브랜치가 **공간 패턴, 시간 동역학, 통계 지표**라는 서로 다른 단서를 학습하여 단일 브랜치 모델 대비 **견고성과 분별력**이 향상됩니다.  
- 최종 출력은 **2-Layer MLP 분류 헤드**를 통해 **2가지 유형(HC, MSA)**으로 분류합니다.  

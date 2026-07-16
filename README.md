# 👋 Hello, I'm a Deep Learning Developer!

> **"이론을 코드로 증명하며, 컴퓨터 비전을 탐구합니다."**

<br>

## 🛠 Tech Stacks

### 💻 Languages
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=C%2B%2B&logoColor=white"/>

### 🧠 Deep Learning & Engines
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/> <img src="https://img.shields.io/badge/Unity-FFFFFF?style=flat-square&logo=Unity&logoColor=black"/> <img src="https://img.shields.io/badge/Open3D-5DADE2?style=flat-square&logo=Open3D&logoColor=white"/>

### 🔧 Tools
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/>

<br>

---

## 🚀 Featured Projects

### 👁️ [MonoMirror](https://github.com/nanasin120/MonoMirror) `진행 중`
* **한 줄 설명:** 자기지도학습(Self-Supervised Learning) 방식을 이용한 3D Point Cloud 생성 모델
* **핵심 구현:** * `ResNet-18` 아키텍처를 인코더로 커스텀하여 비지도 구조에서 Depth 및 Pose 추정 메커니즘 설계
* **Tech Stack:** `Python`, `PyTorch`, `Open3D`

<br>

### 🖼️ [EdgeTraceNet](https://github.com/nanasin120/EdgeTraceNet) `완료`
* **한 줄 설명:** 픽셀간의 연결성을 이용해 윤곽선을 추론하는 자기지도학습 모델
* **핵심 구현:** `ResNet-18`을 백본으로 채택, 인접 픽셀(오른쪽/아래쪽) 간의 픽셀 관계성(Relationship Estimation) 파악을 통한 정밀 윤곽선 추출 구조 구현
* **Tech Stack:** `Python`, `PyTorch`
* **Preview:**
  
  <img width="1292" height="1300" alt="ezgif com-gif-maker" src="https://github.com/user-attachments/assets/d033fe67-63b3-4b15-add3-b7cc19cb9bcc" />

| Method / Stage | Best Threshold | Precision | Recall | F1-Score |
| :--- | :---: | :---: | :---: |  :---: |
| **EdgeTraceNet (Initial)** | 0.1 | 0.0187 | 1.000 | 0.0367 |
| **EdgeTraceNet (100)** | 0.9 | 0.0466 | 0.2118 | 0.0764 |
| **EdgeTraceNet (200)** | 0.9 | 0.0591 | 0.1834 | 0.0894 |
| **EdgeTraceNet (300)** | 0.9 | 0.0547 | 0.1899 | 0.0849 |
| **EdgeTraceNet (400)** | 0.9 | 0.0526 | 0.1943 | 0.0828 |
| **EdgeTraceNet (500)** | 0.9 | 0.0531 | 0.1929 | 0.0833 |

<br>

---

## 📚 Paper Study & Re-implementation

<details>
<summary><b>🔥 클릭하여 논문 구현 및 연구 리포지토리 보기</b></summary>
<br>

| Category | Repository | Description |
| :--- | :--- | :--- |
| **Paper Archiving** | 📄 [Deep Learning Paper Study](https://github.com/nanasin120/Deep-Learning-Paper-Study/blob/main/README.md) | 주요 딥러닝 논문 분석 및 핵심 요약 아카이빙 |
| **CNN Basics** | 🧠 [LeNet-5-Pytorch](https://github.com/nanasin120/LeNet5-Pytorch-) | CNN의 시초인 LeNet-5 구조 PyTorch 재구현 |
| **CNN Basics** | 🧠 [VGGNet-Pytorch](https://github.com/nanasin120/VGGNet-Pytorch) | 3x3 필터를 깊게 쌓은 VGGNet 아키텍처 분석 및 구현 |
| **Self-Supervised** | 👁️ [Monodepth2](https://github.com/nanasin120/Monodepth2) | 단안 카메라 기반 자기지도 딥스 추정 모델 연구 |
| **Self-Supervised** | 👁️ [CroCo](https://github.com/nanasin120/CroCo) | Cross-view Completion 기반 3D 비전 프리트레이닝 연구 |
| **3D & BEV** | 🚗 [3D Voxel Map VoxFormer](https://github.com/nanasin120/3D_Voxel_Map_VoxFormer) | 트랜스포머 기반 3D 복셀 시맨틱 세그멘테이션 분석 |
| **3D & BEV** | 🚗 [BEV-LSS-UNITY-PYTORCH](https://github.com/nanasin120/BEV-LSS-UNITY-PYTORCH) | Lift-Splat-Shoot 기반 뷰 변환 엔진 및 Unity 연동 탐구 |

</details>

<br>

---
## 📈 GitHub Stats
[![](-stats.svg?username=nanasin120&show_icons=true&theme=transparent)](https://github.com/anuraghazra/github-readme-stats)

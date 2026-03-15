# 🛒 Intelligent Cart (지능형 쇼핑카트)

> **AI와 IoT 기술을 활용하여 사용자에게 편리한 쇼핑 경험을 제공하는 지능형 쇼핑카트 시스템입니다.**
## 📺 프로젝트 데모 영상 (Demo Video)

[![Intelligent Cart Demo](https://img.youtube.com/vi/x8mPJWkbGpA/0.jpg)](https://www.youtube.com/watch?v=x8mPJWkbGpA)

*위 이미지를 클릭하면 유튜브 채널로 이동하여 시연 영상을 확인하실 수 있습니다.*
---

## 🌟 주요 기능 (Key Features)

* **자동 상품 인식:** 카메라 및 컴퓨터 비전(OpenCV/YOLO 등)을 활용해 카트에 담긴 물건을 실시간으로 인식합니다.
* **실시간 결제 금액 확인:** 담긴 상품의 가격을 합산하여 디스플레이에 실시간으로 표시합니다.
* **자동 경로 안내:** 마트 내 지도를 기반으로 원하는 품목의 위치까지 최적의 경로를 안내합니다. (기능이 있다면 유지)
* **무인 결제 시스템:** 카트 내에서 직접 결제까지 완료하여 대기 줄 없는 쇼핑을 지원합니다.

## 🛠 기술 스택 (Tech Stack)

### Hardware
* Raspberry Pi / Arduino / Jetson Nano
* Web cam, Motor, Barcode scanner

### Software & AI
* **Language:** Python / C++ / Android Studio
* **Framework:** TensorFlow / PyTorch / OpenCV / ROS
* **Database:** Firebase / MySQL (데이터 관리)

### App/Web (선택 사항)
* React Native / Flutter / Web Dashboard

## 🚀 시작하기 (Getting Started)

### 설치 방법
```bash
git clone [https://github.com/alswns4878/intelligentCart.git](https://github.com/alswns4878/intelligentCart.git)
cd intelligentCart
# 필요한 패키지 설치
pip install -r requirements.txt

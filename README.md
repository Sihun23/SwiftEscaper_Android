# 🚀 SwiftEscaper: 지능형 운전자 안전 탈출 시스템

SwiftEscaper는 **터널 및 지하차도 내에서 사고 감지 및 신속한 대응을 지원하는 시스템**입니다.  
BLE 비콘과 GPS 기반의 **GIPS(복합 위치 측위 시스템)**을 적용하여 **실시간 사고 감지 및 알림**을 제공합니다.

---

## 📌 프로젝트 개요
- **프로젝트명**: SwiftEscaper
- **개발 목적**: 터널 및 지하차도에서 사고 발생 시, **신속한 감지 및 대응을 통해 인명 피해 최소화**
- **핵심 기술**:
  - **GIPS(Beacon + GPS 기반 위치 측위)**  
  - **WebSocket 기반 실시간 사고 알림 시스템**  
  - **위치 기반 사용자 필터링 및 맞춤형 경고 메시지**  
  - **Firebase Cloud Messaging(FCM) 푸시 알림 서비스**  

---

# 📱 SwiftEscaper Android Application
### 📲 **모바일 애플리케이션 개요**
- **Android 기반 실시간 사고 감지 및 경고 시스템**  
- **BLE 비콘 및 GPS를 활용한 위치 측위(GIPS)**  
- **WebSocket을 통한 실시간 사고 정보 수신**  
- **위치별 사용자 필터링 및 맞춤형 알림 메시지 제공**  

### 🔥 **주요 기능**
1️⃣ **GIPS: 복합 위치 측위 시스템 (GPS + BLE 비콘)**  
- **터널 내부**: BLE 비콘 신호를 활용한 실내 측위  
- **터널 외부**: GPS 신호를 활용한 위치 추적  
- **자동 전환**: GPS가 끊기면 BLE 비콘 기반 측위로 자동 변경  

2️⃣ **WebSocket을 활용한 실시간 사고 정보 수신**  
- **서버와 지속적인 WebSocket 연결 유지**  
- **사고 발생 시 즉각적인 데이터 수신 및 UI 반영**  
- **FCM 푸시 알림과 WebSocket 알림을 조합하여 제공**  

3️⃣ **위치 기반 사용자 필터링 및 맞춤형 알림 메시지**  
- **사고 위치를 기준으로 사용자 그룹화**  
- 사용자 위치에 따라 **다른 알림 메시지 제공**  
  - ✅ **터널 내부 사용자**: 긴급 알림(진동, 팝업, 음성 안내)  
  - ✅ **터널 외부 사용자**: 우회 경로 추천 및 사고 발생 알림  

4️⃣ **사용자 맞춤 알림 설정**  
- 🔔 **푸시 알림 (Notification)**  
- 📢 **음성 안내** (Text-to-Speech 활용)  
- 💬 **앱 내 팝업 메시지**  

---

## 🔩 **Android 기술 스택**
### **Android 개발**
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)

### **위치 서비스**
![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=google-maps&logoColor=white)

### **실시간 통신**
![WebSocket](https://img.shields.io/badge/WebSocket-000000?style=for-the-badge&logo=websocket&logoColor=white)
![FCM](https://img.shields.io/badge/FCM-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)

---

## 📆 **업데이트 계획**
✔ **GIPS(위치 측위) 개선 및 비콘 신호 최적화**  
✔ **WebSocket 최적화 (데이터 송수신 속도 개선)**  
✔ **알림 시스템 고도화 (위치별 맞춤 알림 기능 추가)**  
✔ **UI/UX 개선 (사용자 피드백 반영)**  



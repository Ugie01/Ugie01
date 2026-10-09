# 이명욱 / Lee Myungwook

**Robot Software Engineer**

직접 구현한 기능이 실제 환경에서 안정적으로 동작하는 것까지 확인하는 개발을 중요하게 생각합니다.

STM32 펌웨어와 센서 및 모터 제어부터 ROS 2 기반 로봇 SW와 다중 로봇 통신까지 경험하며, **하드웨어와 소프트웨어를 연결하고 실제 구현 과정에서 발생하는 문제를 해결해 왔습니다.**

새로운 기술을 단순히 적용하는 데 그치지 않고, 필요한 기술을 이해하고 연결해 하나의 동작하는 시스템으로 완성해 나가고 있습니다.


- Portfolio: [ugie01.github.io](https://ugie01.github.io/)
---

## 👤 Profile

| 기간 | 활동 | 주요 내용 |
| --- | --- | --- |
| 2026.04 ~ 2026.11 | **대한상공회의소 서울기술교육센터** | AI 융합 로봇 SW 개발자 과정 3기 |
| 2025.02 ~ 2026.02 | **인덕대학교 정보통신공학과 전공심화** | 학사 졸업 |
| 2020.02 ~ 2025.02 | **인덕대학교 컴퓨터전자공학과** | 전문학사 졸업 |


---

## 🛠 Tech Stack

### Languages

![C/C++](https://img.shields.io/badge/C%20%2F%20C%2B%2B-5A3B2E?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-5A3B2E?style=flat-square&logo=python&logoColor=white)

### Robot Software

![ROS 2](https://img.shields.io/badge/ROS%202-Humble%20%2F%20Jazzy-46342C?style=flat-square&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/Nav2-46342C?style=flat-square)
![SLAM Toolbox](https://img.shields.io/badge/SLAM%20Toolbox-46342C?style=flat-square)

### Communication

![Zenoh](https://img.shields.io/badge/Zenoh-A55A35?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-A55A35?style=flat-square&logo=mqtt&logoColor=white)
![Bluetooth](https://img.shields.io/badge/Bluetooth-A55A35?style=flat-square&logo=bluetooth&logoColor=white)

### Embedded & Control

![STM32](https://img.shields.io/badge/STM32-F407%20%2F%20H743-8D4A2F?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-8D4A2F?style=flat-square&logo=freertos&logoColor=white)
![Motor Control](https://img.shields.io/badge/Motor%20Control-8D4A2F?style=flat-square)
![PWM](https://img.shields.io/badge/PWM-8D4A2F?style=flat-square)
![PID](https://img.shields.io/badge/PID-8D4A2F?style=flat-square)

![UART](https://img.shields.io/badge/UART-8D4A2F?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-8D4A2F?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-8D4A2F?style=flat-square)
![DMA / Interrupt](https://img.shields.io/badge/DMA%20%2F%20Interrupt-8D4A2F?style=flat-square)

### Sensor & Vision

![IMU](https://img.shields.io/badge/IMU-6F5747?style=flat-square)
![GPS](https://img.shields.io/badge/GPS-6F5747?style=flat-square)
![2D LiDAR](https://img.shields.io/badge/2D%20LiDAR-6F5747?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-6F5747?style=flat-square&logo=opencv&logoColor=white)
![Camera Calibration](https://img.shields.io/badge/Camera%20Calibration-6F5747?style=flat-square&logo=opencv&logoColor=white)
![2D LiDAR-Camera Fusion](https://img.shields.io/badge/2D%20LiDAR--Camera%20Fusion-6F5747?style=flat-square)
![Time Synchronization](https://img.shields.io/badge/Time%20Synchronization-6F5747?style=flat-square)

### Platform & Development

![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A55A35?style=flat-square&logo=raspberrypi&logoColor=white)
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-A55A35?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-A55A35?style=flat-square&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-A55A35?style=flat-square&logo=git&logoColor=white)

### Collaboration

![Slack](https://img.shields.io/badge/Slack-5A3B2E?style=flat-square&logo=slack&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-5A3B2E?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-5A3B2E?style=flat-square&logo=confluence&logoColor=white)

---

## 📂 Projects

### [AX Multi-Robot Logistics](https://github.com/E1I6-Logistics/Logistics_FMS)

`ROS 2 Jazzy` `Zenoh` `MQTT` `Nav2` `Python`

- **개요:** Zenoh 및 MQTT를 활용해 다중 이동 로봇과 로봇팔의 작업을 연동한 물류 관제 시스템
- **기간:** 2026.09 ~ 진행 중 / 7인 팀
- **담당 역할:** FMS 백엔드 개발 및 다중 로봇 통신, 주행, 작업 흐름 연동
- **구현한 내용:** 로봇 3대 연결 상태 및 주행 명령 관리, Route Graph와 Nav2 FollowWaypoints 연동, 주문 → Pickup → ArUco 정렬 → MQTT OMX 작업 흐름 구성
- **문제 해결:** Chrony 시간 동기화와 LiDAR Scan 지연 조정, 일반 이동과 충전 도킹 조건 분리

[Portfolio 상세 보기](https://ugie01.github.io/projects/fms.html)

---

### [GoSung](https://github.com/Ugie01/GoSung)

`STM32F407` `FreeRTOS` `ROS 2 Humble` `UART` `OpenCV`

- **개요:** STM32 및 ROS 2 기반 주행 시스템을 연동한 실외 배달 로봇
- **기간:** 2024.04 ~ 2024.12 / 6인 팀
- **담당 역할:** STM32 기반 센서 처리 및 BLDC 모터 제어, ROS 2 기반 LiDAR-Camera 데이터 연동
- **구현한 내용:** IMU/GPS 수집, 홀센서 기반 속도 변화 측정, PWM 모터 제어, 초음파 비상정지, Camera Calibration 및 객체 영역 기반 LiDAR Scan 필터링
- **문제 해결:** 경사로 정지 후 밀림을 홀센서 변화로 판단해 반대 방향 PWM을 적용하는 정차 보정 로직 구현

[Portfolio 상세 보기](https://ugie01.github.io/projects/gosung.html)

---

### [AIMing Project](https://github.com/Ugie01/AIMing_Project)

`STM32H743` `FreeRTOS` `DCMI / DMA` `Edge Impulse`

- **개요:** STM32H743 단일 보드에서 카메라 입력, AI 추론, Pan/Tilt 추적을 구현한 온디바이스 AI 시스템
- **기간:** 2026.07 ~ 2026.08 / 4인 팀
- **담당 역할:** 카메라 및 AI 추론 연동, 추적 안정화, FSM 구현
- **구현한 내용:** OV2640 카메라 연동, Edge Impulse 추론 경로 적용, EMA와 Miss Tolerance 기반 좌표 안정화, Idle/Tracking/Lock-on FSM 구성
- **문제 해결:** 카메라 클럭 증가 시 영상 노이즈를 확인하고 안정적인 약 7 FPS 설정으로 조정

[Portfolio 상세 보기](https://ugie01.github.io/projects/aiming.html)

---

### [Tracking Patrol Robot](https://github.com/Ugie01/Tracking_Patrol_Robot)

`Raspberry Pi 5` `OpenCV` `Python` `Bluetooth` `Flutter`

- **개요:** Pose 기반 상황 판단 및 대상 재식별, 추적 기능을 연동한 순찰 로봇
- **기간:** 2026.05 / 4인 팀
- **담당 역할:** Pose 기반 상황 판단, 대상 재식별 및 추적 제어, 모바일 연동 구현
- **구현한 내용:** Pose 기반 위험 및 낙상 의심 판단, Bounding Box 기반 추적 제어, 색상 히스토그램 기반 재식별, Flutter 수동 제어 및 PID 게인 설정
- **문제 해결:** 대상 유실 후 재등장 시 색상 히스토그램을 비교해 기존 대상을 다시 식별하는 로직 적용

[Portfolio 상세 보기](https://ugie01.github.io/projects/tracking.html)

---

### [VIP Wearable](https://github.com/Ugie01/2026ESWContest_free_VIPWEARABLE)

`Raspberry Pi 5` `IMU` `Bluetooth Classic` `TMAP API` `Android Java`

- **개요:** TMAP 경로 안내 및 IMU 방향 정보를 진동으로 전달하는 보행 보조 시스템
- **기간:** 2026.07 ~ 2026.08 / 2인 팀
- **담당 역할:** IMU 방향 정보, 진동 피드백, Android 앱 기능 통합
- **구현한 내용:** IMU Yaw 처리, TMAP 경로 기반 방향 판단, 좌우 진동 패턴 제어, Android 앱과 Raspberry Pi 통신 연동
- **문제 해결:** BLE 연결 불안정으로 Bluetooth Classic 방식으로 변경하고 Raspberry Pi 직접 제어 구조로 단순화

[Portfolio 상세 보기](https://ugie01.github.io/projects/vip.html)

---

### [MPS 창고 적재 제어](https://ugie01.github.io/projects/plc.html)

`Mitsubishi PLC` `GX Works2` `GT Designer3` `Ladder` `HMI`

- **개요:** Mitsubishi PLC 및 HMI로 층별 적재, 비우기, 수동 운전을 구현한 교육 프로젝트
- **기간:** 2026.06 / 2인 팀
- **담당 역할:** PLC 시퀀스, HMI 제어 공동 구현
- **구현한 내용:** 층별 적재 및 비우기 시퀀스, 수동 제어, 인터록, HMI 상태 표시 구현
- **문제 해결:** 서보 리셋 직후 동작 실패와 Ladder 접점 논리 오류를 확인해 대기 시간 및 접점 배치 수정

---

## 🔬 Technical Experiments & Prototypes

### [SensorFusion](https://github.com/Ugie01/SensorFusion)

`ROS 2 Humble` `Camera` `2D LiDAR` `YOLOv5` `OpenCV`

- Camera Calibration 및 내부/외부 파라미터 적용
- ROS 2 `message_filters` 기반 Camera-LiDAR 시간 동기화
- YOLOv5 Bounding Box와 LiDAR 거리 정보 연동
- 2D LiDAR 데이터를 Camera 이미지 좌표계로 투영

### [ROS2 Controller](https://github.com/Ugie01/ROS2_Controller)

`ROS 2 Jazzy` `Android` `Camera` `2D LiDAR`

- Android에서 ROS 2 Camera 영상 및 LiDAR 정보 시각화
- 이동 명령 입력 및 로봇 제어 인터페이스 구성

---

## 🏅 Awards

| 수상일 | 수상 내용 | 주관 기관 |
| --- | --- | --- |
| 2024.12.12 | 캡스톤디자인 경진대회 **우수상** | 인덕대학교 산학협력단 |
| 2024.12.04 | 한이음 ICT 멘토링 **입선** | 한국정보산업연합회 |
| 2024.11.29 | 제22회 임베디드 소프트웨어 경진대회 자율주행 레이싱 부문 **최우수상** | AWS Public Edutech |
| 2024.09.12 | 대학 창업동아리 경진대회 **장려상** | 서울캠퍼스타운 |
| 2023.12.22 | 2023 인덕 창업경진대회 **최우수상** | 인덕대학교 창업지원단 |

---

## 🔗 More

프로젝트별 시스템 구성, 구현 과정, 문제 해결 및 결과는 포트폴리오에서 자세히 확인할 수 있습니다.

**[프로젝트 구현 내용 자세히 보기 →](https://ugie01.github.io/#projects)**
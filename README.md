# 이명욱 / Lee Myungwook

**Robot Software / Embedded Engineer**

직접 구현한 기능이 실제 환경에서 안정적으로 동작하는 것까지 확인하는 개발을 중요하게 생각합니다.

STM32 펌웨어와 센서 및 모터 제어부터 ROS 2 기반 로봇 SW와 다중 로봇 통신까지 경험하며, **하드웨어와 소프트웨어를 연결하고 실제 구현 과정에서 발생하는 문제를 해결해 왔습니다.**

새로운 기술을 단순히 적용하는 데 그치지 않고, 필요한 기술을 이해하고 연결해 하나의 동작하는 시스템으로 완성해 나가고 있습니다.


- Portfolio: [ugie01.github.io](https://ugie01.github.io/)
- GitHub: [@Ugie01](https://github.com/Ugie01)

---

## 👤 Profile

| 기간 | 활동 | 주요 내용 |
| --- | --- | --- |
| 2026.04 ~ 2026.11 (진행 중) | **대한상공회의소 서울기술교육센터** | AI 융합 로봇 SW 개발자 과정 3기 |
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

### Sensors & Perception

![IMU](https://img.shields.io/badge/IMU-6F5747?style=flat-square)
![GPS](https://img.shields.io/badge/GPS-6F5747?style=flat-square)
![2D LiDAR](https://img.shields.io/badge/2D%20LiDAR-6F5747?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-6F5747?style=flat-square&logo=opencv&logoColor=white)
![Camera Calibration](https://img.shields.io/badge/Camera%20Calibration-6F5747?style=flat-square&logo=opencv&logoColor=white)
![2D LiDAR-Camera Fusion](https://img.shields.io/badge/2D%20LiDAR--Camera%20Fusion-6F5747?style=flat-square)
![Time Synchronization](https://img.shields.io/badge/Time%20Synchronization-6F5747?style=flat-square)

### Platform & Development

![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A55A35?style=flat-square&logo=raspberrypi&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-A55A35?style=flat-square&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-A55A35?style=flat-square&logo=git&logoColor=white)
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-A55A35?style=flat-square&logo=stmicroelectronics&logoColor=white)

### Collaboration

![Slack](https://img.shields.io/badge/Slack-5A3B2E?style=flat-square&logo=slack&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-5A3B2E?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-5A3B2E?style=flat-square&logo=confluence&logoColor=white)

---

## 📂 Projects

### [AX Logistics MultiBot — 다중 로봇 FMS](https://github.com/E1I6-Logistics/Logistics_FMS/tree/ugie-fms)

`ROS 2 Jazzy` `Zenoh` `Nav2` `Python`

- **개요:** 여러 로봇의 상태를 수집하고 목적지 및 제어 명령을 전달하는 물류센터 멀티로봇 관제 시스템
- **기간:** 2026.04 ~ 진행 중 / 7인 팀
- **담당:** FMS Backend / Robot Communication
- **통신 구조:** FMS ↔ Zenoh ↔ ROS 2 로봇 간 상태·목적지·제어 명령 인터페이스 구성
- **환경 구축:** 메인 PC와 TurtleBot별 ROS 2 Jazzy, Nav2, Zenoh 실행 환경을 구성하고 실제 로봇 연동
- **테스트 환경:** 실제 로봇과 독립적으로 FMS 기능을 검증할 수 있도록 Mock Robot 및 Mock Fleet 환경 구성
- **문제 해결:** ROS 2 Discovery와 Zenoh 연결 상태를 분리하여 추적하고 PC ↔ Robot 간 통신 경로 및 실시간 상태 연동 문제 점검
- **현재 진행:** 다중 로봇 상태 관리 및 관제 연동을 구현 중이며 자동 배차·교통 관리 및 VLM 기반 판단 기능은 단계적으로 개발 중

---

### [GoSung — 실외 자율주행 배달 로봇](https://github.com/Ugie01/GoSung)

`STM32F407` `FreeRTOS` `ROS 2 Humble` `2D LiDAR` `Camera`

- **개요:** STM32 기반 센서·구동 제어와 ROS 2 기반 인식 및 로봇 SW를 통합한 실외 배달 로봇
- **기간:** 2024.04 ~ 2024.12 / 6인 팀
- **담당:** STM32 센서·구동 펌웨어 및 ROS 2 센서 연동
- **Embedded:** IMU/GPS UART 파싱, Hall Sensor 기반 속도 측정, PWM 기반 모터 제어, 초음파 비상정지 로직 구현
- **ROS 2 연동:** STM32 센서 데이터를 수신·파싱하는 Serial Node를 구현하고 ROS 2 Topic으로 변환하여 로봇 시스템에 연동
- **Perception:** Camera Calibration을 수행하고, YOLOv5 Bounding Box와 2D LiDAR 거리 데이터를 매칭하는 센서 연계 방식 실험
- **문제 해결:** 경사로 정지 후 발생하는 미끄러짐을 Hall Sensor 변화로 판단하여 역방향 PWM을 인가하는 보정 로직 구현
- **검증 결과:** Hall Sensor 기반 경사로 정지 보정 로직을 실제 로봇에 적용했으며, 속도 정확도의 정량 검증과 급가속·외력에 대한 오인식 분리는 후속 과제로 남음

---

### [AIMing Project — 온디바이스 AI 추론 및 제어](https://github.com/Ugie01/AIMing_Project)

`STM32H743` `FreeRTOS` `DCMI / DMA` `Edge Impulse`

- **개요:** STM32H743에서 카메라 입력과 AI 추론 결과를 Pan/Tilt 제어까지 연결한 임베디드 AI 프로젝트
- **기간:** 2026.07.23 ~ 2026.08.04 / 4인 팀
- **담당:** Camera AI 추론 연동 / Pan, Tilt 제어 / 시스템 통합
- **Camera:** OV2640 카메라와 DCMI/DMA를 연동하여 이미지 프레임 수집 및 AI 입력 데이터 변환
- **FreeRTOS:** Vision과 Motor 기능을 태스크 단위로 분리하여 카메라 처리와 추적 제어 구조 구성
- **Control:** 객체 추론 결과를 Pan/Tilt 모터 제어로 연결하여 대상 추적 시스템 통합
- **문제 해결:** 카메라 클럭 증가 시 영상 노이즈가 발생하는 현상을 분석하고 안정성과 FPS 간 관계를 확인하여 안정적인 설정으로 복귀
- **협업 범위:** 카메라, 펌웨어, 제어 및 시스템 통합을 담당했으며 AI 모델 학습은 팀원이 담당

---

### [Tracking Patrol Robot — 대상 추적 순찰 로봇](https://github.com/Ugie01/Tracking_Patrol_Robot)

`STM32F407` `Raspberry Pi 5` `Python` `Computer Vision`

- **개요:** Raspberry Pi의 객체 인식 결과를 STM32 기반 모바일 로봇 주행 제어와 연결한 대상 추적 순찰 로봇
- **기간:** 2026.05.11 ~ 2026.05.21 / 4인 팀
- **담당:** Vision 기반 대상 선택 및 Tracking Logic
- **Perception:** Pose와 Bounding Box 정보를 이용하여 추적 대상 선택 및 목표 방향 계산
- **Tracking:** 대상 유실 시 주변을 탐색하고 다시 검출된 대상의 특징을 비교하여 재식별하는 로직 구성
- **시스템 연동:** Raspberry Pi에서 계산한 추적 결과를 STM32 주행 명령으로 연결하여 실제 로봇 제어
- **협업 범위:** STM32 펌웨어와 IMU Yaw 기반 PID 구현 일부를 지원했으며 해당 부분의 주 구현은 팀원이 담당

---

### [VIP Wearable — 보행 보조 웨어러블](https://github.com/Ugie01/2026ESWContest_free_VIPWEARABLE)

`Raspberry Pi 5` `IMU` `Bluetooth` `Android Java`

- **개요:** 보행 경로와 주변 인식 결과를 음성 및 진동으로 전달하는 보행 보조 웨어러블 프로토타입
- **기간:** 2026.07.01 ~ 2026.08.12 / 2인 팀
- **담당:** IMU 기반 상태 판단 / Haptic Control / Raspberry Pi–Android Communication
- **Sensor:** UART로 수신한 IMU 데이터를 파싱하고 상태 변화를 이용한 3단계 낙상 감지 FSM 구현
- **Haptic:** 상황에 따라 서로 다른 진동 패턴을 출력하는 햅틱 안내 로직 구성
- **Communication:** Android와 Raspberry Pi 사이의 Bluetooth Classic  통신 구현
- **App 연동:** TMAP 기반 보행 안내 정보와 오디오 안내 기능을 시스템에 연동
- **문제 해결:** BLE 연결 안정성 문제를 확인한 뒤 Bluetooth Classic  방식으로 변경하여 통신 구조 재구성
- **협업 범위:** 센서 처리·통신·햅틱 및 앱 연동을 담당했으며 비전 모델과 AI 파이프라인은 팀원이 담당

---

### [PLC Mini Project — 창고 시퀀스 제어](https://ugie01.github.io/projects/plc.html)

`GX Works2` `Ladder Logic` `HMI`

- **개요:** MPS 교육 장비를 이용하여 창고 적재·배출 및 수동 제어 동작을 구성한 PLC 미니 프로젝트
- **기간:** 교육 과정 중 / 2인 팀
- **담당:** PLC 시퀀스 및 HMI 제어 공동 구현
- **Control:** 적재·비우기·수동 동작에 필요한 Ladder Logic과 HMI 인터페이스 구성
- **문제 해결:** 서보 리셋 직후 간헐적으로 다음 동작이 실패하는 현상을 확인하고 대기 시간을 추가하여 장치 준비 완료 후 동작하도록 수정

---

## 🔬 Technical Experiments & Prototypes

### [SensorFusion](https://github.com/Ugie01/SensorFusion)

`ROS 2 Humble` `Camera` `2D LiDAR` `YOLOv5` `OpenCV`

ROS 2 환경에서 Camera와 2D LiDAR의 시간 동기화 및 센서 데이터 연계를 실험했습니다.

- Camera Calibration 및 내부·외부 파라미터 적용
- ROS 2 `message_filters` 기반 Camera–LiDAR 시간 동기화
- YOLOv5 객체 Bounding Box와 LiDAR 거리 정보 연계
- 2D LiDAR 데이터를 Camera 이미지 좌표계로 투영하는 센서 융합 실험

### [ROS2 Controller](https://github.com/Ugie01/ROS2_Controller)

`ROS 2` `Android` `Camera` `2D LiDAR`

Android 환경에서 ROS 2 모바일 로봇의 상태를 확인하고 제어하기 위한 인터페이스를 구현했습니다.

- 로봇 Camera 영상 표시
- 2D LiDAR 정보 시각화
- Android 기반 이동 명령 입력 및 로봇 제어 인터페이스 구성

---

## 🏅 Awards

| 수상일 | 수상 내용 | 주관 기관 |
| --- | --- | --- |
| 2024.12.12 | 캡스톤디자인 경진대회 **우수상**<br>실외 자율주행 배달 로봇 v2 | 인덕대학교 산학협력단 |
| 2024.12.04 | 한이음 ICT 멘토링 **입선**<br>실외 자율주행 배달 로봇 v2 | 한국정보산업연합회 |
| 2024.11.29 | 제22회 임베디드 소프트웨어 경진대회<br>자율주행 레이싱 부문 **최우수상** | AWS Public Edutech |
| 2024.09.12 | 대학 창업동아리 경진대회 **장려상**<br>실외 자율주행 배달 로봇 v2 | 서울캠퍼스타운 |
| 2023.12.22 | 2023 인덕 창업경진대회 **최우수상**<br>실외 자율주행 배달 로봇 v1 | 인덕대학교 창업지원단 |

---

## 🔗 More

프로젝트별 시스템 구성, 구현 과정, 문제 해결 및 결과는 포트폴리오에서 자세히 확인할 수 있습니다.

**[프로젝트 구현 내용 자세히 보기 →](https://ugie01.github.io/#projects)**
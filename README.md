# Physical AI (Mobility + Agent)

MuJoCo 및 ROS 2 기반 자율주행 연구 프로젝트

## 연구 목표

가상환경에서 SLAM, Navigation, 강화학습을 연구하고 Auto Car3G 실물 자율주행 시스템으로 확장한다.

## 연구 기록

📖 Notion 연구노트: 링크 추가 예정

## 연구 단계

1. MuJoCo + ROS 2 가상환경 구축
2. SLAM 및 Navigation 구현
3. 강화학습 알고리즘 비교 실험
4. 실물 Auto Car3G 연동

## 개발 및 연구 환경

- **OS:** Windows 11 Pro / WSL2 Ubuntu 24.04.5 LTS (`Ubuntu-24.04`)
- **IDE:** Visual Studio Code (WSL)
- **프로젝트 경로:** `/home/haewon/AMR`
- **Python:** 3.12.3 (`.venv`)
- **ROS 2:** Jazzy Jalisco
- **Gazebo:** Harmonic 8.15.0
- **MuJoCo:** 3.3.7
- **PyTorch:** 2.14.1+cu130
- **Gymnasium:** 1.4.0
- **Stable-Baselines3:** 2.9.2
- **GPU:** NVIDIA RTX 5050 Laptop GPU (로컬) / NVIDIA RTX 4090 24GB (eGPU)
- **GPU 검증 (2026-11-21):** RTX 4090의 PyTorch CUDA 연산 성공; RTX 5050은 Windows 장치 오류(Code 31) 해결 후 재검증 예정

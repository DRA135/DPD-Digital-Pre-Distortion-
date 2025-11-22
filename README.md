# DPD-Digital-Pre-Distortion-
Repository for PA linearization, signal processing, and deep learning–based DPD models

# DPD & Telecom Algorithms

이 레포는 디지털 프리디스토션(DPD) 및 통신 신호처리 알고리즘 연구·개발 내용을 정리한 프로젝트입니다.  
C 기반 전통적 DPD, DNN 기반 Switching DPD, 강화학습 기반 Feature Selection, TFLite 임베디드 실험 등을 포함합니다.

## 구성
- classic_dpd: C·MATLAB 기반 기본 DPD 알고리즘
- switching_dpd_dnn: 딥러닝 기반 Switching 구조
- rl_feature_selection: DQN 기반 Feature Selection 시스템
- tflite_inference: 모델 경량화 및 C 환경 추론

## 핵심 기술
- DPD Polynomial Modeling
- TensorFlow DNN 기반 시계열 모델
- RL(DQN) Feature Selection + Action Mask
- TFLite 변환 및 임베디드 연동
- ACLR/EVM 측정 기반 성능 평가

## 실험 지표
- ACLR(Adjacent Channel Leakage Ratio)
- EVM(Error Vector Magnitude)

## 향후 개선 방향
- PA Behavioral Modeling 개선
- ONNX 기반 임베디드 통합
- 실측 기반 데이터셋 확장

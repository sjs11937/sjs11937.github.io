# Heart Failure Prediction Project
*(AI 고급프로그래밍)*

## 🔍 프로젝트 개요
본 프로젝트는 Kaggle의 'Heart Failure Prediction Dataset'을 활용하여 환자의 임상 데이터를 기반으로 심부전(Heart Failure) 발생 여부를 예측하는 머신러닝·신경망 기반 AI 예측 시스템을 구현한 프로젝트입니다.

심부전은 조기 진단이 어려우며 고령화 사회에서 발병률과 사망률이 높은 질환으로,  
데이터 분석과 인공지능을 통해 고위험 환자를 사전에 식별하는 것을 목표로 하였습니다.

---

## 🎯 프로젝트 목적
- 심부전 조기 예측을 통한 의료 의사결정 보조
- 임상 데이터 기반 질병 예측 모델 설계 경험
- 신경망 구조 및 활성화 함수 비교 분석
- AI 모델 성능 평가 및 해석 능력 향상

---

## 📊 데이터셋 정보
- Dataset: Heart Failure Prediction Dataset (Kaggle)
- 데이터 수: 918명 환자 데이터
- 입력 변수: 11개 임상 변수  
  (나이, 혈압, 콜레스테롤, 최대 심박수 등)
- 출력 변수(Target): HeartDisease (0 / 1)
- 특징: 결측치 없음 → 전처리 후 바로 학습 가능

---

## 🧠 모델 구조 및 학습
- 모델 구조  
  `Input Layer → Hidden Layer → Output Layer`
- 손실 함수: Softmax with Loss
- 학습 데이터 분할: Train / Test = 70% / 30%
- 활성화 함수 비교 실험:
  - ReLU
  - Sigmoid

---

## 📈 실험 결과 및 분석
- ReLU와 Sigmoid 활성화 함수의 성능 비교 실험 수행
- ReLU 적용 모델이
  - 학습 수렴 속도
  - 예측 안정성
  - 전체 정확도
  측면에서 더 우수한 성능을 보임
- 과적합·과소적합 개념을 고려한 모델 구조 분석 진행

---

## 🧩 사용 기술
- Python
- Numpy, Pandas
- 기본 신경망 구조 구현
- 오차 역전파(Backpropagation) 기반 학습
- Softmax 및 손실 함수 구조 이해

---

## 📄 프로젝트 문서
- Heart Failure Prediction Dataset.pdf
  - 프로젝트 배경 및 목적
  - 데이터셋 분석
  - 모델 구조 설계
  - 활성화 함수 비교 실험
  - 결과 분석 및 결론 정리

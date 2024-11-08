# 세그멘테이션 프로젝트

## 프로젝트 개요
본 프로젝트는 InSpyReNet이라는 고정밀도 세그멘테이션 네트워크를 재학습하여 차량 이미지의 배경 제거 알고리즘을 완성하는 것을 목표로 합니다. InSpyReNet은 최신 딥러닝 기술을 적용하여 복잡한 장면에서도 높은 정확도로 객체를 분리할 수 있는 세그멘테이션 모델입니다.

## 주요 기능
- **고정밀도 세그멘테이션**: 다양한 차량 이미지에서 정확하고 선명한 객체 분리 기능 제공
- **맞춤형 재학습**: 프로젝트 요구사항에 맞춘 데이터셋으로 모델을 재학습하여 최적의 성능 달성
- **자동화된 배경 제거**: 학습된 모델을 이용해 차량 이미지의 배경을 효과적으로 제거하여 투명 배경의 출력 이미지 생성

## 사용된 기술
- **딥러닝 프레임워크**: PyTorch
- **모델 아키텍처**: InSpyReNet
- **데이터셋**: 커스텀 차량 이미지 데이터셋
- **전처리**: 이미지 크기 조정, 데이터 증강 등
- **후처리**: 마스크 적용 및 이미지 합성

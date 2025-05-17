# 🏆 코스포 자동차 충돌 분석 AI 경진대회

## 📊 대회 정보
- **주최**: DACON
- **평가 지표**: Accuracy

## 🎯 프로젝트 개요
### 1. 목표
- 자동차 충돌 영상을 분석하여 충돌 유형 분류
- 딥러닝을 활용한 비디오 분류 모델 개발

### 2. 데이터
- 자동차 충돌 영상 데이터
- 충돌 유형 레이블
- 비디오 메타데이터

### 3. 접근 방법
1. **데이터 전처리**
   - 비디오 프레임 추출
   - 데이터 증강
   - 레이블 인코딩

2. **Feature Engineering**
   - 비디오 특성 추출
   - 시계열 특성 생성
   - 메타데이터 가공

3. **모델링**
   - Conv3D 모델 활용
   - PyTorchVideo 적용
   - HuggingFace 모델 활용

## 📚 프로젝트 구조
```
코스포 자동차 충돌 분석 AI경진대회/
├── [Baseline]Conv3d_video_classification.ipynb  # 베이스라인 코드
├── pytorchvideo_+ huggingface + pytorch lightning 베이스라인.ipynb  # 개선된 베이스라인
├── timm_classification.ipynb  # 최종 제출 코드
├── make_train_cap.ipynb      # 데이터 전처리 코드
└── 성현.md                   # 팀원 작업 기록
```

## 🏆 주요 성과
- 다양한 비디오 분류 모델의 성능 비교
- 효과적인 데이터 전처리 및 증강 기법 적용

## 📝 학습 내용
1. 비디오 데이터 처리
2. 딥러닝 모델링
3. 데이터 증강 기법
4. 앙상블 기법 
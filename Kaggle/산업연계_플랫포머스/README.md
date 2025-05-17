# 2021 DAPlatformers Final

## 📌 대회 정보
- **주최**: DAPlatformers
- **기간**: 2021.11.16 ~ 2021.11.16
- **주제**: 결측치가 있는 데이터셋에 대한 예측 모델 개발
- **평가 지표**: RMSE (Root Mean Square Error)

## 🎯 프로젝트 개요
결측치가 포함된 데이터셋을 분석하고, 효과적인 결측치 처리 방법을 적용하여 예측 모델을 개발하는 프로젝트입니다.

### 주요 목표
1. 결측치 패턴 분석
2. 효과적인 결측치 처리 방법 개발
3. 정확한 예측 모델 구축

## 📊 데이터
- 결측치가 포함된 특성 데이터
- 타겟 변수
- 다양한 데이터 타입 (수치형, 범주형)

## 💻 프로젝트 구조
```
산업연계_플랫포머스/
├── MissForest.ipynb        # MissForest 알고리즘 구현 및 적용
└── 1116_na피쳐 + MF.ipynb  # 결측치 특성과 MissForest 결합 모델
```

## 🔍 주요 분석 내용
1. **결측치 분석**
   - 결측치 패턴 파악
   - 결측치와 타겟 변수 간의 관계 분석
   - 결측치 특성 생성

2. **결측치 처리 방법**
   - MissForest 알고리즘 적용
   - 결측치 특성을 활용한 모델링
   - 다양한 대체 방법 비교

3. **모델 개발**
   - 결측치 처리 방법별 성능 비교
   - 앙상블 모델 구축
   - 하이퍼파라미터 최적화

## 🛠️ 사용 기술
- Python
- Pandas, NumPy
- Scikit-learn
- MissForest
- XGBoost
- Matplotlib, Seaborn

## 📈 주요 성과
1. 효과적인 결측치 처리 방법 개발
2. 결측치 특성을 활용한 모델 성능 향상
3. 다양한 결측치 처리 방법 비교 분석

## 📚 참고 자료
- [대회 페이지](https://www.kaggle.com/competitions/2021-daplatformers-final)
- [MissForest 논문](https://academic.oup.com/bioinformatics/article/28/1/112/219101)
- [Scikit-learn 문서](https://scikit-learn.org/stable/) 
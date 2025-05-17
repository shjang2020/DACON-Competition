# 🏆 문장 유형 분류 AI 경진대회

## 📊 대회 정보
- **주최**: DACON
- **평가 지표**: Accuracy
- **최종 성적**: 14등/333 (상위 4.2%)

## 🎯 프로젝트 개요
### 1. 목표
- 문장의 유형을 정확하게 분류
- 다양한 한국어 문장 유형에 대한 분류 모델 개발

### 2. 데이터
- 문장 데이터
- 문장 유형 레이블
- 한국어 자연어 데이터

### 3. 접근 방법
1. **데이터 전처리**
   - 텍스트 정제
   - 토큰화
   - 불용어 처리

2. **Feature Engineering**
   - TF-IDF 벡터화
   - 임베딩 생성
   - 문장 특성 추출

3. **모델링**
   - BERT 기반 모델 활용
   - 전이학습 적용
   - 앙상블 기법 활용

## 📚 프로젝트 구조
```
문장 유형 분류 AI 경진대회/
├── [Baseline]_TfidfVectorizer + MLP.ipynb  # 베이스라인 모델
├── Klue_베이스라인.ipynb                   # KLUE 모델 베이스라인
├── KoELECTRA[지평].ipynb                   # KoELECTRA 모델
├── klue_kobigbird[문주].ipynb              # KoBigBird 모델
├── kobert.ipynb                           # KoBERT 모델
└── NSMC.ipynb                             # NSMC 데이터 활용
```

## 🏆 주요 성과
- Accuracy 기준 상위 4.2% 달성
- 다양한 한국어 BERT 모델 활용
- 전이학습을 통한 성능 향상

## 📝 학습 내용
1. 자연어 처리 기법
2. BERT 모델 활용
3. 전이학습 방법론
4. 한국어 텍스트 분류 
# 🏆 Big-Contest

빅콘테스트 참가 기록과 코드를 정리하는 공간입니다.

## 📊 참가 대회 목록

| 번호 | 대회명 | 기간 | 성적 | 링크 |
|:---:|:---:|:---:|:---:|:---:|
| 1 | 2021 빅콘테스트 - 프로야구 배럴(Barrel)을 통한 타자 성적 예측 | 2021.09.01 ~ 2021.09.15 | - | [대회 링크](https://www.bigcontest.or.kr/points/content.php#ct04) |

## 🎯 프로젝트 개요

### 1. 프로젝트 목표
- 프로야구 타자의 배럴(Barrel) 데이터를 활용하여 타자 성적(OPS) 예측
- 타구 속도와 발사각을 기반으로 한 배럴 정의 및 분석
- 시계열 데이터를 활용한 타자 성적 예측 모델 개발

### 2. 기술 스택
- **언어**: Python
- **주요 라이브러리**: 
  - 데이터 분석: pandas, numpy
  - 시각화: matplotlib, seaborn
  - 웹 크롤링: requests, beautifulsoup4
  - 머신러닝: scikit-learn

## 📚 프로젝트 구조

```
Big-Contest/
├── POK배럴 타구 정의.ipynb        # 배럴 정의 및 분석
├── 스탯티즈 크롤링.ipynb          # STATIZ 데이터 수집
├── 시각화.ipynb                  # 데이터 시각화
├── 0914_POK모델링코드.ipynb      # 최종 모델링
└── 데이터분석_스포츠테크_P.O.K.pdf  # 최종 보고서
```

## 📝 주요 내용

### 1. 데이터 수집 및 전처리
- **제공 데이터**
  - 2018 ~ 2021 전반기 KBO 선수 및 선수코드
  - 2018 ~ 2021 전반기 타구 데이터
  - 2018 ~ 2021 전반기 KBO 선수 기록
  - 2021 경기일정 데이터

- **추가 수집 데이터**
  - STATIZ 사이트에서 2018~2021.09.13 KBO 선수 기록 크롤링
  - 크롤링 데이터 전처리 및 정제

### 2. 데이터 분석 및 시각화
- 타구 속도와 발사각에 따른 배럴 정의
- 선수별 성적 데이터 분석
- 시계열 데이터 분석
- 다양한 시각화를 통한 인사이트 도출

### 3. 모델링
- 시계열 특성을 고려한 Feature Engineering
- 다양한 머신러닝 모델 실험
- 모델 성능 평가 및 최적화

## 📌 참고 자료
- [빅콘테스트 공식 페이지](https://www.bigcontest.or.kr/)
- [빅콘테스트 가이드라인](https://www.bigcontest.or.kr/guide/guide.php)
- [빅콘테스트 Q&A](https://www.bigcontest.or.kr/board/board.php?board=qa)
- [STATIZ](https://www.statiz.co.kr/)

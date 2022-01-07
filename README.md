# Sentiment_analysis_of_SNS
### 텍스트분석을 활용한 코로나19, 국민 감성변화의 실태조사
* 데이터: 네이버 뉴스 크롤링
* 기간 : 2020.10 ~ 2020.12

## 1. 코드 설명 

### 1) 네이버_뉴스_크롤링
  * 데이터 셋 확보

### 2) 데이터_전처리_추출
  * 전처리 관련 코드
  * 한국어 전처리 패키지(Py-Hanspell)
  * 한국어 품사 태깅(Mecab)

### 3) 최종 모델 및 태깅 코드
  * BERT

### 4) 뉴스 크롤링(중앙/경향)

 *(주무관님의 추가 요청)*
  * 원하는 섹션별로 전문 가져오기 
  * ![기준](https://user-images.githubusercontent.com/60343930/148387120-a6951027-0861-4386-9eaf-147641881c1f.png)
  * [경향(블로그 코드설명)](https://pickwon.tistory.com/74)
  * [중앙(블로그 코드설명)](https://pickwon.tistory.com/71)

### 5) 시도해본 코드
  * __Bert.ipynb__ -> Bert 모델 학습_1
  * __Bert_3.ipynb__ -> Bert 모델 학습_2
  * __BoW,keras_분노.ipynb__ -> BoW,keras_분노.ipynb -> bag of words에서 상위 n개의 단어로 keras 학습 모델
  * __glove.ipynb__ -> glove로 임베딩 후 keras에서 weight 부여
  * __word2vec으로.ipynb__ -> word2vec통해 임베딩 후 keras 모델 적용
  * __word2vec을_통한_단어별_좌표이용.ipynb__ -> word2vec통해 임베딩 후 머신러닝과 keras 모델 적용
  * __저장된_모델을_불러와_테스트.ipynb__ -> 저장된 Bert 모델을 불러와 TEST

## 2. 최종 보고서 

[최종 보고서](https://drive.google.com/file/d/1dQZiu08gpMPn4Te9dkGFJKTh6D8X2Amf/view?usp=sharing)


## 3. 참여자

1) 과제 책임자 
 * 김도연
 * 김주영
 * 박다원

2) 피드백
 * 김학준(서울특별시 빅데이터담당관 주무관님)




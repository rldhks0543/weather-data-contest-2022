# 

<img width="500" alt="★날씨빅데이터2022(최종)_ 기간연장" src="https://github.com/rldhks0543/weather-data-contest-2022/assets/114603826/c13f0a13-6845-47f7-89c8-a2fe7690b280">
  
##### 2차 대회-과제2 : 기상(날씨)에 따른 혈관 질환 발생 예측 모델 개발 참여
  
  
### 📝 **요약**

- **대회의 목표 :** 기상 데이터를 활용하여 전국의 일별, 지역별, 성별, 심뇌혈관 질환 발생 빈도를 예측 및 관련 요인 도
- **대회 Key Point** **:** 독립 변수를 직접 선정 및 수집하여 심뇌혈관 질환 발생 빈도 예측 및 변수 영향력 파악

- **사용 데이터**
    1. 기상 예보(기상청 제공)
    2. 종관기상관측(ASOS)
    3. 방재기상관측(AWS)
    4. 대기질 정보
    5. 지역사회건강조사
    6. 주민등록인구통계
- **사용 모델**
    1. Graidient Boost
    2. XGBoost
    3. CatBoost
    4. LSTM

### 👨‍💼 **역할**

- 프로젝트 전체 인원 : 본인 포함 5명
- 나의 역할과 기여도
    - 심뇌혈관 질환과 관련된 선행 연구에 기반하여 유의미한 변수를 선정
        
        크게 기상, 대기질, 인구학적 특성, 개인 건강 조사 4가지 분류로 나누었으며 각 분류 별 선행 연구를 토대로 변수를 선정하였습니다.
        
    - 여러 변수 중 지역사회건강조사 데이터를 수집 및 가공
        
        각 보건소 위치를 파악해 시도별로 변환 후, 타 데이터들과 활용하기 위하여 17개 시도별 평균으로 재구성하였습니다.
        

### 🏆 **성과**

- 환경부 장관상 수상
<img width="400" alt="KakaoTalk_20221009_170250918_01" src="KakaoTalk_20221009_170250918_01](https://github.com/rldhks0543/weather-data-contest-2022/assets/114603826/8c1d72b7-73b0-4618-b208-dd251028f173">

※ 최종 보고서

[[최종공모안] 2차_2과제_220052_K-로켓단.pdf](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/44fe77f4-b898-450c-9df1-4887b525d465/%EC%B5%9C%EC%A2%85%EA%B3%B5%EB%AA%A8%EC%95%88_2%EC%B0%A8_2%EA%B3%BC%EC%A0%9C_220052_K-%EB%A1%9C%EC%BC%93%EB%8B%A8.pdf)

### 💡 성장 경험

데이터 가공의 중요성과 어려움

- 대회를 진행하는 과정에서 데이터를 수집하고 가공하는 과정이 가장 큰 Challenge 였습니다. 실제로 대회 기간 중 수집한 데이터를 한 기준점을 잡고 하나의 데이터 프레임으로 병합하기 위해 가장 고민을 많이 했고 많은 시간을 들였던 부분이었습니다. 따라서 데이터를 잘 가공하여 사용하기 위해서는 데이터를 수집하는 초기 단계부터 구조와 연결점을 고려하여 체계적으로 데이터를 정리하고, 데이터를 병합하기 위한 효율적인 방법을 찾는 등의 노력이 필요하다는 것을 알 수 있었습니다.

다양한 모델의 활용

- 본 대회에서 4개의 모델에 대한 예측값을 앙상블하여 RMSE값을 더 낮출 수 있었습니다. 이 과정을 통해 하나의 모델만을 사용하는 것이 아닌 다양한 모델을 앙상블함으로써 모델끼리의 상호보완적인 효과를 가져올 수 있다는 점을 깨달을 수 있었습니다.

해석 가능한 AI(XAI)의 유용성

- 활용된 머신러닝 모델들은  일반적인 회귀모델과 달리 블랙박스 모델로 해석에 있어서의 어려움이 존재합니다. 따라서 설명가능한 AI인 SHAP(**SH**apley **A**dditive ex**P**lanation)를 활용하여 예측에 활용된 변수들의 영향력을 파악하였습니다. 이후 도출된 변수 영향력을 기반으로 유용한 insight를 도출 할 수 있었습니다.

### 📊 **시기**

- 프로젝트 진행 기간 : 2022.6 ~ 2022.8

# Basic-Bigdata-2024
2024년 IoT 개발자 과정 빅데이터분석 및 인공지능 학습 리포지토리 

### 빅데이터 머신러닝 + 딥러닝 추가 공부 : https://github.com/rickiepark/hg-mldl 

## 1일차 
- 빅데이터를 사용하여 사회 전반적인 문제, 현상, 원인, 해결점 등을 찾아가는 분석방법 
- 사회 전반에 모든 곳에서 활용됨 
- 예: 소셜커머스에서 20대 중반 여자들이 선호하는(트렌드)화장품 
    1. 소셜커머스에서 20대 중반 여자 - 회원정보를 검색 
    2. 회원들이 검색한 내용 중 화장품을 조회 
    3. 그 중에서 가장 많이 검색된 화장품 통계내기 
    4. 20대 중반 여성 회원이 로그인시
    5. 첫 화면에 검색된 화장품 1~3위를 디스플레이 함 = 추천 

- 빅데이터란? : https://velog.io/@garam/DE-%EB%B9%85%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%9D%98-%ED%8A%B9%EC%A7%953V-5V-7V
    - 빅데이터란 기존 데이터베이스 관리도구의 능력을 넘어서는 대량의 정형 또는 비정형 데이터로부터 가치를 추출하고 결과를 분석하는 기술
    - 3V : Volume(규모), Variety(다양성), Velocity(속도) 
    - 5V : 3V + Veracity(정확성)과 Value(가치)
    - 7V : 5V + Valiaity(정확성), Volatility(휘발성)

- 데이터 
    - 정보를 수집한 자료 자체, 값, 총계에 Value를 더하면 정보(information)가 된다. 

- 빅데이터 분석 순서 : 생성 - 수집 - 저장 - 분석 - 표현 
    1. 생성 : IoT 센싱값, 빅데이터 플랫폼(쇼핑몰, 포털)을 통해서 생성  
    2. 수집 : MQTT로 DB에 전달, 빅데이터 플랫폼(하둡, 카프카...)에서 수집 + 크롤링, 네트워크 포함 
    3. 저장 : 수집과 거의 동일, DB에 저장(카프카, 데이터마이닝, NoSQL...)
    4. 분석 : 통계적 분석, 탐색적 분석(EDA), 머신러닝, 딥러닝, 자연어처리, 이미지 프로세싱 분석툴(Spark, Tableau, MS PowerBI) 사용 
    5. 표현 : 인사이트 도출(시각화, 그리드)

- 데이터 분석 기초
    - 파이썬 (외 R, 자바, C# 등 다른 언어로도 분석 가능. 단, 파이썬이 가장 쉽기때문에 많이 사용)
    1. 데이터 처리 : Numpy(수치해석, 계산), Pandas(데이터처리), Scipy(과학계산)...
    2. 시각화 : Folium(지도), Matplotlib(차트), Seaborn(Matplotlib 고급화)...
    3. 엑셀 : openpyxl(엑셀처리)
    4. 크롤링 : Selenium(웹크롤링 자동화), BeautifulSoup(웹페이지 정제)
    5. 머신러닝/딥러닝 : Scikit-Learn(가장 간단한 머신러닝), MS CNTK, Theano, Keras(최초의 딥러닝), TensorFlow(제일 유명, Keras 포함), PyTorch(파이토치, 페이스북에서 만듦)

**ctrl shift p : create 새 jupyternotebook 만들기**

- 빅데이터 학습
    - 실습자료, 파이썬 기본리뷰, 빅데이터 분석 기초학습
    - [넘파이](https://github.com/hyeily0627/Basic-Bigdata-2024/blob/main/day01/01numpy_basic.ipynb)
    - [판다스](https://github.com/hyeily0627/Basic-Bigdata-2024/blob/main/day01/02pandas_basic.ipynb)
    - [맷플롭립](https://github.com/hyeily0627/Basic-Bigdata-2024/blob/main/day01/03matplotlib_basic.ipynb) 
    
## 2일차 
- 빅데이터 학습
    - 기초학습, 크롤링 관련 
    - [뷰티풀수프](https://github.com/hyeily0627/Basic-Bigdata-2024/blob/main/day02/04beatifulsoup_basic.ipynb)
    - [셀레니움](https://github.com/hyeily0627/Basic-Bigdata-2024/blob/main/day02/05selenium_basic.ipynb) 

- 빅데이터 실습
    - [스타벅스 입지 분석](https://github.com/hyeily0627/Basic-Bigdata-2024/blob/main/day02/06starbucks_analysis.ipynb)

#### *데이터 전처리 
- 데이터로 통계를 낼 때 문제가 없도록 데이터를 사전에 처리 해주는 것 
- 데이터 전처리가 빅데이터 분석 전체 프로젝트의 50%를 차지할 정도로 비중이 높다. 
- 전처리 케이스
1. ❗데이터 결측치 확인 
    - Null, NAN, '', empty 등 값이 없는 컬럼을 제거/유용한 값으로 치환
    - Null, NAN은 통계 계산시 계산된 값도 Null로 바뀜 
    - 숫자로 된 컬럼 값에는 결측치 제거/변경이 필수🚨
2. 필요없는 컬럼/행 제거
3. 필요하지만 없는 컬럼 추가 
4. 잘못 된 값 변경 


## 3일차





## 4일차




## 5일차 




## 6일차 




## 7일차 




## 8일차 




## 9일차 

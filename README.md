## 파이썬을 이용한 크롤링 및 데이터 분석 토이 프로젝트 ( 개인 )

### Intro

.ipynb 파일 특성 상 GitHub 에서 오픈하는 시간이 매우 오래 걸린다. 그래서 대부분 download 를 권장한다  
하지만, 빠르게 내용을 확인 할 수 있는 방법이 두 가지 있다 
    
1. nbviewer 사용 
    
    > 원래는 gist를 통해 원하는 .ipynb 파일의 raw source를 복붙하여 나오는 특정 부분의 URL로 nbviewer에 접근했던 모양이다. <br><br>
    하지만 현재는 깃허브에 업로드된 파일의 URL 자체를 가지고 [https://nbviewer.jupyter.org/](https://nbviewer.jupyter.org/) 에 접속하여 입력만 해도 <br><br>
    nbviewer 로 .ipynb 파일 내용이 그대로 출력되는 것을 확인 할 수 있다. 출력의 결과물 까지 확인 할 수 있기 때문에 편리하다 
    
2. py 파일로 변환 

    > 간단하게 Jupyter 에서 해결 할 수 있다 <br><br>
      pip install nbconvert <br><br>
      ipython nbconvert - to script filename.ipynb <br><br>
      을 입력만 해주면 filename.py 파일이 생성된다. 하지만 .py 확장자 에서는 파일의 코드 자체만 확인이 가능하기 때문에 이 방법을 사용하지 않았다
      
### Open API 

[카테고리 별 open API 사이트 정리 github](https://github.com/dl0312/open-apis-korea#%EA%B3%BC%ED%95%99--%EC%88%98%ED%95%99)

### Topic

[plotly graph reference](https://plotly.com/python/reference/)

* COVID19 의학 수치에 따른 코로나 심각단계 단순 분석 및 가설검정 (+시각화 추가) : __COVID19_impact 폴더__   
[빠른 주피터 노트북 보기](https://nbviewer.jupyter.org/github/Jin-Baek/Py.Crawling_Analysis/blob/main/COVID19_impact/COVID19_impact.ipynb)
  * Visualization : plotly / heatmap , scatter
  * Data Origin : Korea Univ. Sejong Probability and Statistics class

* COVID19 국가별 확진자 동향 분석 ( 01/22/2020 ~ 06/17/202 ) : __COVID19_confirmed 폴더__  
[빠른 주피터 노트북 보기](https://nbviewer.jupyter.org/gist/Jin-Baek/e48d574c14870472ad93fcd0ed77380e)  
[빠른 flourish 시각화 그래프 보기](https://public.flourish.studio/visualisation/4783794/)
  * Visualization : flourish / Bar race 
  * Data Origin : Github , Inflearn 
  
  
* COVID19 한국 2020년도 추이 분석 : __COVID19_Korea_2020 폴더__   
[빠른 주피터 노트북 보기](https://nbviewer.jupyter.org/github/Jin-Baek/Py.Crawling_Analysis/blob/d76c5fe4364ba5092f7fc874a77371dcf5a695cc/COVID19_Korea_2020/COVID19-korea_info_2020.ipynb)
  * Visualization : plotly / Scatter , Bar
  * Data Origin : 대한민국 통계청 
  
  
* 한국보건의료인국가시험원_보건의료인국가시험 성적 분석 ( 2000 ~ 2020 ) + Data type summary :  __HealthCare_national_exam 폴더__   
[빠른 주피터 노트북 보기](https://nbviewer.jupyter.org/github/Jin-Baek/Py.Crawling_Analysis/blob/main/HealthCare_national_exam/EDA_HealthCare_test.ipynb)
  * 탐색적 데이터 분석 EDA 기법 사용
  * Visualization : plotly / box plot , histogram , bar , pie
  * Data Origin : 공공데이터 홈페이지 
  
  (진행중)
* Brazil E-commerce Olist 쇼핑몰 데이터 분석 : ___ 폴더 
  * 탐색적 데이터 분석 (EDA) 기법 사용
  * Customer data , Monthly turnover, Delivery time , Purchase trends by category , Transaction trends by period 등 분석 
  * Visualization : plotly / 데이터 형태에 맞는 그래프 선택 
  * Data Origin : Github , Inflearn 
  
(예정)
* COVID19 국가별 사망률 동향 분석 ( 01/22/2020 ~ 06/17/202 ) : COVID19_Deaths_Rate 폴더 
  * Visualization : flourish / Column Bar race
  * Data Origin : Github , Inflearn 

(예정)
* 네이버 쇼핑몰 카테고리별 상품 판매량 분석 
  * Visualization : flourish / Hierarchy bar 
  * Data Origin : Developers Naver datalab with Crawling

__The origins of the data for all projects are stored as links inside the file ( Some reveal the origin itself, not the URL )__

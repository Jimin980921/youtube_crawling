## 주제  
유튜브는 유행이 즉각적으로 드러나고, 유튜브의 댓글에서 시청자의 반응이나 감정이 잘 들어나는 특징이 있음  
=> __유행에 민감한 유튜브를 크롤링하여 유행음식 분석 및 시각화__


-------------------------------------------------------------------------------------------------------------------
## 개발 환경  
* BeautifulSoup, selenium, chromeWebDriver, Jupyter Notebook 사용

* hadoop, spark, python3 사용

* __데이터 수집방법__: 구독자 수가 10만명이상되는 유튜버들의 먹방 정보 수집  
<br>



## 개발단계  
__1단계: 데이터 수집__  
구독자 20만이상 유튜버 50명의 먹방동영상 정보 크롤링  
<p align="center"> 
<img src="https://user-images.githubusercontent.com/57060127/90315013-ed505a80-df52-11ea-8f89-30286916d3d9.JPG" width=45%>
</p>  
<br>




__2단계: 데이터 전처리__  
50명의 유튜버의 먹방 제목 불용어 제거, 동의어 처리    
<p align="center">   
<img src="https://user-images.githubusercontent.com/57060127/85222662-fd870600-b3f7-11ea-91e6-06901055d920.JPG" width=70%>
</p>
<p align="center"> 
<img src="https://user-images.githubusercontent.com/57060127/85222664-ff50c980-b3f7-11ea-8009-f54fac3f79eb.JPG" width=70%>
</p>
<br>




__3단계: 데이터 정리__  
각 유튜버 먹방 제목의 빈도수 추출한 txt를 합쳐서 FrequencyRdd 생성    
FrequencyRdd에서 음식이름을 기준으로 빈도수를 더해 겹치는 단어의 빈도수를 합침  

-------------------------------------------------------------------------------------

## 분석 결과  
프로젝트시기에 유행했던 불닭볶음면, 치즈볼, 당면 등의 빈도수가 높은 것으로 도출
<p align="center"> 
<img src="https://user-images.githubusercontent.com/57060127/76674502-891c1a00-65f3-11ea-9062-1f7cc7cc43d2.PNG" width=40%>
</p>
<br>
<br>


p.s) 크롤링을 자습하고 진행한 첫 프로젝트이기때문에 효율적으로 구현하지못한 아쉬운점이 있음.  
이후 더 공부하여 다양한 크롤링 프로젝트를 진행함.  

- 유사 프로젝트  
   - [네이버 쇼핑 리뷰 크롤링 프로젝트](https://github.com/Jimin980921/text_mining)  
   - [네이버 지도 크롤링 ](https://github.com/Jimin980921/Dongjak_bigdata_project) 



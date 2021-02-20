# 폐기물 발생 및 처리현황 데이터 분석
### : 생활계 폐기물 처리방식에 따른 분류별 변화추이
-------------------------------------------------------------------
#### Period: 2021.02.09 ~ 2021.02.18
#### Member: 류승환, 장지혜, 장혜임


![d](https://user-images.githubusercontent.com/75402257/108579704-7f567700-736b-11eb-830a-c6452a4ab098.jpg)
 [사진=헤럴드DB]



## “Z세대들 사이에서 이런 행동을 하게 된 가장 중요한 동인은 ‘기후 변화’입니다.”
 ##### - Maya's Ideas CEO Penn
 
 
## 1. 주제 선정

- 'MZ세대'의 주된 관심사인 '지속가능한 미래', '지속가능한 발전'중 환경문제는 전세계적인 이슈
- 기후변화 즉, 지구 온난화 현상의 주범은 온실가스 배출
- 온실가스는 화석 연료를 사용할 때 배출되는 이산화탄소와 농업 활동 및 폐기물 처리로 발생하는 메탄과 아산화질소가 주를 이룸
- 이에 따라 폐기물 발생 및 처리현황 데이터를 분석하여 인사이트를 도출하고자 함

-------------------------------------------------------------------
## 2. Data 소개
  
- 폐기물 처리현황 생활계폐기물
  - 전국의 생활계폐기물에 대한 1년 단위 발생 및 처리현황 데이터 (1996년 ~ 2018년)
  
- 폐기물 종류별 재활용현황
  - 연간 폐기물의 재활용실적 (2001년 ~ 2015년)
  
  

 ### 2-1. Read data
 
 
```
df_1 = read(datas/ -
```
---------------------------------------------------------------
## 3. Goals

 - 생활계폐기물 처리현황 파악
 - 생활계폐기물 종류별 처리현황 분석 (처리유형별: 매립, 소각, 재활용)
 - 처리 유형별 변화추이와 원인 분석

----------------------------------------------------------------
## 4. Process
![1](https://user-images.githubusercontent.com/75402257/108580098-5e8f2100-736d-11eb-8c17-1a875cd07746.PNG)
![그림2](https://user-images.githubusercontent.com/75402257/108580360-8a5ed680-736e-11eb-8809-e3a430fcfb7c.PNG)
![2](https://user-images.githubusercontent.com/75402257/108580099-5fc04e00-736d-11eb-875c-c49cde70f1b2.PNG)
![3](https://user-images.githubusercontent.com/75402257/108580101-618a1180-736d-11eb-848b-6ff46d50e86d.PNG)
![4](https://user-images.githubusercontent.com/75402257/108580102-6353d500-736d-11eb-8ec5-d8436ec4e749.PNG)
![5](https://user-images.githubusercontent.com/75402257/108580105-64850200-736d-11eb-938b-3213e7d6e1b8.PNG)
![6](https://user-images.githubusercontent.com/75402257/108580107-651d9880-736d-11eb-954e-adc06dcd865c.PNG)
![7](https://user-images.githubusercontent.com/75402257/108580108-664ec580-736d-11eb-9474-d6ddcd4af4ae.PNG)
![8](https://user-images.githubusercontent.com/75402257/108580112-66e75c00-736d-11eb-838e-142bf7f1e806.PNG)
![9](https://user-images.githubusercontent.com/75402257/108580114-68188900-736d-11eb-9459-8b6069017167.PNG)


 
----------------------------------------------------------------
## 5. Insight

----------------------------------------------------------------

### Member / role

- 류승환 / 자료조사 및 발표
- 장지혜 / 분석, 발표기획 및 발표자료작성, 검토, 자료조사 
- 장혜임 / 데이터전처리, 분석, 시각화, 발표자료 검토, 자료조사

-----------------------------------------------------------------
### Data 출처

- [국가통계포털(KOSIS)] (https://kosis.kr/)
- [OECD Statistics] (https://stats.oecd.org/)
- [그린피스 코리아] (https://www.greenpeace.org/korea/)

### Reference

#### 기사
- 강은지 (2019. 11. 26.). “폐기물 처리비용 年 23조원 육박… 플라스틱 재활용 체계부터 바꾸자”. <동아닷컴>.
	- URL: https://www.donga.com/news/article/all/20191126/98532768/1
- 김동수 (2020. 03. 25.). [냉장고 비우고 지구를 구하라 ⑦] 음식물 쓰레기 정책…근본적으로 배출량 줄여야. <그린포스트코리아>. 
-	- URL: http://www.greenpostkorea.co.kr/news/articleView.html?idxno=115830#:~:text=두 곳에서 배출된,가스 등)로 재활용됐다.
- 김종민 (2008. 12. 02.). 쓰레기봉투 속 들여다보니…종이류 '최다'. <뉴시스>.
	- URL: https://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=102&oid=003&aid=0002408414
- 연합뉴스 (1992. 07. 20.). '음식물쓰레기처리 퇴비화가 최적'. <연합뉴스>. 
	- URL: https://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=105&oid=001&aid=0003575814"
- 연합뉴스 (1995. 03. 22.). 수도권에 음식쓰레기 처리시설 설치. <연합뉴스>. 
	- URL: https://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=101&oid=001&aid=0003979249"
- 연합뉴스 (1996. 06. 07.). 음식물쓰레기 1t 경제적 가치 8만1천원. <연합뉴스>. 
	- URL: https://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=101&oid=001&aid=0004116008
- 연합뉴스 (1998. 01. 12.). 쓰레기중 종이류 비중 가장 높아. <연합뉴스>.
	- URL: https://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=101&oid=001&aid=0004308700
- 조선일보 (1997. 06. 05.). [입법예고] 2005년부터 음식물쓰레기 직매립 금지. <조선일보>. 
	- URL: https://www.chosun.com/site/data/html_dir/1997/06/05/1997060570160.html
- 코네틱리포트 (2001). 음식물 쓰레기 감량화 및 재활용 기술. <konetic>. 
	- URL: https://www.konetic.or.kr/insight/koneticreport_view.asp?unique_num=323&tblNm=
- happist (2020. 04. 08.). Z세대 특성 2/4, 환경 보호에 높은 관심과 적극적 참여. 
	- URL: https://happist.com/571662/z세대-특성-1-3-환경-보호에-높은-관심과-적극적-참여#Zsedae_teugseong_24_hwangyeong_boho-e_nop-eun_gwansimgwa_jeoggeugjeog_cham-yeo

#### 논문 및 보고서
- 김두환 (2005). 음식물폐기물의 직매립 금지. <나라경제>, 2005(1), 63-66.
- 녹색성장위원회 (2010). <음식물쓰레기 줄이기 종합대책>.
- 배재근 (2017). <음식물류폐기물 처리실태 조사 및 관리방안 연구>. 세종: 환경부.
- 코네틱리포트 (2017). <RFID 기반 음식물류 폐기물 관리체계 구축·운영>. 
- 환경부 (2019). <2018 전국 폐기물 발생 및 처리현황>. 세종: 환경부.



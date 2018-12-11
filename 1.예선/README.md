# 2018_privacy_anonymization_competition_예선

### 참고자료

##### KERIS 비식별조치 가이드라인 [[PAGE_LINK]](http://www.keris.or.kr/know/kn_support02.jsp?bbsid=board18&gbn=view&gp=1&ps=10&sp=&sw=&ob=sor1&ix=25823&orderkey=3)[[PDF_LINK]](http://www.keris.or.kr/board/pb_downloadNew.jsp?bbs_num=22455&ix=25823)


##### K-ICT 빅데이터 보고서 [[PAGE_LINK]](https://kbig.kr/portal/kbig/knowledge/files/bigdata_report.page)
  * 개인정보 비식별화 자가진단도구 
  * 비식별조치 전문교육 교재 및 실습자료  
  * 개인정보 비식별도구 ARX 교재 및 실습자료 
  * 2018년 비식별 사례집 

----

<br>

### STEP2. [[개인정보_비식별]](https://github.com/zel0rd/2018_privacy_anonymization_competition/tree/master/1.예선)
- 개인정보 비식별 조치(ARX, R 이용)  
- 원본데이터 - 사용목적, 데이터속성 분석, 속성별 상관관계, 이상치 수정 및 제거  
- 정제데이터 - 속성별 데이터 분석(대푯값), 유용성 및 상관관계 비교  
- 비식별화 - 개인정보 속성평가(ID,QI,SA,NSA), 비식별방안수립, 비식별화(K,L,T)
- 비식별데이터 평가 - 속성별 데이터 분석(대푯값), 유용성 및 상관관계 비교, 준식별 조합에 대한 유일성 평가  
- 재식별 위험도 측정, 분산 위험도 측정 
  
<br>

----

#### 인정보 비식별 조치(ARX, R 이용)  
> ARX [[DOWNLOAD]](https://arx.deidentifier.org/downloads/)  
> R [[DOWNLOAD]](https://cran.r-project.org)  
> RSTUDIO [[DOWNLOAD]](https://www.rstudio.com/products/rstudio/download/)  

<br>

#### 원본데이터 - 사용목적, 데이터속성 분석, 속성별 상관관계, 이상치 수정 및 제거  

#### [예선전 개최 안내](https://github.com/zel0rd/2018_privacy_anonymization_competition/blob/master/References/02.%5BKISA%5D개인정보_비식별_기술_경진대회_예선전_개최_계획(배포용).pdf) 의 대회데이터셋 정의 예시사용
※ 아래의 데이터셋은 대회 데이터셋 정의 예시로 Dummy Data 입니다.


| 이름 | 생년월일 | 나이 | 성별 | 주소 | 우편번호 | 통신사 | 직업군 | 월카드_이용금액 | 연체금액 | 총대출잔액 | 카드한도 | 신용등급 | 일련번호 | 핸드폰번호 | 월소득 |
|:-------:|:-------:|:-------:|:-------:|
| |b        |c        |d        |


#### 정제데이터 - 속성별 데이터 분석(대푯값), 유용성 및 상관관계 비교  
#### 비식별화 - 개인정보 속성평가(ID,QI,SA,NSA), 비식별방안수립, 비식별화(K,L,T)  
#### 비식별데이터 평가 - 속성별 데이터 분석(대푯값), 유용성 및 상관관계 비교, 준식별 조합에 대한 유일성 평가  
#### 재식별 위험도 측정, 분산 위험도 측정 

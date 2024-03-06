# eda-repo-6
EDA 프로젝트 6조 저장소. 부동산 데이터 분석

---
## 01. 프로젝트 소개

집을 구매할때 초품아,대중교통,대형병원 등의 요소를 고려하는 경향이 있다.
<br/>
주변에 인프라가 많을수록 인기가 높고 집값에도 영향을 준다.<br/>
부동산 가격과 연관성이 있다고 알려진 인프라 요소들과 서울 시 자치구별 아파트 평균 가격을 비교하여 위의 가설이 신뢰성이 있는지 확인해보았다.

---
## <img src = "https://github.com/addinedu-ros-4th/eda-repo-6/assets/55430286/f6801c92-5ead-4a51-9603-49ca9b4bf1db" width = "5%">02. 프로젝트 멤버 및 역할
* 팀명 : 복덕방
* 팀장 (: 뒤에 했던 것들을 적어주세요)
  * 유재상 :
* 팀원
  * 도준엽 : 데이터 수집, 전처리, 시각화, 분석 / 관련 키워드 추출
  * 윤현준 : 데이터 수집, 시각화/ 데이터 별 상관관계 분석
  * 장종찬 :
---
## <img src = "https://github.com/addinedu-ros-4th/eda-repo-6/assets/55430286/92c8ce66-59d5-49a7-8973-6a473ce3950f" width = "5%">0. 사용 기술
<img src = "https://github.com/DJY0404/remote_project/assets/55430286/5f0ceb64-a144-4b76-a132-e2a2b8fb4275">


---
## 0. 결론
분석한 결과, 종로구와 노원구가 특이한 양상을 보이는 것을 확인했다.
<br/>
<img src = "https://github.com/addinedu-ros-4th/eda-repo-6/assets/55430286/fd1bf3a9-9630-4123-8df5-9ad12636a7ba" width = "45%">
<img src = "https://github.com/DJY0404/remote_project/assets/55430286/3133534e-6998-497c-906b-0e0b89d5b903" width = "45%">


---
## <img src="https://private-user-images.githubusercontent.com/55430286/310444943-2dacc240-65b1-4f78-b766-4e45ae09cdf5.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDk3MTkwOTUsIm5iZiI6MTcwOTcxODc5NSwicGF0aCI6Ii81NTQzMDI4Ni8zMTA0NDQ5NDMtMmRhY2MyNDAtNjViMS00Zjc4LWI3NjYtNGU0NWFlMDljZGY1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAzMDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMzA2VDA5NTMxNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTgzZGUwZjlhOGE0YjU5ZWVmMzkxN2Q1NjA2OTkyYmRmNjA0MTA3ZjgyMDRiOWZmZWQ0NzIwYzNhZjVlOTk1N2EmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.492zUkwX6rA--IV0GG4WT4NtNqueIj7RdaVDt4jyWKI" width = "5%" >0. 분석 내용

<img src = "https://github.com/DJY0404/remote_project/assets/55430286/5f0fb6fd-4c10-4504-8aac-f9519ea7400e">
<br/>
서울 아파트 가격 고점을 기록했던 2021년에 특정 요인이 부동산에 미치는 영향을 분석하였다.  
<br/>
<br/>

### 우리가 흔히들 알고 있는 집값에 영향을 미치는 요소들을 구별로 데이터 시각화를 해보겠다.

집값에서 하위권인 노원구가 초등학교 수가 가장 많았다.
![image_720](https://github.com/YoonHJ97/merge_project/assets/162243554/64467807-f69d-488d-936a-1cb8c1495da7)


그 밖에 다른 요소들도 데이터 시각화 해보았다.
![image_720](https://github.com/YoonHJ97/merge_project/assets/162243554/ba01d3f1-85a1-4b53-b55d-4c0b23fcc776)

우리가 알고있던 요소들이 생각보다 집값에 영향을 미치지 않은 것 같다.
더 정확히 알아보기 위해 수집한 데이터들과 아파트 매매가격이 어떤 연관이 있는지 상관계수를 구해보았다.

<code>trade = pop_reg.corr().round(2)['거래금액(만원)']</code>

<br/>
<img src = "(https://github.com/YoonHJ97/merge_project/assets/162243554/3e924fea-7632-49d9-a14c-b78c3387db81)">
pandas 라이브러리에서 사용되는 메서드인 corr()을 통해 아파트 매매가격과 상관관계가 높은 컬럼을 찾을 수 있다.
<br/>
<br/>
<br/>
<img src = "!(https://github.com/YoonHJ97/merge_project/assets/162243554/06bfd30b-5bdb-44f0-a093-1777ef94b42a)">
매매자수 변동 그래프를 살펴보면 노원구가 가장 많이 변화했고, 종로구가 가장 적게 변화한 걸 알 수 있다.
#그리고 전체적으로 18년 8월, 20년 6월을 기점으로 급등한 걸 알 수 있다.
<br/>
<br/>
<br/>

---
## <img src = "https://github.com/addinedu-ros-4th/eda-repo-6/assets/55430286/e2d767e5-d544-45f1-ba1e-dee982b7b2fd" width = "5%">0. 사용한 데이터

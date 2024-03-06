# eda-repo-6
EDA 프로젝트 6조 저장소. 부동산 데이터 분석

---
## 01. 프로젝트 소개

집을 구매할때 초품아,대중교통,대형병원 등의 요소를 고려하는 경향이 있다. 
주변에 인프라가 많을수록 인기가 높고 집값에도 영향을 준다.
부동산 가격과 연관성이 있다고 알려진 인프라 요소들과 서울시 자치구별 아파트 평균 가격을 비교하여 위의 가설이 신뢰성이 있는지 확인해보았다.

---
## <img src = "https://github.com/addinedu-ros-4th/eda-repo-6/assets/55430286/f6801c92-5ead-4a51-9603-49ca9b4bf1db" width = "5%">02. 프로젝트 멤버 및 역할
* 팀명 : 복덕방
* 팀장 (: 뒤에 했던 것들을 적어주세요)
  * 유재상 :
* 팀원
  * 도준엽 :
  * 윤현준 :
  * 장종찬 :
---
## <img src = "https://github.com/addinedu-ros-4th/eda-repo-6/assets/55430286/92c8ce66-59d5-49a7-8973-6a473ce3950f" width = "5%">0. 사용 기술
<img src = "https://github.com/DJY0404/remote_project/assets/55430286/5f0ceb64-a144-4b76-a132-e2a2b8fb4275">

---
## 0. 결론
분석한 결과, 종로구와 노원구가 특이한 양상을 보이는 것을 확인했다.
![image](https://github.com/addinedu-ros-4th/eda-repo-6/assets/55430286/fd1bf3a9-9630-4123-8df5-9ad12636a7ba)



---
## <img src="https://private-user-images.githubusercontent.com/55430286/310444943-2dacc240-65b1-4f78-b766-4e45ae09cdf5.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDk3MTkwOTUsIm5iZiI6MTcwOTcxODc5NSwicGF0aCI6Ii81NTQzMDI4Ni8zMTA0NDQ5NDMtMmRhY2MyNDAtNjViMS00Zjc4LWI3NjYtNGU0NWFlMDljZGY1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAzMDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMzA2VDA5NTMxNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTgzZGUwZjlhOGE0YjU5ZWVmMzkxN2Q1NjA2OTkyYmRmNjA0MTA3ZjgyMDRiOWZmZWQ0NzIwYzNhZjVlOTk1N2EmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.492zUkwX6rA--IV0GG4WT4NtNqueIj7RdaVDt4jyWKI" width = "5%" >0. 분석 내용

<img src = "https://github.com/DJY0404/remote_project/assets/55430286/5f0fb6fd-4c10-4504-8aac-f9519ea7400e">
<br/>
서울 아파트 가격 고점을 기록했던 2021년에 특정 요인이 부동산에 미치는 영향을 분석하였다.  
<br/>
<br/>
<br/>
<img src = "https://github.com/DJY0404/remote_project/assets/55430286/e0fa2846-c85a-4ee1-9954-9ad92898ff0a">
pandas 라이브러리에서 사용되는 메서드인 corr()을 통해 아파트 매매가격과 상관관계가 높은 컬럼을 찾을 수 있다.
<br/>
<br/>
<br/>
<img src = "https://github.com/DJY0404/remote_project/assets/55430286/13c50936-cef5-4e46-a0b3-b3d6500c1839">
매매자수 변동 그래프를 살펴보면 노원구가 가장 많이 변화했고, 종로구가 가장 적게 변화한 걸 알 수 있다.
#그리고 전체적으로 18년 8월, 20년 6월을 기점으로 급등한 걸 알 수 있다.
<br/>
<br/>
<br/>

---
## <img src = "https://github.com/addinedu-ros-4th/eda-repo-6/assets/55430286/e2d767e5-d544-45f1-ba1e-dee982b7b2fd" width = "5%">0. 사용한 데이터

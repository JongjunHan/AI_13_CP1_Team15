# drought_ds
<p align="justify">
</p>

전체 과정 및 소개 링크 : https://github.com/JongjunHan/drought_cp
배포 주소 : https://drought-info.herokuapp.com

## 프로젝트 내용 및 목표

- ASOS(종관기상관측)자료와 SPI(표준강수지수)를 이용한 가뭄 예측 모델링 과정

- 해당 지역은 호남지역이며 이는 호남지역이 최근 가장 큰 피해를 호소하고 있기 때문

- target은 SPI 지수로, SPI 지수를 예측하여 그에 맞는 가뭄을 예측함

- 모델을 제작함에 따라 각 단계 별 가뭄 예측을 하고, 모델을 통한 서비스 제작에 이바지 하고자 함

## 데이터 수집 과정

- 기상자료개방포털(https://data.kma.go.kr/cmmn/main.do)의 Open API를 이용한 수집

<p align="left">
  <br>
  <img src="./images/columns.png" width="300" height="600">
  <br>
</p>

- 각 columns의 세부 정보는 이러한 형태를 보임


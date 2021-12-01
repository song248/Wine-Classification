# Wine-Classification
## 데이콘 - 와인 품질 분류 경진대회

#### 1. train.csv : 학습 데이터
- id : 식별 고유값
- fixed acidity : 고정(비휘발성) 산도: 와인과 관련된 대부분의 산
- volatile acidity : 휘발성 산도: 와인에 함유된 아세트산의 양. 너무 높으면 불쾌한 식초 맛이 날 수 있음
- citric acid : 구연산: 소량으로 발견되며, 와인에 풍미를 더할 수 있음
- residual sugar : 잔여 당분: 발효가 멈춘 후 남은 설탕의 양으로 1g/L 미만의 와인은 드물며 45g/L 이상의 와인은 단맛으로 간주함
- chlorides : 염소화물: 와인의 염분량
- free sulfur dioxide : 유리 이산화황: 미생물의 성장과 와인의 산화를 방지함
- total sulfur dioxide : 총 이산화황: 저농도에서는 대부분 맛이 나지 않으나 50ppm 이상의 농도에서 맛에서 뚜렷하게 나타남
- density : 밀도: 알코올 및 당 함량에 따라 변함
- pH : 산성 또는 염기성 정도. 0(매우 산성) ~ 14(매우 염기성). 대부분의 와인은 pH 3-4 사이임
- sulphates : 황산염: 이산화황 농도에 기여할 수 있는 와인 첨가제. 항균 및 항산화제로 작용
- alcohol : 와인의 알코올 함량 백분율
- type : 와인에 사용된 포도의 종류. Red(적포도주), White(백포도주)로 나뉨
- quality : 맛으로 평가된 와인의 품질  


#### 2. test.csv : 테스트 데이터
- id : 식별 고유값
- fixed acidity : 고정(비휘발성) 산도: 와인과 관련된 대부분의 산
- volatile acidity : 휘발성 산도: 와인에 함유된 아세트산의 양. 너무 높으면 불쾌한 식초 맛이 날 수 있음
- citric acid : 구연산: 소량으로 발견되며, 와인에 풍미를 더할 수 있음
- residual sugar : 잔여 당분: 발효가 멈춘 후 남은 설탕의 양으로 1g/L 미만의 와인은 드물며 45g/L 이상의 와인은 단맛으로 간주함
- chlorides : 염소화물: 와인의 염분량
- free sulfur dioxide : 유리 이산화황: 미생물의 성장과 와인의 산화를 방지함
- total sulfur dioxide : 총 이산화황: 저농도에서는 대부분 맛이 나지 않으나 50ppm 이상의 농도에서 맛에서 뚜렷하게 나타남
- density : 밀도: 알코올 및 당 함량에 따라 변함
- pH : 산성 또는 염기성 정도. 0(매우 산성) ~ 14(매우 염기성). 대부분의 와인은 pH 3-4 사이임
- sulphates : 황산염: 이산화황 농도에 기여할 수 있는 와인 첨가제. 항균 및 항산화제로 작용
- alcohol : 와인의 알코올 함량 백분율
- type : 와인에 사용된 포도의 종류. Red(적포도주), White(백포도주)로 나뉨




#### 3. sample_submissoin.csv : 제출 양식
- id : 식별 고유값
- quality : 맛으로 평가된 와인의 품질

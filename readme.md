## Titanic Survivor Prediction
#### 변수 설명
- PassengerId : 각 승객의 고유 번호
- Survived : 생존 여부(종속 변수)
  1. 0 = 사망
  2. 1 = 생존
- Pclass : 객실 등급 - 승객의 사회적, 경제적 지위
  1. 1st = Upper
  2. 2nd = Middle
  3. 3rd = Lower
- Name : 이름 X
- Sex : 성별 => categorical(1=male,2=female)
- Age : 나이 => 결측치 확인 => categorical(0=Nan,1=0~15,2=15~34,3=34~65,4=65~)
- SibSp : 동반한 Sibling(형제자매)와 Spouse(배우자)의 수
- Parch : 동반한 Parent(부모) Child(자식)의 수
- Ticket : 티켓의 고유넘버 X
- Fare : 티켓의 요금
- Cabin : 객실 번호 => categorical => 결측치 많음.
- Embarked : 승선한 항
  1. C = Cherbourg = 0
  2. Q = Queenstown = 1
  3. S = Southampton = 2
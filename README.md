### Credit Card Fraud Detection(Kaggle)
Kaggle의 신용카드 사기 데이터 분석<br>
'이프 카카오(if kakao) 개발자 컨퍼런스 2019' 공개 내용을 기반으로 신용카드 사기 데이터 분석을 진행해보고 새로운 결과와 클러스터링이 가능한지 확인해보는 프로젝트이다.언택트 시대, 비대면 은행을 많이 이용하는 요즘에는 사기를 신속하고 정확하게 판단하는 것이 중요하다. 비대면 은행을 범죄 수법 지능화에 따라 변화해가는 이상거래에 대한 탐지 시스템 고도화가 요구되고 있으며 신용카드 데이터를 이용해 분석을 통해 이상거래 탐지에 대해 알아보자.<br><br>
데이터 소개 : 2013년 9월 유럽 신용 카드 소지자들의 거래 데이터이다. 2일 동안 발생한 거래를 보여주며, 284,807 건의 거래 중 492 건의 이상 거래가 있다.   
    PCA 변환의 결과가 columns 데이터로 주어졌으며, 보안상 데이터에 대한 배경, 의미는 따로 주어지지 않았다. PCA 변환 columns (V1,...,V28) 시간, 양 데이터가 추가적으로 주어진다. 'Time(시간)'- 첫 번째 트랜잭션 사이에 경과된 초를 의미한다. 'Amount(양)'- 거래 금액을 의미한다.    
    'Class'는 target으로 이상 거래(1), 정상 거래(0)를 의미한다.  
데이터 불균형 문제 : 이상거래는 492, 정상거래는 284315로 데이터 불균형이 심각하다. 스케일, 전처리 후에도 146319:15로 불균형 문제가 지속되어 SMOTE를 이용하여 불균형 문제를 해결한다.
    
참고 링크 : http://www.bloter.net/archives/351562 , https://www.kaggle.com/terrifictitan12/fraud-detection-data-processing-94-accuracy<br>
kaggle 링크 : https://www.kaggle.com/mlg-ulb/creditcardfraud

### Dacon 신용카드 사용자 연체 예측 프로젝트
Dacon 데이터로 공유 소스를 따라하며 프로젝트를 이해하고 확장시켜본다. <br><br>
참고 링크 : https://dacon.io/competitions/official/235713/overview/schedule

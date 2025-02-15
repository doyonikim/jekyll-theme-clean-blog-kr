---
layout: post
permalink: /marketing/dcando_googleads-conversion-metrics-1
title: '광고 성과 지표 톺아보기 1편'
date: 2021-11-07 09:30:00 +09:00
feature: '/img/posts/mkt/7_googleads/main img/2.jpeg'
background: '/img/posts/mkt/7_googleads/main img/1.jpeg'
categories:
- category-marketing
tags:
  - 메타버스
  - 게더타운
  - 게더타운이벤트
  - 게더타운이벤트운영
  - 게더타운맵

description: '구글애즈 - 전환편'
---



## 1. 구글애즈 전환지표
전환수는 알겠는데 전환가치, 비용당 전환가치, ROI는 대체 뭘까? 어떻게 해석하면 될까? 내가 몰라서 정리한 구글애즈 전환 관련 지표 모음집.

<br>
* * *
<br>


#### 1.1   전환수
말 그대로 전환 액션을 통해 발생한 전환의 횟수. 전환수는 전환 추적을 통해 측정된다. 발생된 모든 전환을 관찰할 수 없는 경우엔 <b>모델링된 전환</b>이 포함될 수 있다. 전환수 지표를 통해 고객이 광고를 통해 비즈니스에 가치가 있다고 정의된 행동을 얼마나 자주 했는지 알 수 있음. 그럼 구체적으로 어떤 액션이냐고? 캠페인 셋팅 시 추적하고자 클릭했던 모든 액션을 의미한다.<br>

그림 1. 구글애즈 캠페인 단계에서 선택하는 전환 목표
![이미지1](/img/posts/mkt/7_googleads/1.png) <br>



<br>
* * *
<br>



#### 1.2   모델링된 전환
* <b>개념</b> <br>
구글에서 직접 관찰할 수 없는 전환을 추정 ,즉 예측한 정보. <br><br>

* <b>설명</b> <br>
구글은 광고 상호작용과 온라인 전환을 수신하지만, 두 항목 사이의 연결 관계는 알 수 없다. 따라서 구글은 이 모델링은 전환 발생 여부가 아닌 구글 광고 상호작용이 온라인 전환으로 이어졌는지를 분석한다. 분석 작동원리는 어떻게 될까? <br><br>

* <b>작동 원리</b> <br>
1. 특정 브라우저에서는 관찰할 수 없지만 다른 브라우저 유형에서 관찰할 수 있는 전환 슬라이스 데이터가 있다고 가정하자.
2. 구글은 먼저 브라우저 유형에 따른 사용자의 행동(예: 전환율)간의 추세를 파악한다.
3. 그리고 측정 가능한 브라우저에서 관찰 가능한 데이터와 모든 체계적 편향을 함께 사용하여 기기유형, 시간, 지리적 위치, 운영체제와 같은 기타 집계 정보를 통합한다.
4. 이를 기반으로 관찰할 수 없는 브라우저 유형에서 광고 상호작용의 전환 이벤트 발생 가능성을 예측한다.<br><br><br>

* <b>모델린된 전환 지표 사용시 이점</b> <br>
캠페인을 보다 더 효과적으로 최적화하고 비즈니스 결과를 개선할 수 있다.
<b>이유는?</b> <br>
개인 정보 보호 규제 및 기술적 제한 사항으로 인해 구글에서는 특정 사용자 집단(예: 동의하지 않은 사용자/ 특정 기기 유형 및 브라우저 사용자)을 관찰하지 못한다. 따라서 구글의 자동 입찰 알고리즘은 불완전한 데이터를 바탕으로 최적화 결정을 내려야 하고, 그 결과는 편향된 학습을 발생시킨다.


<br>
* * *
<br>


#### 1.3   총전환가치
‘전환'에 대한 전환 가치의 총합을 의미한다. 이 지표를 확인하고 싶다면 아래 경로에 진입하여 전환 액션별 가치를 입력해야 한다. <br>

<b>경로</b>: 도구 및 설정 -> 측정 -> 전환 <br><br>

그림 2. 구글애즈 전환별 가치 입력 위치
![이미지2](/img/posts/mkt/7_googleads/2.png) <br>


<br>
* * *
<br>


#### 1.4   비용당 전환 가치
비용당 전환가치를 알 수 있다면 ROI를 예상할 수 있다. 비용당 전환가치를 구하는 수식은 다음과 같다. 수식을 보면 알겠지만 쉽게 설명하면 유저로 하여금 클릭/전환 등의 상호작용을 n회 만들어내는데 사용한 모든 비용 중, 각 전환이 만들어낸 총 가치가 어느정도의 비율을 차지하는지를 의미한다. 그렇기 때문에 이 지표를 통해 광고비 대비 투자수익율을 알 수 있게되는 것이다.

![이미지3](/img/posts/mkt/7_googleads/3.jpeg) <br>




<br>
* * *
<br>



#### 1.5   조회 후 전환정보
* <b>개념</b> <br>
고객이 광고를 본 직후 바로 광고와 상호작용하지 않고, 나중에 사이트에서 전환을 완료할 때에 계산되는 지표이다. 교차 사이트 쿠키를 허용하지 않는 브라우저에서 발생한 조회 후 전환은 보고되지 않는다.  고객이 광고와 상호작용한 후 사이트에서 전환을 완료할 때를 기록하는 다른 전환 열과는 데이터 산정 및 적재 방식이 다르다. <br><br>

* <b>활용</b> <br>
디스플레이 / 동영상 광고 캠페인에 가치를 추적하는데 사용할 수 있는 유용한 기능이다.
 <br><br>

* <b>참고(조회 가능 노출)</b> <br>
디스플레이 네트워크 광고의 경우, 마지막 조회 가능 노출에서 조회 후 전환이 발생한다. 구글의 Active View기술을 활용하면 디스플레이 광고가 최소 1초동안 50%이상 화면에 표시될 때 노출을 조회 가능 노출로 간주하게된다. <br><br>

* <b>참고(조회후 전환/ 모든 전환수 열성과지표):</b> <br>
조회 후 전환 정보는 다른 광고와 상호작용한 사용자의 전환을 자동으로 제외한다.
따라서 ‘전환수'열에 포함되지 않고, ‘조회 후 전환' 및 ‘모든 전환수'열에만 표시된다.


<br>
* * *
<br>

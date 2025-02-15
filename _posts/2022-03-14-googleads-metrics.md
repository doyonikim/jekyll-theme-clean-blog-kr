---
layout: post
permalink: /marketing/dcando_googleads_metrics_1
title: '내가 몰라서 정리한 구글애즈 전환지표 개념'
date: 2022-03-13 09:30:00 +09:00
feature: '/img/posts/mkt/5_metabus/dangdangpe-metabus-gathertown-marketer-intern.jpeg'
background: '/img/posts/mkt/5_metabus/dangdangpe-metabus-gathertown-background.jpeg'
categories:
- category-marketing
tags:
  - 구글애즈
  - 구글애즈 전환지표
  - 전환
  - 전환가치

description: '구글애즈 전환지표 정리'
---



## 1. 전환수?
전환 액션을 통해 발생한 전환의 횟수. 전환수는 전환 추적을 통해 측정됨. 발생된 모든 전환을 관찰할 수 없는 경우에, 모델링된 전환이 포함될 수 있음. 고객이 광고를 통해 비즈니스에 가치가 있다고 정의된 행동을 얼마나 자주 했는지 알 수 있음.




### 1.2   Map 만들기
템플릿을 찾다보면 'Blank'가 나온다. 생성해보면 아무것도 없는 빈공간이 표시되는데, 여기서 중요한 건 좌표 X:0, Y:0을 중심으로 맵을 생성해야 한다는 점. 좌표를 맞추지 않고 맵을 제작하게 되면, 추후 번거로운 상황이 발생할 수도 있으니 참고하자.<br>
![이미지3](/img/posts/mkt/5_metabus/metabus_atoz/ddp3.jpeg) <br>

<br>
* * *
<br>


## 2. 바닥, 벽은 어떻게 만들어요?
자, 공간을 생성했다면 이제 본격적으로 맵을 만들어보자. 이제부터 상단의 Save를 잊으면 안된다!<br>




### 2.1  바닥 타일과 벽 만들기
1. 좌측 상단의 'Walls&Floors' 클릭<br>
2. 마음에 드는 바닥재와 벽재 선택 후 바닥에 깔아주기<br>
3. 상단의 'Done' 클릭 시 생성 끝!<br>

<br>
* * *
<br>


## 3. 타일 이펙트는 어떻게 적용해요?
 바닥 타일과 벽지를 설정했으니, 이제 타일 이펙트 종류에 대해 알아보고, 어떻게 설정하면 좋을 지 설명하겠다.<br>

 ![이미지4](/img/posts/mkt/5_metabus/metabus_atoz/ddp4.jpeg) <br>


### 3.1  타일 이펙트 종류

##### 3.3.1 −  Impassable<br>
주로 공간을 구분하거나, 유저가 오브젝트 위를 지나다니지 않도록 할 때 사용한다. Impassable로 설정해둔 공간은 그 누구도, 어떤 방법으로도 지나갈 수 없다.<br>


##### 3.3.2  −  Spawn
게더타운에 처음 진입한 유저의 아바타가 놓여지는 공간은 운영자가 'Spawn' 지역으로 설정해둔 공간. 또한, 맵 내에서 다른 방으로 이동할 때 그 방의 시작 포인트를 설정하는 역할을 함(방을 따로 생성하는 방법은 추후 설명 예정).<br>


##### 3.3.3  −  Portal
해리포터에서 포탈기능이 있는 특정 물건을 잡으면 다른 공간으로 순간이동이 되는 것처럼 게더타운도 마찬가지다. 먼 거리를 한번에 이동하거나, 다른 방으로 이동할 때 사용한다 (아예 다른 게더타운 채널로도 보낼수도 있음).<br>



##### 3.3.4  −  Private Area
게더타운 내에는 Zoom과 같이 화상 채팅 기능과 화면 공유 기능이 있다. 'Private Area'로 설정된 공간 내부에서는 그 방에 있는 사람들끼리만 대화 및 화면 공유가 가능하다. Zoom 소회의실을 생각해주면 됨!<br>



##### 3.3.5  −  Spotlight
Spotlight 타일을 설정해두면 타일 위에 있는 사람의 음성과 캠 화면이 해당 공간 안에 있는 모든 사람들에게 들리고 보이게 된다. 단, 다른 방에 있는 사람들에게는 표시되지 않는다. 세이브는 이벤트 공지사항을 전달하거나 당당토크쇼 강연자분들을 위해 해당 기능을 사용했다.<br>


하지만, 이 기능은 다수가 참여하는 방에서는 잘 사용되지 않으니 참고할 것. 타일 이펙트로 'Spotlight' 기능을 사용하는 것 보다, 운영자가 특정 사람을 지정해서 'Spotlight' 시킬 수 있는 기능이 보다 더 편리하기 때문.<br>





### 3.2  타일 이펙트 종류별 설정 방법


##### 3.2.1  Impassable, Private Area, Spotlight
이 세 유형은 바닥타일과 벽을 생성하는 방법과 동일하니 위 2번을 참고.<br>
![이미지5](/img/posts/mkt/5_metabus/metabus_atoz/ddp5.jpeg) <br>



##### 3.2.2  Private Area
'Private Area'는 'Area ID' 작성으로 구분. 단순하게 구역의 이름을 정해준다고 생각하시면 됨. 넘버링을 해도 되고, '기획팀' '마케팅 1팀' 등의 ID를 정해주어도 무관.<br>
![이미지6](/img/posts/mkt/5_metabus/metabus_atoz/ddp6.jpeg) <br>


바닥타일, 벽을 생성하는 방법과 동일. Area Id 아래, Color tiles를 체크했다면 아래 사진에서 보이는 것처럼 구역들이 표시된다.<br>


##### 3.2.3  Portal
우선 아바타를 순간 이동 시킬 포탈 구역을 선택하자.<br>


1. 포탈 타입 선택
        → Portal to a room : 현재 space 내부의 맵이나 방으로 보내는 기능.<br>
        →  Portal to another space: 나, 혹은 타인이 생성한 공간으로 보내는 기능.<br>

2. 포탈 출구 장소 선택
        → Portal to a room : 현재 Space에서 포탈을 설치할 장소를 선택하는 기능.<br>



3. 포탈 출구 타일 선택
        → 포탈 출구를 설치할 타일을 선택.<br>



다음 2편에서는 맵 안에 방을 만드는 방법, 오브젝트 및 인터랙션 삽입에 관해 설명하겠다.

<br>
* * *
<br>

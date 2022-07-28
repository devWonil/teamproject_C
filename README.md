## :meat_on_bone: 치킨 배달 게임 프로젝트 :meat_on_bone:


제작 기간은 1주이며 총 3명이 합작하여 만들었습니다.




### 게임설명

 플레이어가 치킨집을 운영하며 직접 치킨을 조리하여 배달까지 하는 치킨집 경영 게임입니다.
 
 
 

 ### 주요 클래스 설명
 - [Player](#player)
 - [Moveable](#moveable)
 - [BackgroundMapFrame](#backgroundmapframe)
 - [BackgroundKitchenMapFrame](#backgroundkitchenmapframe)
 - [BackgroundDeliveryMapFrame](#backgrounddeliverymapframe)
 - [Chicken](#chicken)
 - [Sales](#sales)



### Player
- 사용자가 조작하는 플레이어
- JLabel 클래스, Moveable 인터페이스 구현하여 플레이어 동작 정의
- 상, 하, 좌, 우로 이동할 수 있는 메소드 존재, Thread 사용


### Moveable
- 플레이어와 치킨의 동작 정의를 위한 인터페이스


### BackgroundMapFrame
- JFrame 클래스, 게임이 실행되는 틀
- 키 이벤트 발생시 플레이어 동작 메소드 호출, 방향키로 동작하는 플레이어
- 버튼 클릭 이벤트로 맵 이동 


### BackgroundKitchenMapFrame
- 주방 맵에서 플레이어와 외벽, 바닥과의 충돌 검사하는 코드 작성


### BackgroundDeliveryMapFrame
- 배달 맵에서 플레이어와 외벽, 바닥과의 충돌 검사하는 코드 작성


### Chicken
 - JLabel 클래스, 치킨의 조리 단계에 따라 다른 치킨 이미지
 - Thread 사용하여 별도의 조작없이 정해진 위치에서 움직이는 이미지 구현
 
 
### Sales
 - JLabel 클래스, 게임이 시작하고 배달을 완료함에 따라 올라가는 매출
 - 목표 매출 달성시 매출 리셋됨
 


https://user-images.githubusercontent.com/102580743/181428446-ed0e87f6-35d8-4c19-bd2e-6315af2c5483.mp4


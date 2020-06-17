# BeMyAlarm

미확실 프로젝트  (보류중)


현재 SRS 작성 및 디자인 작업중 

(그러기 위해 다른 알람 앱들 모양들이나 기능들도 보고있고...

디자인 툴 adobe xd 받아서 사용 해 보는중.. )



## 만들 기능

- 기본 알람기능 제공

- youtube 링크를 통해, 알람 대신, youtube로 알람 열기  

- 친구 추가, 친구에게 녹음한 내용 알람으로 전송, 친구는 해당 음성 이 울림 

( 이 기능 때문에 미확실 프로젝트 ) 

  ~ 확인 결과 .. 노즈모드 ( 화면잠금상태 ) 에서는 온라인 사용이 불가능. 더 알아봐야할듯.

## work flow
![workflow](https://user-images.githubusercontent.com/36880919/81048236-e9924e00-8ef6-11ea-8b8e-d13355b274e3.png)





## 기능 요구사항 

|번호|내용|진행|
|-|-----|--|
|1| 기본 알람 기능 제작||
|2| youtube 링크 작동 ||
|3| 로그인 기능 구현 ||
|4| 친구 추가 기능 구현 ||
|5| 녹음 기능 구현 ||
|6| 녹음 내용 전송 구현 ||
|7| 전송 성공 시 상대 폰에서 울리는지 확인||
|8| 알람 목록 리스트 구현 ||
|9| 일반 알람에서, 진동 온 오프 기능 ||
|10| 일반 알람 <=> youtube 알람 스위칭 기능 ||
|11| 설정된 알람을 수정 가능 하도록 ||
|12| 친구에 대한 삭제/ 차단 기능 추가 ||


- #1 포그라운드 서비스로, 노티바 또한 구현 해야 함. 

- #3 FIREBASE AUTH 사용

- #3/4 닉네임 기능 또한 구현. 중복 불가 

- #10 token 만들어서, visible / gone 설정


## 비기능 요구사항 
|번호|내용|진행|
|-|-----|--|
|1|녹음 기능 제한 ||
|2|알람에 게임 기능 만들기? ||

- #1 녹음 시간에 제한을 두어, 너무 많은 트래픽, 데이터가 발생 하지 않도록 제한


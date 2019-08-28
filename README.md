# Gabyscone-Game

### 개 요
----
`Last man stading`의 모바일 버젼으로 `Unity`로 앱을 제작하고 기본적인 서버 개발에 중점을 둔다.

### 구상도
#### Andorid Client
- `Last man stading`의 게임 룰을 베이스로 개발한다.
    ``` 
    게임의 룰은 아래와 같다.
    1. 내가 유저라는 사실을 숨겨야 한다.
    2. 움직이는 캐릭터 중 유저를 찾아야 한다.
    3. 제한시간 내 가장 많은 유저를 찾은 사람이 승리한다.
    ```
    
#### Login Server
- 로그인 서버는 FireBase로 개발한다. 굳이 별도로 
    서버를 운영할 필요 없이 `FireBase`의 *Authentication* 기능을 사용하여 토큰을 받도록 하고 `FireBase`의 *DataBase*에 리프레시 토큰을, `Android` 내부 *DataBase*에 **Login Token**을 넣어 사용하도록 한다.

#### Socket Server
- 멀티 플레이를 위한 실시간으로 제어가 가능한 서버가 필요하다. `C#`으로 개발할.. 예정

#### Ranking Server



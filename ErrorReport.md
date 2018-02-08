# Error Report

## Project Setting

### IDE
#### 01 IntelliJ 입력모드

___Problem___
- ctrl키를 사용한 단축키사용, 텍스트 드래그나, Delete 키 사용. 기본적인 타이핑을 하는데 인텔리제이를 사용할 떄 평소에 사용하는 방식이 아닐 때가 있다.
- 이것은 기본적으로 입력모드가 안되고 a버튼을 눌러야 입력모드로 들어가서 타이핑이 가능하다는것이다. 
    - 맨 앞줄에서 왼쪽 화살표 키를 누르면, 바로 윗줄의 맨 끝으로 이동하는 기능이 안먹는것.
    - 텍스트를 드래그한 후, delete키를 누르면 지워지지 않거나, Insert 입력모드 상태 등.
    
___Solution___
- Preferences-> plugin검색 ->ideavim 플러그인을 제거하기.
- 리눅스, 유닉스 환경에서 사용되는 vi/vim의 입출력모드와 같은 것으로 플러그인을 제거하거나 체크해제를 하면된다.


___More___
- [StackOverFlow Q&A Link](http://stackoverflow.com/questions/26788552/intellij-14-weird-editor-cursor-behaviour)
- [other Blog Link](http://geneus.egloos.com/3536401)

</hr>

### Kotlin Project
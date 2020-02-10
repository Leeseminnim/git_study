# CLI 와 Git
## CLI(command Line Interface)

CLI는 컴퓨터 운영체계나 응용 프로그램과의 사용자 인터페이스로서, 사용자는 프롬프트가 나타나면 정해진 줄 위에 명령어를 입력하고, 시스템으로부터 이에 대한 응답을 받은 다음, 또다시 다른 명령어를 입력하는 식으로 진행된다.   

윈도우 운영체제의 경우 cmd를 실행하면 CLI 명령어로 입력의 조작을 할 수 있으며 맥의 경우 내장되어 있는 터미널에서 CLI 명령을 수행할 수 있다.

### CLI 명령어

- cd (디렉토리 이동) - change directory
- mkdir (디렉토리 생성)
- rmdir (비어있는 디렉토리 삭제)
* mv (이름 및 이름변경)
* cp (복사)
* rm (파일 또는 디렉토리 삭제)
* touch (빈 문서 생성)
* echo (내용이 있는 문서 생성)
+ clear (화면 지우기)
+ pwd (현재 디렉토리 위치 조회)
+ history (명령어 히스토리 조회) -사용했던 내역


## Git 버전 관리
Git은 분산버전 관리 시스템이다.

작업한 파일을 로컬 저장소뿐만 아니라 원격 저장소에도 배포하여 저장할 수 있으며 작업 이력을 관리하고 분기하여 원하는 시점으로 파일을 복원하거나 통합할 수 있다.

원격 저장소를 이용하여 팀 단위로 협업이 가능하고 버전 별로 일관된 관리 시스템을 제공하여 소스의 품질을 보장할 수 있다.

### Git 명령어
1. Git config --global user.name "사용자 이름"
2. Git config --global user.email "이메일 주소"
3. Git init (Git 저장소로 초기화 하기)
4. Git status (상태 확인하기)
5. Git add (커밋 대기 상태)
6. Git commit -m (커밋 생성하기)
7. Git commit --amend (커밋 수정하기)
8. Git tag [태그이름] (태그 삽입하기)
9. Git remote add origin "원격 저장소 URL" (원격 저장소 등록하기)
10. Git push origin master -u (원격 저장소로 보내기)
11. Git clone [원격 저장소 URL] (원격 저장소의 내용을 로컬 저장소로 복제하기)

  
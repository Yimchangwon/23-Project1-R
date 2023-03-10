# 임창원

## 첫수업 (230302)

### R 언어를 사용해서 수업을 진행 (교재 난생처음 R코딩&데이터분석 -> 한빛소프트)

- R 라이브러리 잘 되어있어서 쉽게 데이터 분석 가능함
- R-Studio 사용할거임

* R언어로 수업을 계속 할지 말지 수업하면서 상의해보자

리액트(자바스크립트의 라이브러리)를 얘기하심 -> 나중엔 이거 배울수도 있음


### 학점 부여 기준
- 출석 20% -> 1주일 이내에 수정안하면 수정안됨 (출장(출장증빙자료), 예비군, 병원(처방전 복사본) 사진 찍어서 단톡방 or 개인 메시지 전송을 1주일 안에 해야함)
- 수행 20% -> 별도 평가를 하는건 아니고 배운거 정리해서 git-hub에 README 파일 올리면 그걸로 평가함 (시작시점 별도로 얘기해줌)
- 중간고사 30% -> 실기
- 기말고사 30% -> 실기

[중간/기말고사] 
작업지시서 (짧게는 15개 많게는 20개이상)
프로젝트 이름은 뭘로 하고,
데이타를 어떻게 가져와서 어떻게 처리해서 가공은 어떤 함수를써라 이런 느낌으로 함

### Github
1. 버전 관리를 위함 (개인용)
2. 팀 프로젝트 내 협업을 위함
3. 스크립트 롤백을 위해 사용함
4. 분산 프로젝트 관리


### Semantic Versioning
* 배포버전.기능.픽스된오류 (버전 표기 방식 - 맨 처음은 0.1.0 -> 릴리즈하면 1.0.0)
누가 봐도 알 수 있는 버전 양식을 갖춤
* 유의적 버전 명세 (https://semver.org/lang/ko/)

### Git 설치
설치 유무 확인 : CMD -> git -v (Git 버전 확인)
1. 구글에 git 검색 -> 모니터 모양에 다운로드 버튼 클릭 -> Standalone Installer에서 OS 환경에 맞게 다운로드
2. 디폴트로 설치 (Next 연속 클릭)
3. 버전 확인(설치가 잘 되었는지)
4. 다운로드 받은 페이지에서 Downloads 밑에 CUI Clients 진입해서 구경함

### VScode 설치
1. 홈페이지에서 다운로드
2. VScode 서브메뉴 (왼쪽 아이콘) 내 Source Control 이 Git 이다.
3. Ctrl + ~ 하면 터미널 나옴
4. Initialize Reposite 클릭 
5 .Explorer에서 파일을 하나 생성하면 Source Control에 1이 표시됨
6. 작업 후 저장하면 Source Control에 Commit 버튼 표시됨
7. 커밋 메시지는 첫줄(제목) 58자 이내로 작성 후 엔터 두번 치고 설명은 글자 수 제한 없음
위 내용을 작성하고 커밋 버튼 클릭 시 알림창 나타남 (Stage를 거치지 않고 .Git 폴더에 바로 커밋할거냐고 물어보는 팝업임)
8. 다수의 스크립트 파일중 일부만 커밋할 경우엔 Stage를 거쳐야됨
해당 알림창을 Close로 닫고 좌측 서브 트리에서 작업한 스크립트에 마우스를 올리고 + 버튼을 클릭하면 Stage에 들어감 (Staged Change)
이후 커밋 버튼을 다시 클릭하면 깃을 등록하라는 경고창이 나타남
9. git 등록 명령어 -> git.bash에서 아래 명령어를 순서대로 입력한다
- 1. git config –global user.name “사용자 이름”
    -  “”가 들어간 이유는 안의 내용에 스페이스가 포함되었기 때문 스페이스가 없다면 생략 가능
- 2. git config –global user.email 이메일
    - 사용자 이름과 이메일을 제외하고 명령어 입력 시 현재 사용자와 이메일 정보가 나타남
        
- global 옵션을 빼면 로컬 환경이 아닌 공용환경에서 쓰기 좋다.
10. 그리고 커밋하면 알림창에서 바로 커밋할거냐 나오고 Yes 누르면 커밋됨
프로젝트명 옆에 필터같은 아이콘(git graph) 누르면 커밋 현황 볼 수 있음(그 전에 Extensions 에서 git graph 다운받음)
11. README.md 로 수업내용 올리면 됨


### md 사용 예시

# h1 tag
## h2 tag
### h3 tag
* 아스터리스크
- 하이픈
```
빽핑? (code 넣는곳)
```


```html
<div id="임창원"> 블라블라블라 </div>
```


```java
if(i=1)
{
    System.out.println("색깔이 달라용");
}
```
----------------------------------------------------------------------
## 지난시간 이어서 Git에 대한 수업 진행 (230309)

### 1. git 버전확인 하는 방법은 두 가지가 있음
- git –version
- git -v

위의 두 가지 중 하나는 무조건 되므로 기억(환경에 따라 먹는 명령어가 다를 수 있음)

### 2. git hub 계정 생성
### 3. 번역 프로그램 - deepL 파파고보다 4배 정확한 번역해줌
### 4. 커밋 내용 작성에 첫줄은 제목이라 50 char 까지만 사용가능 (엔터 두번 입력 후 내용은 무한으로 사용가능)

### Git hub로 push 하기
* 1. source tree 이동 후 SOURCE CONTROL 문구 옆 케밥 메뉴 클릭 -> Push 선택 -> 아직 Repository(저장소) 없다는 팝업 발생 -> Add Remote 클릭 -> Github에 만들겠냐는 문구 표시 -> 원하는 reposite 선택
* 2. Publish Branch 버튼 클릭 -> GitHub에 사인이 안되어 있다는 팝업 발생 (연동하기 전에 시스템의 기본 브라우저(크롬) 이용하여 Git hub 접속 -> 로그인) -> Allow 버튼 클릭 -> 연동되는데 저장소 2개 나옴 -> 위에는 Private 모드 저장소 아래는 Public 모드 저장소 -> 교수님에게 공유 할 거니까 Public으로 함

### Git hub Repository 지우기
- 해당 Repository 진입 후 Settings 맨 아래 Delete this Repository 클릭 후 해당 Repository 명 입력 시 삭제됨 (바로 윗 줄 복사 붙여넣기 하면 됨)

# 이론수업 시작

## 1. 프로그래밍이란 무엇인가요?

### 컴퓨터의 구성
- 하드웨어
- 소프트웨어

### 프로그래밍과 프로그래밍 언어
- 프로그래밍 : 요리하는 과정에 비유 할 수 있음 (정해진 절차에 따라 수행해야함)
    - 컴퓨터가 해야 할 작업의 순서를 논리적으로 명시
- 프로그래밍 언어
- 단순 명령어세트 : 애플에서 사용(M1, M2) 단순 명령어를 처리 (CPU 부하 적음)
- 복잡 명령어세트 : 복잡한 명령어를 처리 (CPU 부하 많음 - 기기 뜨거워짐)
    - 대표적인 프로그래밍 언어 : C, JAVA, Python 등
    - 1965~2019 순위 : C > JAVA > Java Script > C++ > PHP > Perl > Visual Basic...
        - R은 데이터 관리 언어인데도 불구하고 순위권 안에 들어가있음 (아주 드문 경우)

## 2. R 언어에 대해서 알아봅시다.
### 1. R 언어의 특징
- S-PLUS의 무료버전
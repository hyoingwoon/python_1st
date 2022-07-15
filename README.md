# README.md

## 여기가 저장소가 될 위치(디렉토리) 입니다.

### 저장소를 만들 위치에 README.md 파일 생성하기

vscode를 열었는데 터미널이 안보여요!

=> vscode 메뉴의 터미널 메뉴 => 새 터미널 선택

vscode의 터미널을 파워쉘이 아니라 git bash 로 바꾸기

1. '+'버튼 누르고 기본 프로필 설정
2. 화면 위쪽에 선택 가능한 프로그램 목록이 뜨는데 거기서 git bash 선택(git 이 설치 되어있어야 한다.)
3. 기존의 파워셀 터미널은 휴지통 버튼을 통해 제거
4. 다시 새터미널을 생성해서 bash 로 되어있는지 확인

git init 명령어를 통해 저장소를 버전관리 하겠다고 설정

# 터미널을 사용할 때 (cli)현재 작업경로가 내가 원하는 경로와 맞는지를 꼭 확인하세요!!

**git config --global user.name** " 깃허브 유저네임"

**git config --global user.email** "깃허브 이메일"

-global 옵션은 전역으로 설정하겠다는 뜻입니다.(현재 작업영역 외에도 똑같이 사용)

README.md

git add. : 현재 작업영역의 모든 파일 staging area에 올리기

git commit -m"커밋 메시지":staging area에 있는 관리 대상 파일 모두 commit,-m은 메시지를 남길수 있는 옵션입니다.

git remote add origin "깃허브 레포지토리 url":어떤 원격 저장소에 깃 작업을 할건지 등록

git push origin master : 내가 지금까지 커밋한 내용(파일들) 원격 저장소에 업데이트

git 인증 방법 : settings->developer settings->personal aceess tokens 가서 토큰 발급받기

(웹으로 인증하라고 알림이 뜰시엔 초록색 버튼 누르면 인증 완료)

발급한 토큰은 다시 볼수 없으므로 꼭 메모장 같은곳에 저장하기!

expiration date : 토큰의 만료기간

권한 설정 :repo부분만 체크(저장소 관련 권한)

git clone "깃허브 레포지토리 url" 해당 원격 저장소에 있는 파일들 현재 작업 영역으로 복사

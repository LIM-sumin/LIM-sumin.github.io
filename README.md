# **프로젝트 build 과정**
### 1.github repo 만들기
#### git blog를 저장할 저장소를 아이디와 github.io를 붙여 제작하였습니다.
#### 로컬저장소와 원격저장소를 git clone을 통해 연결시켜 주었습니다.

### 2. jekyll 설치
#### 루비를 먼저 설치를 해 준 다음에 jekyll new . --force 명령어를 통해 현재 디렉토리에 jekyll을 설치한다. jekyll -v 명령어를 통해 설치를 확인할 수 있다.

### 3. jekyll 실행
#### bundle exec jekyll serve 명령어를 통해 jekyll serve를 실행 후, localhose;4000에 접속하여 기본 테마로 된 jekyll 사이트를 확인할 수 있다.

### 4. 테마 설정
#### 저는 layon테마를 설정하였고 해당 원격저장소를 git clone하여 테마를 받아올 수 있다. _posts, config.yml, REAME.md는 사용자의 취향에 맞게 수정하였다.

### 5. 댓글 적용
#### 댓글 기능을 추가하기 위해 disqus라는 플랫폼을 사용하였다. diqus 사이트에 가입한 후에 installing disqus 페이지에 있는 코드를 복사하여 _config.yml에 추가하였다.

# **에러**
### 1. css 에러
#### 분명 코드를 맞게 입력했음에도 블로그 화면이 깨져서 나왔다. 그래서 config.yml에 있는 baseurl을 삭제하였고 url 본인의 블로그 주소를 기입하였다.

### 2. 병합 과정
#### 외부에서 코드를 수정하느라 원격저장소를 수정허였다. 그 후 로컬 저장소에서 내용을 수정하였더니 충돌이 발생하였다. 그래서 git pull 명령어를 통해 병합을 해주었다.



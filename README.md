## 💻 My First Time Git

> Github 접속 및 가입

➡️ Your repositories —> new —> Repository name: Medicines —> Public —> Create Repository

<br>

> terminal

$ brew install git ➡️ git 설치.

$ git config --global user.name “Aneunkyoung” ➡️ Github push용 이름 세팅.

$ git config --global user.email “lindsayan991128@gmail.com” ➡️ Github push용 이메일 세팅.

$ git config --list ➡️ Github push용 이름 및 이메일 확인.

$ cd /Users/eungyeongan/Desktop/medicines ➡️ push 할 프로젝트 파일에 접속.

$ git init ➡️ push 할 프로젝트 초기화.

$ git add . ➡️ 현재 및 하위 디렉토리 모든(.) 파일 index 추가.

$ git status ➡️ 파일이 잘 등록되었는지 확인.

$ git commit -m "first commit" ➡️ local repository에 추가.(히스토리 만들기) ➡️ ex) 최종, 진짜 최종, 마지막 최종, 찐막

$ git remote add origin https://github.com/Aneunkyoung/medicines.git ➡️ 내 프로젝트와 깃의 연결고리.(원격저장소와 연결 세팅)

$ git remote -v ➡️ 연결한 주소가 뜨면 성공.

$ git push origin master ➡️ remote repository에 추가.


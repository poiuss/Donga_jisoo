**\[GitHub 메모 - 지수용]**



**0) 처음 1번만(또는 확인)**

git config --global user.name "poiuss"

git config --global user.email "88subini@gmail.net"



**확인**

git config --global --get user.name

git config --global --get user.email



**1) 완전 새 폴더를 GitHub에 처음 올릴 때**

(왜) 이 폴더를 Git 저장소로 만들고, 첫 업로드를 한다.



git init

(왜) 이 폴더에 .git이 생기고 Git이 관리 시작함



**git branch -M main**

(왜) 브랜치 이름을 main으로 통일



**git add .**

(왜) 올릴 파일을 "스테이징"에 올림



**git commit -m "첫 업로드"**

(왜) 스테이징된 파일을 하나의 기록(커밋)으로 저장



**git remote add origin https://github.com/아이디/저장소이름.git**

(왜) 내 폴더와 GitHub 저장소를 연결



**git push -u origin main**

(왜) GitHub로 업로드 + 이후 push 기본 대상 설정



**2) 업데이트(수정/추가 후 반복)**

(왜) 바뀐 것만 다시 기록하고 GitHub에 올린다.



git add .

git commit -m "설명"

git push



**3) push 인증**

Username: poiuss

Password: GitHub 비밀번호가 아니라 토큰(PAT)






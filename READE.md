git init : 로컬의 Git 저장소를 설정한다.
git remote add origin <remote repository url> : origin이라 이름으로 원격 저장소가 등록 되었다는 의미
git commit : 인덱스에 추가된 변경 사항을 이력에 추가하는 것 한마디로 현재 상태 저장
git push origin <branch name> : git add .  commit 을 진행한 후 원하는 브랜치로 push하여 원격 서비스에 전송 하는 것
git pull origin <branch name> : 원격 저장소의 내용을 현재 디렉토리로 가져오는 것
git merge <branch name> : 현재 브랜치에 다른 브랜치 수정사항 병합을 한다.

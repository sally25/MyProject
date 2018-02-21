mkdir ~/myproject
cd ~/myproject
git init # 깃 명령어를 사용할 수 있는 디렉토리로 만든다.
git status # 현재 상태를 훑어보고
git add 파일명.확장자 # 깃 주목 리스트에 파일을 추가하고 or
git add . # 이 명령은 현재 디렉토리의 모든 파일을 추가
git commit -m "설명" # 커밋해서 스냅샷을 찍는다.

git remote add origin https://github.com/sally25/myproject.git # 로컬과 원격 연결
git remote -v # 연결상태 확인
git push origin master # 깃허브로 푸시


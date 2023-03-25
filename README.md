# git-command

git clone "https://github.com/jwk0224/git-command.git" "folder_name"
> 현재 경로에 원격 깃 저장소 복제 (폴더명 미지정시 현재 경로에 repository 이름과 동일하게 생성됨)

git init
> 현재 경로를 깃 저장소로 만들기

git status
> 현재 깃 저장소 상태 보기

git add .
> push를 위한 임의의 변경사항 추가

git add -A
> 현재 경로에 추가된 모든 파일 add

git add -p
> 현재 경로의 변경된 모든 파일 staging

git commit -m “message”
> 현재 경로의 변경사항 커밋

git push origin main
> 로컬의 최신 변경사항을 원격 main 브랜치로 push

git pull origin main
> 원격 main 브랜치의 최신 변경사항을 로컬로 pull

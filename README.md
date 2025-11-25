# git-
git 사용 설명서


git 명령어

bash	: 터미널

mkdir	: 새 폴더 생성 (Make Directory)
ls	: 현재 디렉토리 모든파일 출력
cd	: 이동 (Change Directory)
touch	: 새파일 생성, 기존 파일의 수정 시간을 최신으로 갱신
echo	: 문자열 출력 사용법: echo "작성할 메시지">[파일명]
nano 	: 텍스트 편집기를 실행하여 파일 작성/수정
cat	: 파일 내용을 화면에 출력하거나 여러 파일을 이어 보여주는 명령어

git init : 저장소(repository) 생성
ls -a

git status
git add | git add . | git add * | git add -A
git commit -m "message"
git push origin main : main 브랜치에 올림
git pull origin main : main 브랜치의 변경사항 가져오기
git 

git remote add origin <원격 저장소 URL>
git remote -v

#"master"일 경우
git branch -M main : main으로 바꿈

git config --global user.email "you@example.com"
git config --global user.name "Your Name"

git log

git branch	: 브랜치 생성
git branch -b : 브랜치 생성 / 이동
git checkout : 이동

git Merge : 합치기

## 협업

git clone <원격 저장소 URL> : 레퍼지토리 복제
Collaborator 초대
PR(Pull Request): 작업한 코드를 팀원이 검토한 뒤 메인 브랜치에 반영하도록 요헝하는 절차





### git 이란

: 소스 관리 오픈소스 툴



- git init : .git 이 생성된다. 깃을 프로젝트 디렉토리에 생성한다. staging과 (working directory 생성) local repository 가 생성되어 변화 내용을 저장한다. 
- git add (파일 명) : staging 으로 옮긴다.
- git commit : 파일을 최종적으로 local repo에 저장한다. 
- git checkout : 커밋된 파일을 수정할 때 사용, local repo에 있는 것을 가져온다. 
- git push : 로컬 에서 remote repo에 업로드 한다.
- git pull : github remote repo에서 로컬 repo 로 가져온다.
- git brach : 현재 브런치를 보여준다.
- mater branch : 최종본 
- git status : 현재 staging 상태를 확인한다. 
- git checkout -- : 이전 상태로 복원한다.(local repo에 있는 것)
- git remote add origin (주소): origin은 별명, 원격 저장소에 연결한다. 
- git push origin master : master 브런치를 origin 에 올린다.
- git clone (주소) : 원격 저장소를 로컬로 가져온다.
- git diff (파일명) : 수정된 사항을 보여준다. 
- git pull :  최신 원격 버전을 로컬에 가져오는 것
- git pull/push (url) (branch)
- git branch (이름) : 특정 이름의 브런치를 만든다. 
- git branch : 브랜치 목록을 보여준다. (*) 가 현재 브랜치이다.
- git checkout (branch) : 현재 브랜치를 변경한다.
- git checkout -b (이름) : 브랜치를 만들고 그 브랜치로 변경한다.
- git merge (commit) : 커밋 버전을 master 브랜치와 병합한다.(마스터 브랜치에서 실행)
- git branch -d (branchname) : 브랜치를 삭제한다. 
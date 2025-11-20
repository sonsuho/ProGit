
git status -- 파일상태확인 (스테이징된 변경 사항 및 스테이징되지 않은 변경 사항 보기)

git diff -- 파일변경내용확인 (작업 디렉터리와 스테이징 영역에 있는 내용을 비교)

git log -- 커밋 기록 보기 (-p / --stat / --pretty)

git reset HEAD -- 스테이징된 내용 취소 (--soft / --mixed / --hard)

git restoe - 파일 되돌리기 (해당 파일 이전 commit 내용으로 되돌림)

git config - 깃 설정하기 (--local --list / --global)

git remote - 깃 저장소 관리 (--add / --remove / --set-url)

// git config로 현재 설정 확인 후 git remote로 저장소 변경 가능

git branch - 충돌 해결 (충돌 해결 브렌치를 생성하자!) 

// 충돌 해결 브렌치는 항상 내가 작업한 브렌치 아래로 만들자 (v11-merge-fix)

// 충돌 해결 브렌치에 충돌 발생한 브렌치를 merge 하자 (dev -> v11-merge-fix)

// 충돌이 발생 -> 충돌 해결하자! (인텔리제이의 충돌 해결을 사용하면 깔끔하고 좋다!)

git status -- 파일상태확인 (스테이징된 변경 사항 및 스테이징되지 않은 변경 사항 보기)

git diff -- 파일변경내용확인 (작업 디렉터리와 스테이징 영역에 있는 내용을 비교)

git log -- 커밋 기록 보기 (-p / --stat / --pretty)

git reset HEAD -- 커밋 취소 (--soft / --mixed / --hard)

git restore - 파일 되돌리기 (해당 파일 최근 commit 내용으로 되돌림)

git config - 깃 설정하기 (--local --list / --global)

git remote - 원격 저장소 관리 (--add / --remove / --set-url)

// git config --local --list로 현재 설정 확인 후 git remote로 저장소 변경 가능

// 개별 프로젝트마다 원격 저장소 다르게 설정하려면 git remote 사용해야함
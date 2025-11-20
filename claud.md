
git status - 파일상태확인 (스테이징된 변경 사항 및 스테이징되지 않은 변경 사항 보기)

git diff - 파일변경내용확인 (작업 디렉토리와 스테이징 영역에 있는 내용을 비교)

git log - 커밋 기록 보기 (-p / --stat / --pretty)

git reset HEAD - 커밋 취소 (--soft / --mixed / --hard)

git restore - 파일 되돌리기 (해당 파일 최근 commit 내용으로 되돌림)

git config - 깃 설정하기 (--local --list / --global)

git remote - 원격 저장소 관리 (--add / --remove / --set-url)

// git config --local --list로 현재 설정 확인 후 git remote로 저장소 변경 가능

// 개별 프로젝트마다 원격 저장소 다르게 설정하려면 git remote 사용해야함

git rebase - 머지와 마찬가지로 브렌치를 병합하지만 이력을 강제로 일자로 정렬함 (병합 시, 기존 커밋 이력을 그대로 쓰는게 아닌, 비슷한 새 커밋 이력을 생성해 뒤에 붙임)

// rebase는 이력을 수정하므로 머지할 브렌치가 포함하고 있는 커밋 이력과 충동이 발생하거나 이력이 꼬일 수 있음 => dev는 a b 이력을 가지고 있는데 rebase 해버리면 a b 이력이 없고 a' b' 이력을 가지게 됨 => 이력이 호환되지 않아 문제가 발생할 수 있음

// 머지와 리베이스 차이점 (머지는 합치는 과정이 그대로 기록 - 안전하고 이력이 명확하니 추적이 쉬움 / rebase는 커밋을 새 기반 위로 덮어짐 - 이력이 깔끔하지만 추적이 어려워짐 - 그래서 사용 X)

// 기본 팁 

// git diff --check 명령어 (탭과 스페이스 혼용, 또는 줄 끝에 공백이 있는 등 코드 스타일에 위배되는 부분을 검사)

// git stash - 미완료 변경 사항 스택에 저장 (list / apply / drop)

// git grep - 검색 (-n / --count)

// git revert - 커밋 이력은 유지하며 특정 커밋 되돌리기 (HEAD 사용해서 맨 위 커밋 되돌리기 가능 / REVERT를 다시 REVERT 하면 REAPPLY로 나옴)
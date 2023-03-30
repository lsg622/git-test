- `git init`
  = 깃허브를 이용하기 위한 초기 환경 초기화 실행.
- `git remote add origin <remote repository url>`
  = 깃 계정에서 설정한 repository 주소와 로컬파일과의 원격 연결을 설정.
- `git add <file name>`
  = 로컬의 변경 사항을 원격 브랜치에 수정 사항을 적용.
- `git commit`
  = 기능 구현, 수정 등 기존 사항과의 변경 작업 사항에 대한 내용을 남김. 다른 개발자들이 이해하기 쉽도록 커밋 메세지 커벤션을 참고하여 작성.
- `git push origin <branch name>`
  = 로컬 파일의 커밋 사항을 원격상의 브랜치(branch name)로 올리는 과정.
- `git pull origin <branch name>`
  = 원격상에 저장된 merge 파일을 로컬 브랜치(branch name)로 가져오는 과정.
  = 주니어 개발자는 바로 작업하는 곳으로 pull하지 말고
  = 작업 중이던 내용을 commit -m"wip(work in process - 작업중..)" 한 이후,
  = 로컬 메인으로 브랜치를 이동하여 원격 main을 로컬 main으로 가져 오는 순으로 작업을 진행 하는 것을 추천.
- `git merge <branch name>`
  = 원격에서 로컬 main으로 가져온 파일을 작업중인 파일과 merge를 하여 하나의 파일로 합치는 과정.
  = 원격 main을 로컬 main으로 pull 한 이후, merge하고자 하는 브랜치로 이동 후, merge하기를 원하는 브랜치에서 local main과 merge 하여 하나의 파일로 연결.

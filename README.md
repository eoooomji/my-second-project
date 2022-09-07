# TIL
### 리눅스 명령어
1. ls   
    list (목록표시)
2. cd   
    change directory (작업 경로 변경)
3. rm   
    remove (파일 삭제)
4. rm -r(파일명)   
    디렉토리에 파일이 존재할 때 삭제
5. rm -rf   
    무조건 적인 삭제
6. rm -rf .git   
    그 폴더의 git 확장자 제거하기
7. mkdir   
    make directory (작업 목록 생성)
8. rmdir   
    remove directory (작업 목록 삭제)
9. touch   
    파일 생성
10. cat   
    파일의 내용 출력   
11. pwd
    print working directory (현재 위치)
12. vi   
    파일 들어가기 혹은 파일 생성 후 들어가기


### Git
1. init   
    git 생성
2. add <파일명>   
    Staging Area(stage)에 파일 이동
3. commit -m '<메세지>'
    Repository로 이동
4. push <원격저장소> <브랜치>   
    원격(github)으로 이동
5. pull <원격저장소> <브랜치>   
    원격(github)에서 로컬로 복사 - 수정된 파일만 
6. clone <원격저장소> <브랜치>   
    원격에서 로컬로 복제 - repository전체
7. status   
    Staging Area의 상태, git의 상태
8. log   
    repository의 상태, commit된 상태
9. git commit --amend   
    바로 전 commit과 Stagig Area의 Merge를 할 때
10. git restore --staged <파일명>   
    Staging Area의 파일을 Working Directory로 가져옴

![Git Cheat Sheet](asset/gitcheatsheet.jpg)
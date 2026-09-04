하나로 통합하는 과정 = build

운영 main
테스트 dev     
         front
         back   (자신의 branch에 올린 후 dev에 올려주세요 라고 요청)
=> 다 완성되면 main 으로 최종통합
git flow 

=> 롤백 했을 때 어떤 문제가 생길지까지 생각해보기


main 최종 배포버전. 아무나 변경하면 안됨.   (최종용 별도 레퍼지토리를 맹금 : 주로 팀장님, 시니어님)
  

김연지  (이름 따라 레포지터리 생성) 


보통 회사에서는 main (최종배포)
본인 main
본인 branch
=> 본인 branch 에서 작업하다가 본인 main 에 업로드 하고 확인 후 회사 main 에 승인 후 업로드
다른 branch 에서 작업한거 아닌지 확인

first pull request
=> 처음으로 **** 을 요청하려고 해

git push origin main 0904_yeonji
=> branch 의 내용이 0904 에 갔습니다.

0904 yeonji 

switch 로 branch 와 main 왔다갔다 할 수 있음

commit : 로그와 함께 남길 수 있음
stash : 임시저장같은 상태

#git stash : 


** git switch 0904_yeonji


불필요한 branch 지우기
99_git 당겨오기 요청 compare&pull request
맨 위에 어디서 어디로 합치는지 적혀있음.

branch 에서 
=> 자신의 main 으로 합치기 => 그 다음에 전체 main 으로 합치기

Add a description (markdown 언어도 작성 가능)

긴급인지, 프론트엔드인지 마크 맹글어놓기 
마크 맹글어서 붙여넣기 

두번째 Pull Request 들어가보기 
=>또는 PR이라고 함
=>Merge pull request 

LGTM 

commit message 
이름 과 내용 적고 
merge pull request 

git stash pop
git stash list
변경사항 쓰고 switch 하면 안넘어가짐.

stash 해놓고 넘어가면 충돌 많이 남
웬만하면 넘어가기 전에 commit 을 해 줘야 함 

git -help

git -help a
git --help : 기본적인 애들

변경사항 입력하고 저장. 넘어가면 안넘어가짐. 저장 필요

git stash (임시저장)
git switch main
git switch

git switch branch 
git stash pop (불러오기)

git add .
git commit - m"fix:restore stashed lines"
저장소에 올라감

git hub 에 간 다음에 0904_jihyun 가면 변경
main 가서 추가

merge => confirm 

hotfix.배너수정

=>branch 없애기

폴더 안에 있으면 폴더 못지우듯이
branch 안에 있으면 branch 삭제 불가

branch 지우기 -d 

git branch

git add.

git commit -m: "fix: 0904_yeonji"

git push








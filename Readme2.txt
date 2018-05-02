오 연동됐어!!
 

git clone [주소입력]	-> 다운받고싶은곳을 클론하기
cd [주소파일]		-> 주소파일생성된 곳으로 들어가기
touch Readme.txt 	-> 시험용 리드미 파일 생성
git status		-> 새로 생성된 파일 상태 확인
git add Readme.txt 	-> 추가할 파일 깃에게 알리기
git commit -m "add Readme.txt"   -> 커밋작성하기
git remote -v 		-> 연동상태 확인하기
 (연동안되어있으면 git remote add origin https://github.com/username/myproject.git // 로컬과 원격 저장소를 연결 
git push origin master	-> 깃허브로 푸쉬하기
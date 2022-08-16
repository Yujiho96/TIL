cd ..  상위폴더로 이동
ls -a 현재 하위의 폴더나 파일 숨긴파일까지
ls -l 현재 하위의 폴더나 파일 자세한 부분까지 확인
mkdir 디렉토리 명 - 새로운 디렉토리 생성
mkdir .디렉토리 명 - 숨김처리
touch 파일.확장자 - 파일 만들기

mv 파일 이동
mv main.js sample - 현재 위치의 main.js를 sample 디렉토리로 이동
mv ../test.txt. - 상위 디렉토리의 test.txt를 현재 위치에 이동

cp 파일 복사
cp server.py ./server-copy.py  - 현재 위치에서 현재위치에 중복되지 않게 이>름을 수정해서 사본 생성
cp sample.md sample/  - 현재 위치의 sample.md를 sample 위치로 사본생성
cp ../server.py ./  - 상위 폴더의 server.py를 현재 위치에 사본 생성

rm 파일.확장자 - 파일 지우기
mv 기존파일.확장자 바꿀이름.확장자 - 이름 변경
rm -r 폴더/


### 환경설정

git config --list
git config --global user.name "깃허브 이름"
git config --global user.email "email 주소"
git config --global core.editor "vim"
git config --global core.pager "cat"
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --"

### github
1. github 접속
2. New repository
3. Code 주소 복사
4. git bash -> git clone 주소
5. cd 저장소이름
6. touch 파일생성
7. vi 파일 -> 내용작성
8. git status 상태확인
9. git add 파일
10. git commit -> 작업내용 작성
<pre - fix>
feat: features
docs: documentations
fix: bug-fix
refactor: refactoring
conf: configurations(poetry, requirements.txt)
test: test

11. git push origin main

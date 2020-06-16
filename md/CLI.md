# CLI 명령어

* pwd : print working directory, 현재 디렉토리 확인하기


* mkdir : make directory, 디렉토리 생성하기
```
mkdir fus13(디렉토리 이름)
mkdir test view 복수 디렉토리 생성
```
* cd: 디렉토리 이동하기
```
cd dev(디렉토리 경로)
cd ./ 현재 디렉토리
cd ../ 상위 경로로 1번 올라감
cd ../../ 상위 경로로 2번 올라감
cd ~/desktop 데스크탑 디렉토리로 바로 이동
```
* ls: list segments
```
fus13(디렉토리명) ls
ls -l 상세정보 함께 표시
ls -a 모든목록 표시
ls -a 모든목록 + 상세정보 표시
```
* touch: 빈 파일 생성
* echo: 간단한 내용이 들어있는 파일 생성
```
touch index.html(파일명)
touch fus13/index.html 디렉토리 안에 파일 생성
echo 'CLI 명령어' > fus13/index.html 디렉토리 안에 텍스트가 들어간 파일 생성
```
* cat: 파일 내용 확인하기


* rm: remove, 파일/비어있지 않은 디렉토리 삭제
```
rm fus13 (디렉토리/파일명)
rm -r fus13 폴더 내부 하위 디렉토리까지 모두 제거
rm -rf fus13 폴더 내부 하위 디렉토리까지 모두 제거 및 경고 없음
```
* rmdir: remove directory, 디렉토리 제거
```
rmdir fus13 (제거할 디렉토리명)
```
* mv: move, 이미 존재하는 파일/디렉토리의 경우 이름 변경 가능

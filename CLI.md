# Git 사용

Git은 특정 파일을 관리하는 프로그램이 아닌 **폴더 관리** 툴

## 디렉토리

### 기본 디렉토리

- 사용자 폴더(~로 표시)
- 가장 위로 올라가면 C 드라이브가 존재

## 기본 기능

- 파일 생성: `touch` 여러개를 만들고 싶으면 띄어쓰기 이용
- 폴더 생성: `mkdir`
- 파일을 폴더로 이동: `mv` *파일* **폴더**
- 특정 폴더로 이동: `cd` **폴더**
- 위로 가기: `cd ..`
- 최상위 폴더: `/`
- 삭제: `rm`
- 숨김파일: `.hidden.확장자`
- 파일 혹은 폴더 보기: `ls`
- 숨겨진 파일 혹은 폴더까지 보기: `ls -a`
- 



# Visual Studio 사용

## 시작하기

- `git init` 으로 시작
  - 되돌리기: `rm -rf .git`
- 디렉토리 옆에 `(master)`가 붙어있으면 **리포**가 된 것
- 해당 디렉토리 안에 있는 파일, 폴더 보기: `ls` 
- 숨겨진 폴더까지 보기: `ls -a`
- 파일 생성: `touch`
- git의 상태 파악: `git status`
- 이름과 메일 설정:  
  - `git config --global user.email "you@example.com"`
  - `git config --global user.name "Your Name"`















## 
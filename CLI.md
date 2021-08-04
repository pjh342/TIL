# 기초 CLI 명령어

>CLI : Command Line Interface
>
>GUI 환경인 윈도우와는 다르다.
>
>

- ls : 현 디렉토리 파일 목록

  > $ ls
  >
  > 1.txt

- touch  파일명. 확장자 : 파일 만들기

  >$ test. text

- pwd : 현재 작업디렉토리 출력 ---> print working directory

  > $pwd
  >
  > /c/Users/user/Desktop/실습1

- mkdir : make directory 폴더 만들기

  >$mkdir test

- cd  예시(test) : 폴더이동  예시 test 폴더 이동(change directory)

  >$ cd test
  >
  >/c/Users/user/Desktop/실습1/test

  .. : 상위 디렉토리(폴더) 이동

  > $ cd..
  >
  > /c/Users/user/Desktop/실습1/

  . : 현재 디렉토리(폴더)
  
- git init

  >git 폴더 초기화

- git status

  >$git status
  >
  >on branch master
  >
  >#트래킹되고 있지 않은 파일들
  >
  >Untracked files:
  >
  >#Staging area에 포함시키기 위해서는 git add를해.
  >
  >#Staging area  -> 커밋 대상 파일들 모아놓는 공간(커밋이 도리 예정인 것들)
  >
  >(use"git add <file> ..." to include in what will be committed) 2.txt
  >
  >#커밋하기 위해 추가된 것은 없는데, untracked files 존재한다.
  >
  >#Working directory -> 파일 있어
  >
  >#Staging area -> 파일 없어
  >
  >noting added to commit but untracked files present(use "git add" to track) 

  > on branch master
  >
  > #커밋 될 변경사항들
  >
  > Changes to be committed:
  >
  > (use "git restore -- staged<file>..." to unstage)
  >
  > new file:	new.txt

>$git status
>
>on branch master
>
>#Staging area(Staged O)
>
>Changes to be committed:
>
>(use "git restore --staged<file..." to unstage)
>
>new file :1
>
>





# 저장소 만들기

____

## 저장소 지정

touch _.txt

git clone 주소

git init

____



### 작업 도중

git add ___

git commit -m "___"

____



#### 상태 보기

git log

git status

____

##### 원격저장소 저장

git remote add origin <url> 

 => 깃아 원격저장소(remote) 추가해줘. (add) origin라는 이름으로 url을

git push origin master

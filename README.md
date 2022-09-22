## Week1-1 강의 내용 (강의계획서)
---
- 개설학과 : AI 융합대학 인공지능학부
- 대상학년 : 2 학년
- 지도교수 : 최광훈 교수님

<br>

## Week1-2 오픈소스소프트웨어 개요
---
> **what is open source software ?**  
소프트웨어 저작권 소유자가 모든 사람에게 소스 코드를 게시, 사용, 복사, 수정 및 배포할 권리를 부여한 소프트웨어

<br>

> **OSS License**  
오픈소스 소프트웨어의 사용, 복제, 수정, 배포 권한의 범위를 지정

<br>

## Week2-1 버전 관리 개요
---
### 개요
시간이 지남에 따라 이전의 버전을 쉽게 되돌릴 수 있도록 하기 위해서 도입된 개념이다.

<br>

*4개의 단계가 존재*
1. Workspace
1. Stage
1. Local Repository
1. Remote Repository

<br>

## Week2-2 Git
---
### Git Hub 란?
![img](./img/github.png)
> Git 이라는 도구를 응용한 사이트, 각종 Remote Repository 들의 집합소  
<br>
GitHub 바로가기 [GitHub](https://github.com/)

### 깃허브 명령어
- stage 단계로 추가하기 : `$ git add [file_name]`
- commit 하기 : `$ git commit -m "commit message"`
- 상태 확인 : `$ git status`
- 차이점 확인하기 : `$ git diff`
- 원격 저장소로 등록하기 : `$ git remote add origin <url>`
- 원격 저장소에 push 하기 : `$ git push origin master`
- 가장 최근 커밋 지우기 : `$ git reset HEAD~1`
- add 한 것 취소하기 : `$ git reset`

<br>

## Week2-3 Github, fork, pull request
---
- fork : 다른 사람의 원격 저장소를 나의 원격 저장소를 가져오는 과정
- pull request : 내가 수정을한 파일을 다른 사람의 원격 저장소로 수정해 달라고 요구하는 과정
<br>

## Week3 Mark down
---
Mark down은 형식된 문서를 생성하기 위한 가벼운 *markup language* 이다.
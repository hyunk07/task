# task

## 과제방에 repo 주소로 업로드

1. task repository 포크로 본인 repository에 복사
2. 내려 받기해서 해당 README.md 문서 수정
3. 오늘까지 배운 git 내용 마크다운 형식으로 __잘__ 정리
  _markdown-cheetseat 참고_
4. 본인 repository에 업로드
5. 로컬 저장소 내용도 캡쳐해서 함께 업로드

이 아래로 내용 작성

===================

# git 내용정리
## ***git:***
파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템

## ***github:***
온라인 상에서 협업을 통해 버전 관리를 할 수 있게 해주는 대표적인 깃 호스팅 업체

# 명령어

## ***Bash:***
	cd 폴더명: 그 폴더로 들어감
	cd ..: 현재 디렉토리에서 바로 상위 디렉토리로 이동
	cd -: touch 파일명 :파일 생성
	q: 다양한 옵션이 존재하며 입력 끝내기

## ***git 기본명령어:***
	- 내정보 등록
	*git config --global user.name "아이디 or 이메일"
	-로컬에 저장된 정보 확인하기
	*git config --list 
	-파일 추가하기
	*git add  README.md <기본 사용>
	*git add . 혹은 git add * <파일이 많은 경우>
	-메시지 작성과 함께 커밋
	*git commit -m "파일 설명"
	-기록 확인, 현재상태 확인하기
	*git log <기록>
	*﻿git status <상태>
	-add, commit 동시에
	*﻿git commit -am "파일 설명"
	- branch 만들기
	*git branch dev <- 브랜치 생성
	*git switch dev <- dev 브랜치로 이동
	*git switch -c dev <- 브랜치 바로 생성 후 이동

## ***git과 github 연동***
	사이트 로그인후
	###- git 명령어 입력###
	*git remote add origin "url"
	-github에서 파일 내려받기
	*​git clone "https://~"


# Git Practice

## 자기소개
컴퓨터ai 26학번 정윤우입니다.

## 관심 분야
- Web
- Reversing

## Git 명령어 정리
- git init: 지금의 디렉토리 기준으로 git이 이 디렉터리를 관리
- git status:  현재 작업중인 git저장소 상태 확인
- git add: 지금의 디렉토리를 기준으로 변경사항에 대해서 git이 추적 (add 뒤에 경로(i.e,마침표)명시)
- git commit: 커밋은 변경사항에 대한 작업을 확정
- git log: 커밋로그 확인
- git branch: 브랜치 확인
- git switch 또는 git checkout: branch변경
- git remote: 원격으로 연결
- git push: 로컬저장소에 작업한걸 원격저장소에 업로드

## CLI 실습 기록
- 사용한 명령어 순서:
git init
git remote add origin https://github.com/fptcmrhfptcmrh/git-practice
git add asdf.py
git commit -m "첫번째 커밋"
git add README.md
git commit -m "README생성 & 두번째 커밋"
git branch -M main
git push -u origin main
git branch feature/profile
git switch feature/profile
git add README.md
git commit -m "README수정"
git push -u origin feature/
git push origin feature/profile

- 생성한 브랜치명:feature/profile
- 커밋 메시지 3개: 첫번째커밋/README생성&두번째커밋/README수정
- 어려웠던 점: git을 다뤄본적이 한번도 없어서 3~4시간동안 해매면서 겨우한거라 다 어려웠습니다

## PR 실습 기록
- PR 제목: README수정
- PR 링크:
- PR에서 수정한 내용: README수정함
- Merge 여부: 함 관심 분야
- Web
- Reversing

## Git 명령어 정리
- git init: 지금의 디렉토리 기준으로 git이 이 디렉터리를 관리
- git status:  현재 작업중인 git저장소 상태 확인
- git add: 지금의 디렉토리를 기준으로 변경사항에 대해서 git이 추적 (add 뒤에 경로(i.e,마침표)명시)
- git commit: 커밋은 변경사항에 대한 작업을 확정
- git log: 커밋로그 확인
- git branch: 브랜치 확인
- git switch 또는 git checkout: branch변경
- git remote: 원격으로 연결
- git push: 로컬저장소에 작업한걸 원격저장소에 업로드

## CLI 실습 기록
- 사용한 명령어 순서:
git init
git remote add origin https://github.com/fptcmrhfptcmrh/git-practice
git add asdf.py
git commit -m "첫번째 커밋"
git add README.md
git commit -m "README생성 & 두번째 커밋"
git branch -M main
git push -u origin main
git branch feature/profile
git switch feature/profile
git add README.md
git commit -m "README수정"
git push -u origin feature/
git push origin feature/profile

- 생성한 브랜치명:feature/profile
- 커밋 메시지 3개: 첫번째커밋/README생성&두번째커밋/README수정
- 어려웠던 점: git을 다뤄본적이 한번도 없어서 3~4시간동안 해매면서 겨우한거라 다 어려웠습니다

## PR 실습 기록
- PR 제목: README수정
- PR 링크: https://github.com/fptcmrhfptcmrh/git-practice/pull/1
- PR에서 수정한 내용: README.md 파일을 수정함
- Merge 여부: 함

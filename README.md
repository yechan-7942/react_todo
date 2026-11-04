## Project Information: 프로젝트 소개, 선택 이유, 원본 GitHub URL 및 라이선스

### 프로젝트 소개: react기반 Todo 관리 서비스이다. 

### 선택 이유 : 주제가 익숙하고 이해하기 쉬워서 선택했다. 

### 원본 GitHub URL: https://github.com/KonyD/react-todo-app

## Installation: 설치·실행 방법 및 실행 화면
설치 : git clone으로 하고 npm install -> npm run dev로 실행 하였다. 


설치 화면 :![npm 설정 화면](<capture/npm 설정.png>)


실행 화면 :![npm 실행 화면](<capture/npm 실행.png>)


## Source Code Exploration: 주요 파일, 컴포넌트, 코드 분석


## Customizing: 수정한 3가지 내용, 수정 파일명 및 전/후 결과

1. 수정 파일 변경명 : src/TodoList.jsx : React Todo App에서 '오늘의 할일"이라고 한국어로 변경

    기존: ![제목 변경 이전 영어 화면](<capture/영어.png>)

    변경: ![제목 변경 이후 한국어 화면](<capture/한국어.png>)

2. 수정 파일 변경명 : src/index.css : 배경색을 보라색으로 변경했다.

    기존: ![배경색 변경 이전](<capture/배경색이전.png>)

    변경: ![배경색 변경 이후](<capture/배경색 이후.png>)

3. 수정 파일 변경명 : src/TodoList.jsx : 등록된 할 일 개수를 표시하는 UI를 추가했다.

    기존: ![할 일 개수 표시 이전](<capture/할일 개수 이전.png>)

    변경: ![할 일 개수 표시 이후](<capture/할일 개수 이후.png>)

## Deployment: 실제 접근 가능한 Vercel URL : https://react-todo-brown-one.vercel.app/


## Weekly Review:


## 새롭게 배운 내용 3가지
1. react에서 화면과 기능이 어떻게 연결되는지 이해하게되었다
2. 기존 프로젝트를 실행하고 코드를 보면서 전체적인 구조를 파악했다
3. 원본 코드를 많이 바꾸지 않아도 원하는 기능을 추가할 수 있다는 것을 알게 되었다.

## 어려웠던 점과 해결 방법
Vercel에 배포한 뒤 흰 화면만 나타나는 문제가 있었다. 기존경로가 설정되어 있어서 정적 파일을 불러오지 못했다. vite.config.js의 base를 '/'로 변경하고 다시 배포해 해결했다. -(Ai의 도움을 받음)

## AI 활용 내용 및 느낀 점
AI의 도움을 받아 코드를 수정하고 배포 오류를 해결했다.
전체적인 react가 전체적으로 어떻게 돌아가는지 이해한거 같다.
# 2021년 혁신성장 청년인재 집중양성 사업
# 클라우드 분야 프로젝트 멘토링
vue 기반 애플리케이션의 frontend 입니다.

## 서버실행
npm run dev

## 개발 환경
Node.js 10.16
(https://nodejs.org/en/download/releases/)

## NVM 설치 및 버전 변경
Node.js 10.16에 맞게 설치

1) VsCode 터미널에서 아래 명령어 실행
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash

2) bashrc 파일에 명령어 추가
2-1) 파일열기 vi ~/.bashrc 
2-2) 아래 명령어 추가
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

3) nvm 명령어 입력
4) 노드설치
nvm install 10.16
5) 노드버전 변경
nvm use 10.16
6) 버전 확인 
node -v
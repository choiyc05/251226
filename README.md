# 251226

 ## node.js
    web_study/frontend/node/
    node.js 다운

    - 초기화
    npm init -y

    - 한 번 실행
    npm run

    - nodemon 설치
    npm i nodemon (패키지 설치)
    > 폴더 내에 node_modules 폴더 생성 > 프로젝트 내에 포함 /

    - npm i
    "dependencies": {
    "nodemon": "^3.1.11"
    }
    확인하여 설치 
    => node_modules는 github 등에 올려서 이동할 필요 없음
    => npm run dev > 실행 파일 감시(watch)하며 자동으로 프로그램 재실행 / ctrl + c 2번하여 종료 가능
    실행 중이면 작업 관리자에 Node.js JavaScript Runtime 표시됨 / 종료 가능

    - 다른 파일에서 보내기/가져오기
    (가져갈 파일) module.exports = { * .... };
    (가져올 파일) require("./***.js");

    

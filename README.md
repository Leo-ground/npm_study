## npm

1. npm init: package.json 파일을 생성
2. npm start: packaage.json의 script부분을 실행, 단 직접만든 script의 경우 npm run 스크립트명 으로 실행
3. 버전정보
   - 1.0.0 은 각 부분이 Major.Minor.Patch임
   - Patch
     - 출시한버전의 버그, 사소한 오류 재배포시 한단계 업 1.0.1
   - Minor
     - 중간에 조금더 기능이 추가되거나 작은 기능이 추가된 경우 업 1.1.0
   - Major
     - 기존의 제품에서 정말다른 기능들이 제거/추가, 기능 변경사항이 발생했을 때 업 2.0.0
4. npm install명령어
   - npm i -h : help
   - npm i -g netlify : -g는 글로벌 옵션 , netlify 프론트 배포할때 사용하는 라이브러리
   - npm ll -g --dept=0 : ll은 list축약어, 설치리스트의 dept조절가능: 라이브러리의 라이브러리 보지 않을때
   - npm view underscore: 특정한 라이브러리(underscore) 버전보기
   - npm i underscore@1.13.1: @뒤에 특정버전을 입력가능, 입력하지 않을경우 최신 버전으로 설치됨
   - 설치가되면 node_modules에 해당 라이브러리가 설치됨
   - npm un underscore: 설치 라이브러리 삭제
   - npm oudated : 업데이트 필요 라이브러리 확인
   - npm update underscore: 업데이트 하기

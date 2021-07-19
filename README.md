# study_react
React 개발 관련 공부

## 개발환경 구축
### (설치) npm을 이용하는 방법
npm install -g create-react-app : npm에게 create-react-app을 install 시킨다.(이 컴퓨터의 어느 곳이든지 실행할 수 있도록)

### (설치) npx를 이용하는 방법
- create-react-app이라는 프로그램을 임시로 설치하여 한번만 실행시키고 지우는 방법.
- 컴퓨터의 공간을 낭비하지 않는다.
- 실행할 때마다 다운로드를 받기 때문에 항상 최신 상태이다.

### create-react-app 실행
해당 폴더에서 터미널 실행 후, create-react-app . (현재 디렉토리에 react 작업을 위한 환경을 만들어줌.)

### npm (run) start
브라우저에 띄어주는 역할, Ctrl C를 누르면 자동으로 꺼지게 된다.    

### npm run build
create-react-app이 실제 production 환경에서 사용되는 app을 만들기 위해서 기존에 갖고 있는 index.html 파일의 공백과 같이 불필요하게 용량을 차지하는 정보를 없앤 것이다.(용량이 훨씬 작다.)    
실제로 서비스를 할때는 build 안의 파일들을 쓰면 된다.

### npx serve -s build
한번만 실행시킬 웹서버를 다운로드 받아 실행할 때 build directory를 documet root로 하여 실행한다 (localhost:5000) -> 일반적으로 npm start할 때보다 훨씬 용량이 적게 나온다!    

---

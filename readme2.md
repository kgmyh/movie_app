1. create-react-app 으로 application 생성
   - npx create-react-app app이름
   - npx : 패키지를 다운받아 명령어를 실행한다.
   - create-react-app: react 앱을 생성할 수 있는 보일러 플레이트를 설치한다. (보일러 플레이트: 개발을 바로 시작할 수 있는 환경을 만들어 준다.)
2. create-react-app 후 내용 수정할 것
   1. package.json 수정
      - script의 "eject", "test" 삭제
        - script는 npm 으로 바로 실행시킬 수 있는 명령어를 등록한것.
3. 실행
   - `npm start`
   - 서버가 실행된다. 종료는 `control+c`
4. github에 올리기
   1. `git init`
      - repository 초기화
   1. github에 저장소 생성한다.
   1. git remote add origin https://github.com/kgmyh/movie_app.git
      - 원격지 저장소 주소 등록
   1. `git add .`
   1. git commit -m "first commit"
   1. git push origin main

```

```

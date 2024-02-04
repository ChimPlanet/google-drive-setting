# google-drive-setting
침플레닛의 스케줄러 log를 관리할 수 있도록 google drive를 셋팅하는 문서입니다.

## 사용 설명서
1. [블로그](https://velog.io/@poooq/Java-%EA%B5%AC%EA%B8%80%EB%93%9C%EB%9D%BC%EC%9D%B4%EB%B8%8CAPI%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%B4-%EC%9E%90%EB%B0%94%EB%9E%91-%EC%97%B0%EA%B2%B0%ED%95%98%EA%B3%A0-CRUD%EC%9E%91%EC%97%85%EA%B9%8C%EC%A7%80-1)의 [Google Cloud 설정(중요!)] 항목까지만 진행한다.
2. 다운로드한 OAuth json 파일의 이름을 "credentials.json"로 변경한다.
3. "credentials.json" 파일을 /src/resources 경로로 옮긴다.
4. Main 클래스를 실행한다.
5. 실행 후 웹 페이지가 열리게 되면 [계정 선택] > [계속] > [계속] 을 클릭하여 권한을 얻어온다.
6. 정상적으로 권한을 얻었다면 웹 페이지에 "Received verification code. You may now close this window." 이러한 문장이 출력된다.
7. 콘솔창에 출력된 "application.properties 파일의 log_dir_id에 들어갈 내용 : <생성된 폴더 ID>"을 복사하여 저장한다.
8. /token 폴더와 내부에 "StoredCredential"파일이 성공적으로 생성되었는지 확인한다.

### ※ [봇](https://github.com/ChimPlanet/ChimPlanet-mgt-bot), [서버](https://github.com/ChimPlanet/ChimPlanet-back) 프로젝트에 위 과정을 진행하며 생성된 파일 및 ID를 적용하여 사용한다.
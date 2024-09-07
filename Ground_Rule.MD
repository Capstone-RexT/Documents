# Ground Rule

### 의사 소통

- 급한 연락은 카카오톡으로, 이를 제외한 모든 연락, 의논 사항은 슬랙을 이용한다.
- 연락 확인 시 슬랙 및 카카오톡 체크 이모티콘, 대답 등의 확인 표시를 남긴다.
- 

### 회의

- 회의로 결정된 사항은 반드시 약속 기한까지 마무리한다.
- 회의 시작 전 이전 회의록 및 이전 미팅 내용, 이번 회의 안건을 숙지 후 참여한다.
- 회의 불참 및 지각 시 회의 하루 전까지 알린다.
- 

### 피드백/업데이트

- 수정 사항 발생 시 반드시 깃허브 pull request 작성, 슬랙 update 채널에 메시지 작성 후 main에 반영한다.
- 

### 코드 컨벤션

- **Naming Convention**
    
    
    | **타입** | **규칙** | **기타 주의사항** |
    | --- | --- | --- |
    | 변수명 | `snake_case` |  |
    | 상수명 | `UPPER_CASE` |  |
    | 함수명 | `carmelCase` |  |
    | 파일명 | `snake_case` | 띄어쓰기, 기타 특수문자 사용 X |
    | 폴더명 | `snake_case` | 띄어쓰기, 기타 특수문자 사용 X |
- **Github Commit Convention**
    
    
    | **타입** | **설명** |
    | --- | --- |
    | Fix | 주석, 오타 수정 |
    | Docs | 문서 수정 |
    | Add | 새로운 변수, 함수 추가 / 새로운 코드 추가 |
    | Modify | 기존 변수명, 함수명 수정 / 파일명 수정 / 폴더 구조 변경 / 기존 코드 수정 / 코드 스타일 변경 |
    | Remove | 함수 삭제 / 불필요 코드 삭제 / 파일 삭제 |
- Pull request title은 commit message 헤더와 동일하게 작성한다.
- commit message 예시: `Modify: 함수1 class, instance 번호 추출 방식 수정`
- 오타 수정과 같은 자잘한 수정이 아닌 모든 수정사항은 review 요청 후 모든 팀원이 확인 후 PR 작성자가 merge한다.
- 반드시 `git pull origin main`으로 최신 변경 사항을 반영한 후에 push한다.

[참고]

https://gist.github.com/stephenparish/9941e89d80e2bc58a153

[https://velog.io/@shin6403/Git-git-커밋-컨벤션-설정하기](https://velog.io/@shin6403/Git-git-%EC%BB%A4%EB%B0%8B-%EC%BB%A8%EB%B2%A4%EC%85%98-%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0)
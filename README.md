# 지하철 즐겨찾기

## 1단계 - 회원관리 기능

### 요구 사항
- 회원 정보를 관리하는 기능 구현
- 자신의 정보만 수정 가능하도록 해야하며 **로그인이 선행**되어야 함
- 토큰의 유효성 검사와 본인 여부를 판단하는 로직 추가
- side case에 대한 예외처리
    - 회원 가입
        - 이메일 형식이 맞지 않는 경우
        - 이미 존재하는 이메일인 경우
        - 패스워드와 패스워드 확인이 다를 경우
    - 로그인
        - 이메일 형식이 맞지 않은 경우
    - 로그인 후 회원정보 조회/수정/삭제
        - 이메일 형식이 맞지 않는 경우
        - 이미 존재하는 이메일인 경우
        - 패스워드와 패스워드 확인이 다를 경우
- 인수 테스트와 단위 테스트 작성
- API 문서를 작성하고 문서화를 위한 테스트 작성
- 페이지 연동

### 기능 목록
1. 회원가입
2. 로그인
3. 로그인 후 회원정보 조회/수정/삭제
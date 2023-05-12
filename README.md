# kakao 로그인 API 실습
## 실습 목적
- 카카오 로그인 API가 v2로 업그레이드 되어 실습
- v1에서 사용하던 함수가 변경되어 실습
  - Kakao.Auth.login( ) → Kakao.Auth.authorize( )

## 상태
- 카카오로그인을 오류없이 진행하면 로그인 후 주소창에 인가코드를 받아오고 code 라는 상수로 저장

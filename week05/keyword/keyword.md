- XSS 공격 / CSRF 공격 🍠
  - XSS 공격
    XSS (Cross-Site Scripting)는 공격자가 댓글란 같은 입력창에 script를 심어 넣는 것을 말한다. 이를 프론트나 서버에서 보안 설정해주지 않으면 다른 사용자가 공격자가 심어놓은 댓글을 로딩할 때 script로 인식되어 공격자가 원하는 동작이 실행되게 된다. react는 자동으로 escape처리를 해준다.
  - CSRF 공격
    브라우저가 쿠키를 자동으로 실어서 요청을 보내는 것을 악용한 공격이다. 이를 방지하기 위해서 같은 사이트의 요청에만 쿠키를 담는 SameSite 및 Secure설정을 쿠키에 해주어야한다.

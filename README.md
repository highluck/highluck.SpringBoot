# highluck.AccountBoot
Spring boot & Jpa 를 이용한 rest api 계정인증서버

1. 기능 명세

- email (회원가입인증, 패스워드 변경) 

thymeleaf 를 이용한 이메일 템플릿 전송 


- Token

로그인시 토큰 생성후 클라이언트 전송

로그아웃 시 토큰 삭제 

패스워드 변경 이메일에 토큰 전송 

토큰을 이용한 접근권한


2.사용 Flow 

클라이언트 -> 계정인증서버 -> 클라이언트(인증) -> 어플리케이션서버 
            


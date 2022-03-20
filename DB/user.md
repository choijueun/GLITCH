### 회원ID
탈퇴해도 이미 사용된 아이디는 사용할 수 없게
1. No
    - PK & AUTO_INCREASED
    - 일련번호
1. id		
    - UNIQUE
    - 회원 ID

<br/>

### 회원
1. id		
    - PK & FK
    - 회원 ID
1. nickname	
    - UNIQUE
    - 회원 닉네임
1. password	
    - VARCHAR(25)
    - 회원 비밀번호
1. url (NULL)
    - VARCHAR(100)
    - 회원 블로그/홈페이지 주소
1. reg_date		
    - DATETIME
    - 가입일시
1. pw_modify_date	
    - DATETIME
    - 비밀번호 수정일시

<br/>

### 로그인 내역
1. id
    - PK & AUTO_INCREASED
    - 일련번호
1. login
    - DATETIME
    - 로그인 일시

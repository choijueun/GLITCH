### chr_profile
GLITCH MEMBER PROFILE PAGE
1. No
    - PK & AUTO_INCREMENT
    - 일련번호
1. id
    - FK
    - 작성자 아이디
1. chr_name
    - UNIQUE
    - 캐릭터 이름
1. chr_gender
    - VARCHAR(10)
    - 성별
1. chr_rank
    - INT
    - CR(RANK)
1. chr_aclass
    - 아키 직업
1. chr_mclass
    - 메인 직업
1. chr_str
    - INT
    - 능력치 STR
1. chr_dex
    - INT
    - 능력치 DEX
1. chr_pow
    - INT
    - 능력치 POW
1. chr_int
    - INT
    - 능력치 INT
1. reg_date
    - DATETIME
    - 작성일시
2. update_date
    - DATETIME
    - 수정일시

### chr_skill

### chr_subclass
1. No
    - 일련번호
    - PK & AUTO_INCREMENT
2. chr_no
    - FK (chr_profile)
    - 캐릭터 프로필 번호
3. chr_subclass
    - VARCHAR
    - 서브클래스
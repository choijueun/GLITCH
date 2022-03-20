### Union

1. union
    - PK & VARCHAR
    - 유니온명
1. reg_date
    - DATETIME
1. update_date
    - DATETIME

<br/>

### Union_member
1. No
    - PK & INT & AUTO_INCREMENT
1. union
    - FK
1. chr_no
    - FK
1. chr_name
    - 캐릭터명
1. chr_grade
    - DOMAIN: 마스터, 부마스터, 길드원

<br/>

### Union_items
1. union
    - FK & PK
1. item_name
    - 아이템명
1. item_cnt
    - INT
    - 아이템 갯수
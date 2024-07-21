notion 링크:https://wind-dewberry-ca7.notion.site/sql-953307df0b38424097a534068e447b3b?pvs=4

---

![image](https://github.com/user-attachments/assets/00dc4d85-d36d-4b1c-85d7-0a6ecc173f1e)


정형:정형은 데이터베이스 sql문으로 수정,삭제등 표현이 가능하다.

비정형:**XML, JSON, 텍스트 문서, 이미지, 비디오 및 오디오 파일**

DB는 데이터베이스 즉 데이터의 집합일 뿐이며 DBMS는 데이터를 관리하는 응용 소프트웨어일 뿐이므로 별도의 의미를 내포한다.

### 관계형 데이터베이스

---

- 관계형 데이터베이스는 열(colum)과 행(row)를 갖는 2차원 배열 형식의 데이터베이스
- 수많은 데이터를 가공하는 키와 관계라는 연결 고리로 연결하여 원하는 데이터를 조회하고 가공하는 데이터베이스
- 
![image](https://github.com/user-attachments/assets/0895d67c-e461-46e1-88dc-b295969cfbc7)


## 계층형 데이터베이스

---

- 가장 오래된 형태의 데이터베이스 윈도우에서의 디렉토리 방식
- 직관적이기에 개인용 저장 장치에 쓰이나 기업에서 자주 사용하는 형태는 아니다.
![image](https://github.com/user-attachments/assets/56731464-78c4-4acd-a40f-96dcfc2f17ae)

### 객체 지향 인터페이스

---

- 객체와 객체 식별자, 속성,메소드 클래스,클래스 계층 및 상속 복합 객채 지향 데이터모델을 지원하는 데이터베이스(db에서의 자바와 같은?)
- 자바,c++ 과 같은 객체 지향언어의 객체 지향 프로그래밍에 적합한 데이터베이스.

![image](https://github.com/user-attachments/assets/03d7ef7f-0c77-46b0-bcff-7a611d1ac9a1)


### SQL이란?

---

- 데이터 조작어(DML, Data Mainpulation Language)
- 데이터 정의어(DDL, Data Defintion Language)
- 데이터 제어어(DCL,Data Control Language),
- 트랜잭션(Transaction Control Language)

![Uploading image.png…]()


.

| 구분 | 명령어 | 설명 |
| --- | --- | --- |
| 데이터 조작어(DML, Data Mainpulation Language) | select
insert
UPDATE
DELETE | 검색SELECT)
행 삽입(INSERT)
행 수정(UPDATE)
행삭제(DELETE) |
| 데이터 정의어(DDL, Data Defintion Language)  | CTEATE
ALTER
DROP
RENAME
TRUNCATE | 테이블의 정의 구조,생성,수정,제거 |
| 데이터 제어어(DCL,Data Control Language), | GRANT
REVOKE | 데이터베이스내 접근 권한을 부여,제거 |
| 트랜잭션(Transaction Control Language) | COMMIT
ROLLBACK
SAVEPOINT | dmL로 설정한 변경 사항을 저장 or 관리. |

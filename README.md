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

![s_2.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7540eda1-50b0-4704-924e-78f9872ec9b8/289acc6f-ee3e-4771-a163-875cb1ff8067/s_2.png)

## 계층형 데이터베이스

---

- 가장 오래된 형태의 데이터베이스 윈도우에서의 디렉토리 방식
- 직관적이기에 개인용 저장 장치에 쓰이나 기업에서 자주 사용하는 형태는 아니다.

![s_3.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7540eda1-50b0-4704-924e-78f9872ec9b8/36c6ea76-e69b-4d8a-9add-1b915cbdfdc2/s_3.png)

### 객체 지향 인터페이스

---

- 객체와 객체 식별자, 속성,메소드 클래스,클래스 계층 및 상속 복합 객채 지향 데이터모델을 지원하는 데이터베이스(db에서의 자바와 같은?)
- 자바,c++ 과 같은 객체 지향언어의 객체 지향 프로그래밍에 적합한 데이터베이스.

![s_4.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7540eda1-50b0-4704-924e-78f9872ec9b8/e158b2a5-6d88-4376-aa48-e4b38ed3d6a8/s_4.png)

### SQL이란?

---

- 데이터 조작어(DML, Data Mainpulation Language)
- 데이터 정의어(DDL, Data Defintion Language)
- 데이터 제어어(DCL,Data Control Language),
- 트랜잭션(Transaction Control Language)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/7540eda1-50b0-4704-924e-78f9872ec9b8/77ece8db-5dd5-4d85-a356-7566ef98a1c9/Untitled.png)

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

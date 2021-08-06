# DDL & DML 

1. 테이블 생성 : 테이블 명 - `my emp`

   - 테이블 구성 필드 : `empno : char(5)`, `ename : varchar2(10)`, `hiredate : date`

     ​                               `sal : number(10)`, `memo : varchar2(10)`

     ```sql
     create table myemp (id varchar2(20) primary key,
     empno char(5),
     ename varchar2(10),
     hiredate date,
     sal number(10),
     memo varchar2(10));
     ```

     

2. 데이터입력하기  : `0001`, `scott`, `오늘날짜`, `3000`, `신입`

   ```sql
   insert into myemp values(1, '0001','scott',sysdate,'3000','신입');
   ```

   

3. 삽입된 데이터 저장하기

   ```sql
    commit;
   ```

   

4. 전체 데이터 조회하기

   ```
   ID  EMPNO  ENAME  HIREDATE   SAL     MEMO
   1   0001   scott   21/08/06  3000    신입
   
   ```

   

​    
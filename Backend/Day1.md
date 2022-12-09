#### mySQL 에러 - [42000][1248] Every derived table must have its own alias
+ 서브쿼리에 `Alias` 를 달지 않아 생기는 에러이다.
+ [에러] `select * from (select * from table);`
+ [수정] `select * from (select * from table) t ;`



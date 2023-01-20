#### org.mybatis.spring.MyBatisSystemException: nested exception is org.apache.ibatis.exceptions.TooManyResultsException: Expected one result (or null) to be returned by selectOne(), but found: 2 에러🛑
+ Mybatis로 조회 시 위와 같은 에러 메시지가 콘솔에 찍혔다.
+ 에러 메시지를 번역해 보면 `리턴된 결과는 1개 혹은 0 이어야 하는데 두개 이상이 리턴`되고 있다는 말이다.
+ 실제로 그런지 디비 콘솔에 찍어보니 상세 페이지 관련 쿼리여서 한개의 데이터만 나와야 하는데 2개의 데이터가 나오고 있었다.
+ 알고보니 디비에 잘못된 데이터 값이 들어가서 데이터 2개가 나온 것이였다.]
+ 데이터를 수정하여 위와 같은 문제를 해결하였다😎

#### Caused by: org.apache.ibatis.reflection.ReflectionException: There is no getter for property named 'request' in 'class.java.lang.{타입}' 에러🛑
+ 직역하면 `클래스 타입인 "타입"으로 만들어진 "변수" 프로퍼티는 getter가 존재하지 않는다.` 이다.
+ 에러 이유
  +  mybatis에 써놓은 쿼리중에 `#{변수}` 이 부분이 잘못되어 에러가 나는 것이다. 
+ `mapper.java`에서 쿼리문과 매핑하여 넘겨주는 `request` 값이 있는데 `xml` 파일에 쿼리에서 그 형태를 잘못 넣어줘서 그랬던 것이다.
+ 해결
  + 예시) #{request.mango} -> #{mango}

#### 데이터 무결성🔥
+ 문의✅
  + 프론트 쪽에서 운영서버에서 리뷰api 테스트를 진행하려고 하는데 리뷰 등록 시 주문번호가 필요해 임의로 리뷰데이터 등록 가능한지 문의가 들어왔다.
  + 결론은 NO‼️ 이다.
  + 리뷰는 주문을 완료 한 경우에만 작성이 가능하다.
  + 따라서 주문 내역이 없으면 리뷰 등록이 불가하다.❌
+ 데이터 무결성은 데이터의 정확성, 일관성, 유효성이 유지되는 것을 의미한다.
+ 여기서 정확성이란 중복이나 누락이 없는 상태를 뜻하고, 일관성은 원인과 결과의 의미가 연속적으로 보장되어 변하지 않는 상태를 뜻한다. 
+ 만약 데이터베이스에서 데이터 무결성 설계를 하지 않는다면 테이블에 중복된 데이터 존재, 부모와 자식 데이터 간의 논리적 관계 깨짐, 잦은 에러와 재개발 비용 발생 등과 같은 문제가 발생할 것이다.
+ 그렇기 때문에 DBMS에서 데이터의 무결성이 유지되는 것은 중요한 사항이며, 주로 데이터에 적용되는 연산에 제한을 두어 데이터의 무결성을 유지한다.
+ 따라서 데이터 무결성 문제로 인해 임의로 데이터를 추가해 줄 수 없다.❌

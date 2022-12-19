#### 크롬과 엣지에서는 되는데 IE(Internet Explore)에서 적용 안 되는 것들
+ 람다식 문법
  + IE는 최신 문법인 람다식 문법이 적용되지 않는다.
  + 따라서 람다식 대신 익명함수를 사용하면 된다.
  + `() => {}` 말고 `function() {}` 
+ 백쿼트(`)
  + IE에는 백쿼트 문법이 지원되지 않는다.
  + 따라서 백쿼트 대신 ""안에 '' 이렇게 해줘야 한다.
  + 예) `"'menu' + menuList.pdf "`
+ include() 함수
  + IE는 include() 함수가 지원이 안 된다.
  + 따라서 이 대신 indexOf() 함수를 사용하면 된다.
  + indexOf() 함수는 0,1,-1 등 해당 문자열이 포함된 위치의 인덱스 값을 리턴한다.
+ css
  + display: grid
  + box-shadow
  + grid-template-columns
  + div border가 이상하게 먹히는 현상
  + 이외에도 최신 css들..

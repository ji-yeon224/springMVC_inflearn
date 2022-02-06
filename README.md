# springMVC_inflearn

##요청 매핑
###@RestController
- @Controller는 반환 값이 'String'이면 뷰 이름으로 인식된다. 그래서 **뷰를 찾고 뷰가 랜더링** 된다.
- @RestController는 반환 값으로 뷰를 찾는 것이 아니라, **HTTP 메세지 바디에 바로 입력**한다. 따라서 실행 결과로 ok 메세지를 받을 수 있다.

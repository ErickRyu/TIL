# WAS, Web server, JSP, Sevlet

### WAS

* WAS는 web server + web container를 합한 것
* 톰캣은 JSP환경을 포함하고 있는 sevlet container

#### WAS와 웹서버의 차이

* 아파치는 웹 서버, 톰캣은 WAS
* 웹 서버는 정적인 데이터를 처리, WAS는 동적인 데이터를 처리. 두 개의 서버를 연동해서 사용하면 더욱 효과적인 서비스를 제공할 수 있다.

[참고] : [WAS와 웹서버의 차이 - 톰캣과 아파치를 구별하지 못하는 사람을 위해](http://sungbine.github.io/tech/post/2015/02/15/tomcat%EA%B3%BC%20apache%EC%9D%98%20%EC%97%B0%EB%8F%99.html)

[참고] : [웹 구현을 위해 알아야 할 개념](http://wan00ny.tistory.com/m/11)

[참고] : [apache와 apache tomcat의 차이점](http://ithub.tistory.com/101#recentComments)

### Servlet container

* 서블릿을 실행하고 생명주기를 관리하는 역할
* 멀티 스레딩을 지원하여 클라이언트의 다중 요청을 알아서 처리해준다.
* 대표적 컨테이너에는 Tomcat, jetty, jboss등이 있다.


### JSP

* JSP는 서블릿을 더 쉽게 프로그래밍하기 위해 나온 것
* 개발자가 JSP를 짜면 WAS가 서블릿을 만들어줌

#### JSP와 Servlet을 같이 사용하는 이유

* JSP는 HTML과 자바코드가 혼재. 로직과 디자인이 한 파일내에 섞여 유지보수가 어렵다.
* Model2를 사용
  * View는 JSP로, Controller는 Servlet으로.
  * OOP적 노하우가 축적되면서 Spring이 나오게 됨.

[참고] : [JSP와 Servlet, 왜 같이 쓸까?](http://anster.tistory.com/128)



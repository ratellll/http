Uniform: 리소스 식별하는 통일된 방식
Resource: 자원, URI로 식별할 수 있는 모든(제한없음)
Identifier:다른 항목과 구분하는데 필요한 정보

URL: Uniform Resource Locator


URL-Locator : 리소스가 있는 위치를 지정

URN-Name : 리소스에 이름을 부여

위치는 변할 수 있지만 , 이름은 변하지않는다.
URN이름만으로는 실제 리소를 찾을수 있는 방법이 보편화되지않음


scheme://[userinfo@]host[:port][/path][?query][#fragment]
 https://www.google.com:443/search?q=hello&hl=ko


POST 란

1.새 리소스 생성(등록)
서버가 아직 식별하지 않은 새 리소스 생성

2.요청 데이터 처리
단순히 데이터를 생성하거나 변경하는 것을 넘어서 프로세스를 처리해야 하는 경우
예) 주문에서 결제완료 -> 배달 -> 도착 처럼 단순히 값변경으로 넘어 프로세스 상태가 변경되는경우
POST의 결과로 새로운 리소스가 나오지않을떄

3.다른 메소드로 처리하기 애매할때
예)JSON으로 넘겨야하는데 GET을 쓰기 어려울경우
애매하면 POST






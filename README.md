# shopping_SPA

**SPA 구현 문제**
SPA를 구성하는 부분에서 중요한 것이 URL 라우팅 처리이다

## Location

Location 인터페이스는 객체가 연결된 장소(URL)를 표현합니다
Location 인터페이스에 변경을 가하면 연결된 객체에도 반영되는데, Document와 Window 인터페이스가 이런 Location을 가지고 있다

각각 `Document.location` 과 `Window.location`으로 접근할 수 있다

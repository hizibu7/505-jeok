## 📝 오늘 공부한 내용
> Linux vi와 Spring 스터디 학습과 작성한 코드를 확인 (groovy -> java)

## 😲 오늘 깨달은 내용
서비스 계층의 역할. 컨트롤러와 리포지토리를 이어준다.
의존성 주입에 인터페이스를 사용하는게 좋을까? (그렇다)
- 유연성 : 인터페이스를 구현한 여러 클래스 주입 가능 → 코드 변경없이 구현체 교체 or 새로운 구현체 추가 가능
- 확장성 : 기존 코드 변경 없이 새로운 구현체 추가 가능
- 의존성 역전 원칙 : 고수준 모듈이 저수준 모듈에 의존하지 않고 추상화에 의존토록 해줌. → 코드 유연성 + 재사용성
- 단위 테스트 용이성 : mock object를 통해 테스트 용이

## 🥲 오늘 이해못했거나 궁금한 내용
1. 의존성 주입에 대해 다시 한 번 알아보기
   
## 📁 참고한 자료 및 사진 첨부
- 'RESTful API 서버 구현' 도서
다음의 블로그들을 통해 의존성 주입에 대해 학습중
 - https://tecoble.techcourse.co.kr/post/2021-04-27-dependency-injection/
 - https://velog.io/@sana/DI-%EC%9D%98%EC%A1%B4%EC%84%B1-%EC%A3%BC%EC%9E%85Dependency-Injection-%EC%9D%98-%EA%B0%9C%EB%85%90%EA%B3%BC-%EB%B0%A9%EB%B2%95
 - https://mangkyu.tistory.com/150

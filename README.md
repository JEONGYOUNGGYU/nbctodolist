# 회원가입, 로그인 기능이 있는 투두앱 백엔드 서버 만들기

## 과제에 대한 고려사항
1. 처음 설계한 API 명세서에 변경사항이 있었나요?
   변경 되었다면 어떤 점 때문일까요? 첫 설계의 중요성에 대해 작성해 주세요!
- 구현했던 부분까지는 변경사항이 없었습니다! 
3. ERD를 먼저 설계한 후 Entity를 개발했을 때 어떤 점이 도움이 되셨나요?
- 작업 할 때 편리하지만, fk 설정이 아직 헷갈립니다.
4. JWT를 사용하여 인증/인가를 구현 했을 때의 장점은 무엇일까요?
- 구현을 못했습니다...
5. 반대로 JWT를 사용한 인증/인가의 한계점은 무엇일까요?
- 구현을 못했습니다...
6. 만약 댓글이 여러개 달려있는 할일을 삭제하려고 한다면 무슨 문제가 발생할까요? Databases 테이블 관점에서 해결방법이 무엇일까요?
- 댓글까지 다 삭제가 되며, 댓글ID와 할일ID 두개를 FK로 설정하는 방법..?
7. IoC / DI 에 대해 간략하게 설명해 주세요!
- IoC : 제어의 역전, 메소드나 객체의 호출작업을 개발자가 결정하는 것이 아니라, 외부에서 결정되는 것을 의미
- DI : 스프링이 다른 프레임워크와 차별화되어 제공하는 의존 관계 주입 기능, 객체를 직접 생성하는게 아니라 외부에서 생성한 후 주입 시켜주는 방식
- 아직 와닿지 않아요..

커밋..하다가 파일이 다 사라졌습니다..
## Use case diagram
..

## API 명세서
![image](https://github.com/JEONGYOUNGGYU/nbctodolist/assets/110453217/37da8377-8af0-4102-9ad6-7ccb33ed3b57)

![image](https://github.com/JEONGYOUNGGYU/nbctodolist/assets/110453217/853d28ec-5f63-411f-b315-9b4b10f48149)

![image](https://github.com/JEONGYOUNGGYU/nbctodolist/assets/110453217/2ee1fc17-454d-4d4c-832c-77d8cd72b583)

![image](https://github.com/JEONGYOUNGGYU/nbctodolist/assets/110453217/aa294a3d-33a2-4a35-844c-a6183c3aad50)


## ERD
![image](https://github.com/JEONGYOUNGGYU/nbctodolist/assets/110453217/4d71337b-a2a0-468c-8fdd-311e6595cc6c)

# SPRING ADVANCED

백엔드 기본 요소를 기반으로 꼼꼼한 테스트까지 고려하는 백엔드 개발자를 향하여!
---

### Lv1. 코드 개선

1. 코드 개선 퀴즈 - Early Return -> Refactor : Lv1_1 Early Return
2. 리팩토링 퀴즈 - 불필요한 if - else 피하기 -> Refactor : remove unnecessary else if
3. 코드 개선 퀴즈 - Validation -> Refactor : Lv1-3 validation

---

### Lv2. N+1 문제

JPQL fetch join을 사용하여 N+1 문제를 해결하고 있는 TodoRepository가 있습니다. 이를 동일한 동작을 하는 @EntityGraph 기반의 구현으로 수정해주세요.
<br>-> Refactor : Lv2 N+1 problem
---

### Lv3. 테스트코드 연습

#### 1. 테스트 코드 연습1

테스트 패키지 package org.example.expert.config; 의 PassEncoderTest 클래스에 있는 matches_메서드가_정상적으로_동작한다() 테스트가 의도대로 성공할 수 있게 수정해
주세요.
<br>-> Refactor : Lv3 테스트 코드 연습 -1
<br>
<br>

#### 2. 테스트 코드 연습2_1

테스트 패키지 package org.example.expert.domain.manager.service; 의 ManagerServiceTest 의 클래스에 있는
manager_목록_조회_시_Todo가_없다면_NPE_에러를_던진다() 테스트가 성공하고 컨텍스트와 일치하도록 테스트 코드와 테스트 코드 메서드 명을 수정해 주세요.
<br>-> Refactor : Lv3 테스트 코드 연습 -2_1
<br>
<br>

#### 3. 테스트 코드 연습2_2

테스트 패키지 org.example.expert.domain.comment.service; 의 CommentServiceTest 의 클래스에 있는 comment_등록_중_할일을_찾지_못해_에러가_발생한다() 테스트가
성공할 수 있도록 테스트 코드를 수정해 주세요.
<br>-> Refactor : Lv3 테스트 코드 연습 -2_2
<br>
<br>

#### 3. 테스트 코드 연습2_3

테스트 패키지 org.example.expert.domain.manager.service의 ManagerServiceTest 클래스에 있는 todo의_user가_null인_경우_예외가_발생한다() 테스트가 성공할 수
있도록 서비스 로직을 수정해 주세요.
<br>-> Refactor : Lv3 테스트 코드 연습 -2_3
<br>


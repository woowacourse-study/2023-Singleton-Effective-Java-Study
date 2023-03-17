# 싱글톤’s 이펙티브 자바 스터디

## 멤버

- [그레이](신비한%20크루%20사전/그레이)
- [푸우](신비한%20크루%20사전/푸우)
- [호이](신비한%20크루%20사전/호이)
- [키아라](신비한%20크루%20사전/키아라)
- [블랙캣](신비한%20크루%20사전/블랙캣)
- [콩하나](신비한%20크루%20사전/콩하나)
- [져니](신비한%20크루%20사전/져니)
- [에코](신비한%20크루%20사전/에코)

## 교재

- 이펙티브 자바

## 운영방식

- 주 2회
    - **월: 11시**
    - **금: 5시**
- Item 한 개당 발표자 한 명이 발표하는 것으로

## 발표 규칙

- 발표자료: 마크다운
- 발표형식: 자유
- 순서대로 가되, 본인 하고 싶은 파트가 있으면 미리 선점해서 할 수 있다.
- 발표 주제는 이전 스터디 회의 내에서 선택하는 것 한다.
- 총 8명, 2인 4팀으로 만들어서 하루에 4개
- 금요일 발표면 발표 전 **수요일까지**, 월요일 발표면 발표 전 **토요일까지** 페어에게 발표 내용에 대해 피드백을 받아야한다.
- final 벌금 =  **5000원**

# 목차

## 2장. 객체 생성과 파괴

- [x]  [item 1. 생성자 대신 정적 팩터리 메서드(static factory method)를 고려하라](내용%20정리/2장/item_01) ➢ 에코
- [x]  [item 2. 생성자에 매개변수가 많다면 빌더를 고려하라](내용%20정리/2장/item_02) ➢ 블랙캣
- [x]  [item 3. private 생성자나 열거 타입으로 싱글턴임을 보증하라](내용%20정리/2장/item_03) ➢ 키아라
- [x]  [item 4. 인스턴스화를 막으려거든 private 생성자를 사용하라](내용%20정리/2장/item_04) ➢ 키아라
- [x]  [item 5. 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라](내용%20정리/2장/item_05) ➢ 콩하나
- [x]  [item 6. 불필요한 객체 생성을 피하라](내용%20정리/2장/item_06)  ➢ 푸우
- [x]  [item 7. 다 쓴 객체 참조를 해제하라](내용%20정리/2장/item_07) ➢ 키아라
- [ ]  item 8. finalizer와 cleaner 사용을 피하라
- [x]  [item 9. try-finally 보다는 try-with-resources를 사용하라](내용%20정리/2장/item_09) ➢ 져니

## 3장. 모든 객체의 공통 메서드

- [ ]  item 10. equals는 일반 규약을 지켜 재정의하라
- [ ]  item 11. equals를 재정의하려거든 hashCode도 재정의하라
- [x]  [item 12. toString을 항상 재정의하라](내용%20정리/3장/item_12) ➢ 그레이
- [ ]  item 13. clone 재정의는 주의해서 진행하라
- [x]  [item 14. Comparable을 구현할지 고려하라](내용%20정리/3장/item_14) ➢ 호이

## 4장. 클래스와 인터페이스

- [x]  [item 15. 클래스와 멤버의 접근 권한을 최소화하라](내용%20정리/4장/item_15) ➢ 콩하나
- [ ]  item 16. public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라
- [x]  [item 17. 변경 가능성을 최소화하라](내용%20정리/4장/item_17) ➢ 에코
- [x]  [item 18. 상속보다는 컴포지션을 사용하라](내용%20정리/4장/item_18) ➢ 블랙캣
- [ ]  item 19. 상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라
- [x]  [item 20. 추상 클래스보다는 인터페이스를 우선하라](내용%20정리/4장/item_20) ➢ 에코
- [ ]  item 21. 인터페이스는 구현하는 쪽을 생각해 설계하라
- [ ]  item 22. 인터페이스는 타입을 정의하는 용도로만 사용하라
- [ ]  item 23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라
- [ ]  item 24. 멤버 클래스는 되도록 static으로 만들라
- [ ]  item 25. Top Level 클래스는 한 파일에 하나만 담으라

## 5장. 제너릭

- [ ]  item 26. Raw Type은 사용하지 말라
- [ ]  item 27. 비검사 경고를 제거하라
- [ ]  item 28. 배열보다는 리스트를 사용하라
- [x]  [item 29. 이왕이면 제네릭 타입으로 만들라](내용%20정리/5장/item_29) ➢ 져니
- [x]  [item 30. 이왕이면 제네릭 메서드로 만들라]내용%20정리/5장/item_30) ➢ 블랙캣
- [ ]  item 31. 한정적 와일드카드를 사용해 API 유연성을 높이라
- [ ]  item 32. 제네릭과 가변인수를 함께 쓸 때는 신중하라
- [ ]  item 33. 타입 안전 이종 컨테이너를 고려하라

## 6장. 열거 타입과 애너테이션

- [ ]  item 34. int 상수 대신 열거 타입을 사용하라
- [ ]  item 35. ordinal 메서드 대신 인스턴스 필드를 사용하라
- [ ]  item 36. 비트 필드 대신 EnumSet을 사용하라
- [ ]  item 37. ordinal 인덱싱 대신 EnumMap을 사용하라
- [ ]  item 38. 확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라
- [ ]  item 39. 명명 패턴보다 애너테이션을 사용하라
- [ ]  item 40. @Override 애너테이션을 일관되게 사용하라
- [ ]  item 41. 정의하려는 것이 타입이라면 마커 인터페이스를 사용하라

## 7장. 람다와 스트림

- [x]  [item 42. 익명 클래스보다는 람다를 사용하라](내용%20정리/7장/item_42) ➢ 호이
- [x]  [item 43. 람다보다는 메서드 참조를 사용하라](내용%20정리/7장/item_43) ➢ 그레이
- [ ]  item 44. 표준 함수형 인터페이스를 사용하라
- [x]  [item 45. 스트림은 주의해서 사용하라](내용%20정리/7장/item_45) ➢ 그레이
- [ ]  item 46. 스트림에서는 부작용 없는 함수를 사용하라
- [ ]  item 47. 반환 타입으로는 스트림보다 컬렉션이 낫다
- [ ]  item 48. 스트림 병렬화는 주의해서 적용하라

## 8장. 메서드

- [ ]  item 49. 매개변수가 유효한지 검사하라
- [x]  [item 50. 적시에 방어적 복사본을 만들라](내용%20정리/8장/item_50) ➢ 푸우
- [ ]  item 51. 메서드 시그니처를 신중히 설계하라
- [ ]  item 52. 다중정의는 신중히 사용하라
- [ ]  item 53. 가변인수는 신중히 사용하라
- [ ]  item 54. null이 아닌, 빈 컬렉션이나 배열을 반환하라
- [x]  [item 55. 옵셔널 반환은 신중이 하라](내용%20정리/8장/item_55) ➢ 호이
- [ ]  item 56. 공개된 API 요소에는 항상 문서화 주석을 작성하라

## 9장. 일반적인 프로그래밍 원칙

- [x]  [item 57. 지역변수의 범위를 최소화하라](내용%20정리/9장/item_57) ➢ 푸우
- [x]  [item 58. 전통적인 for문보다는 for-each문을 사용하라](내용%20정리/9장/item_58) ➢ 푸우
- [ ]  item 59. 라이브러리를 익히고 사용하라
- [ ]  item 60. 정확한 답이 필요하다면 float와 double은 피하라
- [ ]  item 61. 박싱된 기본 타입보다는 기본 타입을 사용하라
- [ ]  item 62. 다른 타입이 적절하다면 문자열 사용을 피하라
- [x]  [item 63. 문자열 연결은 느리니 주의하라](내용%20정리/9장/item_63) ➢ 져니
- [ ]  item 64. 객체는 인터페이스를 사용해 참조하라
- [ ]  item 65. 리플렉션보다는 인터페이스를 사용하라
- [ ]  item 66. 네이티브 메서드는 신중히 사용하라
- [ ]  item 67. 최적화는 신중히 하라
- [x]  [item 68. 일반적으로 통용되는 명명 규칙을 따르라](내용%20정리/9장/item_68) ➢ 콩하나

## 10장. 예외

- [ ]  item 69. 예외는 진짜 예외 상황에만 사용하라
- [ ]  item 70. 복구할 수 있는 상황에는 검사 예외를, 프로그래밍 오류에는 런타임 예외를 사용하라
- [ ]  item 71. 필요 없는 검사 예외 사용은 피하라
- [ ]  item 72. 표준 예외를 사용하라
- [ ]  item 73. 추상화 수준에 맞는 예외를 던지라
- [ ]  item 74. 메서드가 던지는 모든 예외를 문서화하라
- [ ]  item 75. 예외의 상세 메시지에 실패 관련 정보를 담으라
- [ ]  item 76. 가능한 한 실패 원자적으로 만들라
- [ ]  item 77. 예외를 무시하지 말라

## 11장. 동시성

- [ ]  item 78. 공유 중인 가변 데이터는 동기화해 사용하라
- [ ]  item 79. 과도한 동기화는 피하라
- [ ]  item 80. 스레드보다는 실행자, 태스트, 스트림을 애용하라
- [ ]  item 81. wait와 notify보다는 동시성 유틸리티를 애용하라
- [ ]  item 82. 스레드 안전성 수준을 문서화하라
- [ ]  item 83. 지연 초기화는 신중히 사용하라
- [ ]  item 84. 프로그램의 동작을 스레드 스케줄러에 기대지 말라

## 12장. 직렬화

- [ ]  item 85. 자바 직렬화의 대안을 찾으라
- [ ]  item 86. Serializable을 구현할지는 신중히 결정하라
- [ ]  item 87. 커스텀 직렬화 형태를 고려해보라
- [ ]  item 88. readObject 메서드는 방어적으로 작성하라
- [ ]  item 89. 인스턴스 수를 통제해야 한다면 readResolve보다는 열거 타입을 사용하라
- [ ]  item 90. 직렬화된 인스턴스 대신 직렬화 프록시 사용을 검토하라

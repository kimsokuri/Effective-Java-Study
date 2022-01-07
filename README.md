# **소쿠리의 스터디**
> + 더이상 미룰수없어요.. 저의 공부..
> + 명서인 이펙티브 자바 늘 시도하다가 실패하는데요.. 
> + 2022년 호랑이의 해니까 `호랑이소쿠리` 도전해보겠습니다!!!!!!!
----
## **책 소개**

Effective Java 3/E - 조슈아 블로크

## **이것만은 지키자**
1. 하루에 적어도 아이템 1개씩은 공부
2. 거짓말은 치지말자...

## **목차**
### *2장 객체생성과 파괴*
[아이템 1. 생성자대신 정적 팩터리 메서드를 고려하라](#아이템-1-생성자대신-정적-팩터리-메서드를-고려하라)  

[아이템 2. 생성자에 매개변수가 많다면 빌더를 고려하라](#아이템-2-생성자에-매개변수가-많다면-빌더를-고려하라)


[아이템 3. private 생성자나 열거 타입으로 싱글턴임을 보증하라](#아이템-3-private-생성자나-열거-타입으로-싱글턴임을-보증하라)

[아이템 4. 인스턴스화를 막으려거든 private 생성자를 사용하라](#아이템-4-인스턴스화를-막으려거든-private-생성자를-사용하라)  

[아이템 5. 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라](#아이템-5-자원을-직접-명시하지-말고-의존-객체-주입을-사용하라)  

[아이템 6. 불필요한 객체 생성을 피하라](#아이템-6-불필요한-객체-생성을-피하라)  

[아이템 7. 다 쓴 객체 참조를 해제하라](#아이템-7-다-쓴-객체-참조를-해제하라)  

[아이템 8. finalizer와 cleaner 사용을 피하라](#아이템-8-finalizer와-cleaner-사용을-피하라)  

[아이템 9. try-finally보다는 try-with-resources를 사용하라](#아이템-9-try-finally보다는-try-with-resources를-사용하라)  

### **3장 모든 객체의 공통 메서드**

[아이템 10. equals는 일반 규약을 지켜 재정의하라](#아이템-10-equals는-일반-규약을-지켜-재정의하라)  

[아이템 11. equals를 재정의하려거든 hashCode도 재정의하라](#아이템-11-equals를-재정의하려거든-hashCode도-재정의하라)  

[아이템 12. toString을 항상 재정의하라](#아이템-12-toString을-항상-재정의하라)  

[아이템 13. clone 재정의는 주의해서 진행하라](#아이템-13-clone-재정의는-주의해서-진행하라)  

[아이템 14. Comparable을 구현할지 고려하라](#아이템-14-Comparable을-구현할지-고려하라)  


### **4장 클래스와 인터페이스** 

[아이템 15. 클래스와 멤버의 접근 권한을 최소화하라](#아이템-15-클래스와-멤버의-접근-권한을-최소화하라)  

[아이템 16. public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라](#아이템-16-public-클래스에서는-public-필드가-아닌-접근자-메서드를-사용하라)  

[아이템 17. 변경 가능성을 최소화하라](#아이템-17-변경-가능성을-최소화하라)  

[아이템 18. 상속보다는 컴포지션을 사용하라](#아이템-18-상속보다는-컴포지션을-사용하라)  

[아이템 19. 상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라](#아이템-19-상속을-고려해-설계하고-문서화하라-그러지-않았다면-상속을-금지하라)  

[아이템 20. 추상 클래스보다는 인터페이스를 우선하라](#아이템-20-추상-클래스보다는-인터페이스를-우선하라)  

[아이템 21. 인터페이스는 구현하는 쪽을 생각해 설계하라](#아이템-21-인터페이스는-구현하는-쪽을-생각해-설계하라)  

[아이템 22. 인터페이스는 타입을 정의하는 용도로만 사용하라](#아이템-22-인터페이스는-타입을-정의하는-용도로만-사용하라)  

[아이템 23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라](#아이템-23-태그-달린-클래스보다는-클래스-계층구조를-활용하라)  

[아이템 24. 멤버 클래스는 되도록 static으로 만들라](#아이템-24-멤버-클래스는-되도록-static으로-만들라)  

[아이템 25. 톱레벨 클래스는 한 파일에 하나만 담으라](#아이템-25-톱레벨-클래스는-한-파일에-하나만-담으라)  

### **5장 제네릭**

[아이템 26. 로 타입은 사용하지 말라](#아이템-26-로-타입은-사용하지-말라)  

[아이템 27. 비검사 경고를 제거하라](#아이템-27-비검사-경고를-제거하라)  

[아이템 28. 배열보다는 리스트를 사용하라](#아이템-28-배열보다는-리스트를-사용하라)  

[아이템 29. 이왕이면 제네릭 타입으로 만들라](#아이템-29-이왕이면-제네릭-타입으로-만들라)  

[아이템 30. 이왕이면 제네릭 메서드로 만들라](#아이템-30-이왕이면-제네릭-메서드로-만들라)  

[아이템 31. 한정적 와일드카드를 사용해 API 유연성을 높이라](#아이템-31-한정적-와일드카드를-사용해-API-유연성을-높이라)  

[아이템 32. 제네릭과 가변인수를 함께 쓸 때는 신중하라](#아이템-32-제네릭과-가변인수를-함께-쓸-때는-신중하라)  

[아이템 33. 타입 안전 이종 컨테이너를 고려하라](#아이템-33-타입-안전-이종-컨테이너를-고려하라)  

### **6장 열거 타입과 애너테이션**
[아이템 34. int 상수 대신 열거 타입을 사용하라](#아이템-34-int-상수-대신-열거-타입을-사용하라)  

[아이템 35. ordinal 메서드 대신 인스턴스 필드를 사용하라](#아이템-35-ordinal-메서드-대신-인스턴스-필드를-사용하라)  

[아이템 36. 비트 필드 대신 EnumSet을 사용하라](#아이템-36-비트-필드-대신-EnumSet을-사용하라)  

[아이템 37. ordinal 인덱싱 대신 EnumMap을 사용하라](#아이템-37-ordinal-인덱싱-대신-EnumMap을-사용하라)  

[아이템 38. 확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라](#아이템-38-확장할-수-있는-열거-타입이-필요하면-인터페이스를-사용하라)  

[아이템 39. 명명 패턴보다 애너테이션을 사용하라](#아이템-39-명명-패턴보다-애너테이션을-사용하라)  

[아이템 40. @Override 애너테이션을 일관되게 사용하라](#아이템-40-@Override-애너테이션을-일관되게-사용하라)  

[아이템 41. 정의하려는 것이 타입이라면 마커 인터페이스를 사용하라](#아이템-41-정의하려는-것이-타입이라면-마커-인터페이스를-사용하라)  

### **7장 람다와 스트림**
[아이템 42. 익명 클래스보다는 람다를 사용하라](#아이템-42-익명-클래스보다는-람다를-사용하라)  

[아이템 43. 람다보다는 메서드 참조를 사용하라](#아이템-43-람다보다는-메서드-참조를-사용하라)  

[아이템 44. 표준 함수형 인터페이스를 사용하라](#아이템-44-표준-함수형-인터페이스를-사용하라)  

[아이템 45. 스트림은 주의해서 사용하라](#아이템-45-스트림은-주의해서-사용하라)  

[아이템 46. 스트림에서는 부작용 없는 함수를 사용하라](#아이템-46-스트림에서는-부작용-없는-함수를-사용하라)  

[아이템 47. 반환 타입으로는 스트림보다 컬렉션이 낫다](#아이템-47-반환-타입으로는-스트림보다-컬렉션이-낫다)  

[아이템 48. 스트림 병렬화는 주의해서 적용하라](#아이템-48-스트림-병렬화는-주의해서-적용하라)  


### **8장 메서드**

[아이템 49. 매개변수가 유효한지 검사하라](#아이템-49-매개변수가-유효한지-검사하라)  

[아이템 50. 적시에 방어적 복사본을 만들라](#아이템-50-적시에-방어적-복사본을-만들라)  

[아이템 51. 메서드 시그니처를 신중히 설계하라](#아이템-51-메서드-시그니처를-신중히-설계하라)  

[아이템 52. 다중정의는 신중히 사용하라](#아이템-52-다중정의는-신중히-사용하라)  

[아이템 53. 가변인수는 신중히 사용하라](#아이템-53-가변인수는-신중히-사용하라)  

[아이템 54. null이 아닌, 빈 컬렉션이나 배열을 반환하라](#아이템-54-null이-아닌,-빈-컬렉션이나-배열을-반환하라)  

[아이템 55. 옵셔널 반환은 신중히 하라](#아이템-55-옵셔널-반환은-신중히-하라)  

[아이템 56. 공개된 API 요소에는 항상 문서화 주석을 작성하라](#아이템-56-공개된-API-요소에는-항상-문서화-주석을-작성하라)  


### **9장 일반적인 프로그래밍 원칙**

[아이템 57. 지역변수의 범위를 최소화하라](#아이템-57-지역변수의-범위를-최소화하라)  

[아이템 58. 전통적인 for 문보다는 for-each 문을 사용하라](#아이템-58-전통적인-for-문보다는-for-each-문을-사용하라)  

[아이템 59. 라이브러리를 익히고 사용하라](#아이템-59-라이브러리를-익히고-사용하라)  

[아이템 60. 정확한 답이 필요하다면 float와 double은 피하라](#아이템-60-정확한-답이-필요하다면-float와-double은-피하라)  

[아이템 61. 박싱된 기본 타입보다는 기본 타입을 사용하라](#아이템-61-박싱된-기본-타입보다는-기본-타입을-사용하라)  

[아이템 62. 다른 타입이 적절하다면 문자열 사용을 피하라](#아이템-62-다른-타입이-적절하다면-문자열-사용을-피하라)  

[아이템 63. 문자열 연결은 느리니 주의하라](#아이템-63-문자열-연결은-느리니-주의하라)  

[아이템 64. 객체는 인터페이스를 사용해 참조하라](#아이템-64-객체는-인터페이스를-사용해-참조하라)  

[아이템 65. 리플렉션보다는 인터페이스를 사용하라](#아이템-65-리플렉션보다는-인터페이스를-사용하라)  

[아이템 66. 네이티브 메서드는 신중히 사용하라](#아이템-66-네이티브-메서드는-신중히-사용하라)  

[아이템 67. 최적화는 신중히 하라](#아이템-67-최적화는-신중히-하라)  

[아이템 68. 일반적으로 통용되는 명명 규칙을 따르라](#아이템-68-일반적으로-통용되는-명명-규칙을-따르라)  


### **10장 예외**

[아이템 69. 예외는 진짜 예외 상황에만 사용하라](#아이템-69-예외는-진짜-예외-상황에만-사용하라)  

[아이템 70. 복구할 수 있는 상황에는 검사 예외를, 프로그래밍 오류에는 런타임 예외를 사용하라](#아이템-70-복구할-수-있는-상황에는-검사-예외를,-프로그래밍-오류에는-런타임-예외를-사용하라)  

[아이템 71. 필요 없는 검사 예외 사용은 피하라](#아이템-71-필요-없는-검사-예외-사용은-피하라)  

[아이템 72. 표준 예외를 사용하라](#아이템-72-표준-예외를-사용하라)  

[아이템 73. 추상화 수준에 맞는 예외를 던지라](#아이템-73-추상화-수준에-맞는-예외를-던지라)  

[아이템 74. 메서드가 던지는 모든 예외를 문서화하라](#아이템-74-메서드가-던지는-모든-예외를-문서화하라)  

[아이템 75. 예외의 상세 메시지에 실패 관련 정보를 담으라](#아이템-75-예외의-상세-메시지에-실패-관련-정보를-담으라)  

[아이템 76. 가능한 한 실패 원자적으로 만들라](#아이템-76-가능한-한-실패-원자적으로-만들라)  

[아이템 77. 예외를 무시하지 말라](#아이템-77-예외를-무시하지-말라)  


### **11장 동시성**

[아이템 78. 공유 중인 가변 데이터는 동기화해 사용하라](#아이템-78-공유-중인-가변-데이터는-동기화해-사용하라)  

[아이템 79. 과도한 동기화는 피하라](#아이템-79-과도한-동기화는-피하라)  

[아이템 80. 스레드보다는 실행자, 태스크, 스트림을 애용하라](#아이템-80-스레드보다는-실행자,-태스크,-스트림을-애용하라)  

[아이템 81. wait와 notify보다는 동시성 유틸리티를 애용하라](#아이템-81-wait와-notify보다는-동시성-유틸리티를-애용하라)  

[아이템 82. 스레드 안전성 수준을 문서화하라](#아이템-82-스레드-안전성-수준을-문서화하라)  

[아이템 83. 지연 초기화는 신중히 사용하라](#아이템-83-지연-초기화는-신중히-사용하라)  

[아이템 84. 프로그램의 동작을 스레드 스케줄러에 기대지 말라](#아이템-84-프로그램의-동작을-스레드-스케줄러에-기대지-말라)  


### **12장 직렬화**

[아이템 85. 자바 직렬화의 대안을 찾으라](#아이템-85-자바-직렬화의-대안을-찾으라)  

[아이템 86. Serializable을 구현할지는 신중히 결정하라](#아이템-86-Serializable을-구현할지는-신중히-결정하라)  

[아이템 87. 커스텀 직렬화 형태를 고려해보라](#아이템-87-커스텀-직렬화-형태를-고려해보라)  

[아이템 88. readObject 메서드는 방어적으로 작성하라](#아이템-88-readObject-메서드는-방어적으로-작성하라)  

[아이템 89. 인스턴스 수를 통제해야 한다면 readResolve보다는 열거 타입을 사용하라](#아이템-89-인스턴스-수를-통제해야-한다면-readResolve보다는-열거-타입을-사용하라)  

[아이템 90. 직렬화된 인스턴스 대신 직렬화 프록시 사용을 검토하라](#아이템-90-직렬화된-인스턴스-대신-직렬화-프록시-사용을-검토하라)









---
## **아이템 1. 생성자대신 정적 팩터리 메서드를 고려하라**
클라이언트가 클래스의 인스턴스를 얻는 전통적인 수단은 `public 생성자` 다.  
하지만 알아둬야할 기법이 하나 더 있다.
#### `정적 팩터리 메서드 (static factory method)`
클래스의 인스턴스를 반환하는 단순  정적 메서드
>[예제] 기본타입인 `boolean` 값을 받아 `Boolean 객체참조` 로 변환
##### Boolean.valueOf(boolean)
``` java
public static Boolean valueOf(boolean b){
    return b ? Boolean.TRUE : Boolean.FALSE; 
    // boolean b의 값이 true이면 Boolean의 TRUE, false이면 Boolean의 FALSE 리턴
}
```
### **장점**
1. **이름을 가질 수 있다.**  
    생성자에 넘기는 매개변수와 생성자 자체만으로는 반환되는 객체의 특성을 제대로 설명하지 못한다.  
    이름만 잘 지으면 반환될 객체의 특성을 쉽게 묘사할 수 있다는것!  
    > 값이 소수인 BigInteger를 반환한다

    #### *생성자 : BigInteger(int, int, Random)*
    : 하나의 시그니처로는 생성자를 하나만 만들수있다.  
    입력 매개변수들의 순서를 다르게 한 생성자를 추가하는 방법이 있지만 좋지않은 발상이다.  
    그런 경우 각 생성자마다 무슨 객체를 생성하는지 모르니까 문서를 일일이 참고하지않는다면..  
    엉뚱한 생성자를 호출 할 수 있다.
    #### *정적 팩터리 메서드 : BigInteger.probablePrime (JAVA 4)*
    한 클래스에 시그니처가 같은 생성자가 여러개 필요한 경우 정적팩터리메서드로 변경하고 이름을 명확히!

 2. **호출될 마다 인스턴스를 새로 생성하지는 않아도 된다.**  
    이 덕분에 [불변 클래스(  class)](#아이템-17-변경-가능성을-최소화하라)는 아래의 방법으로 불필요한 객체생성을 피할수있다.  
        * 인스턴스를 미리 만들어 놓는다.  
        * 새로 생성한 인스턴스를 캐싱하여 재활용한다.  
    * 또한 동치인 인스턴스가 단 하나뿐임을 보장할 수 있다.
            >   a == b 일 때만 a.eqauls(b) 가 성립된다.      
    * 대표적인 예로 [Boolean.valueOf(boolean)](#booleanvalueofboolean)메서드는 객체를 아예 생성하지않는다.   
    -> (특히 생성비용이 큰) 같은 객체가 자주 요청되는 상황이라는 성능을 끌어올려준다.  
    (`플라이웨이트 패턴`: 이와 유사함)
    > `인스턴스 통제 클래스 (instance-controlled-class)` 
    >> 반복되는 요청에 같은 객체를 반환하여 인스턴스의 생명주기를 철저히 통제할 수 있다.  
    >>>플라이웨이트 패턴의 근간, [열거타입](#아이템-34-int-상수-대신-열거-타입을-사용하라)은 인스턴스가 하나만 만들어짐을 보장한다.
    * 인스턴스를 통제하는 이유는?  
    클래스를 [싱글톤(singleton)](#아이템-3-private-생성자나-열거-타입으로-싱글턴임을-보증하라) 또는 [인스턴스화 불가(noninstaniable)](#아이템-4-인스턴스화를-막으려거든-private-생성자를-사용하라)로 만들수 있다.

3. **반환 타입의 하위 타입 객체를 반환할 수 있는 능력이 있다.**  
   반환될 객체의 클래스를 자유롭게 선택할수있게하는 엄청난 유연성!!
   ``` java
   class Earth {
       public static Animal getAnimal(boolean isStudy){
           return isStudy ? new Person() : new Pig();
       }
   }
   
   class Animal {}
   class Person extends Animal {}
   class Pig extends Animal {}
   ```
   * API 생성시 구현 클래스를 공개하지않고도 그 객체를 반환할 수 있어 API 작게 유지가능  
     * [인터페이스 기반 프레임워크](#아이템-20-추상-클래스보다는-인터페이스를-우선하라): 정적 팩터리 메서드의 반환 타입이 `인터페이스`
     * `자바 8 이전` : 인터페이스에 정적 메서드 선언 불가  
     이름이 **Type**인 인터페이스를 반환하는 정적 메서드가 필요하면   
     **Types**라는 **(인스턴스화 불가인) 동반클래스**를 만들어 그안에 정의하는것이 관례였다. 
     * `자바 8 이후` : 인터페이스에 정적 메서드 선언 가능, `public 정적 멤버만 허용`   
     (인스턴스화 불가인) 동반클래스를 굳이 만들지 않음.  
     -> 동반클래스에 두었던 `public 정적 멤버들(필드, 클래스..)` 상당수를 그냥 인터페이스에 두면 된다.  
     * `자바 9` : 인터페이스에 정적 메서드 선언 가능  
      `public 정적 멤버, private 정적 멤버 메서드 가능` 

        |인터페이스 내부에 선언 가능한 멤버| `자바 8 이전` | `자바 8` | `자바 9` |
        | -------- | ----------- |----------- |----------- |
        | public 정적 멤버 필드  |X|O|O|
        | public 정적 멤버 메서드 |X|O|O|
        | public 정적 멤버 클래스 |X|O|O|
        | | | |
        | private 정적 멤버 필드 |X|X|X|
        | private 정적 멤버 메서드 |X|X|O|
        | private 정적 멤버 클래스 |X|X|X|
    * `java.util.Collections 인스턴스화 불가 클래스`  
    핵심 인터페이스들에 수정불가나 동기화 등의 기능을 덧붙인 총 `45개의 유틸리티 구현체`등을 해당 클래스의 `정적 팩터리 메서드`를 통해 얻게 함  
        > 45개의 클래스를 공개하지 않기 때문에 API를 훨씬 작게 만들수있다.  
        > 또한 API를 사용하기 위해 익혀야하는 개념과 난이도도 낮춤  
        > *프로그래머는 명시한 인터페이스대로 동작하는 객체를 얻는다는것이 명확함.*  
        > 즉, **정적 팩터리 메서드**를 사용하는 클라이언트는 얻은 객체를 [`인터페이스`](#아이템-64-객체는-인터페이스를-사용해-참조하라) 만으로 다룬다.

4. **입력 매개변수에 따라 매번 다른 클래스의 객체를 반환할 수 있다.**  
   반환하려는 객체가 `반환타입의 하위타입`이기만 하면 어떤 클래스의 객체를 반환하든 상관없다.  
   * [EnumSet 클래스](#아이템-36-비트-필드-대신-enumset을-사용하라)  
   public 생성자 없이 오직 정적 팩터리 메서드만 제공한다.    
   클라이언트는 아래 두개의 클래스 존재를 모름~   
   그냥 호출할때 EnumSet 클래스의 속성을 가진 인스턴스가 내려오겠구나~ 생각할수있음  
    **OpenJDK** : 원소의 수에 따라 두가지 하위 클래스 중 하나의 인스턴스 반환  
      * 원소가 64개 이하 : *RegularEnumSet* 인스턴스 (`long 변수`로 관리)
      * 원소가 65개 이상 : *JumboEnumSet* 인스턴스 (`long 배열`로 관리)   
5. **정적 팩터리 메서드를 작성하는 시점에는 반환할 객체의 클래스가 존재하지 않아도 된다.**  
   ``` java
   public class MyBook{
    public static List<MyBookInterface> getInstance(){
        return new ArrayList<>();
    }
   }

   public interface MyBookInterface {
       // 아직 구현 되지 않은 구현체
   }

   public class MyBookImpl implements MyBookInterface{
       // 추후 MyBookInterface 를 상속받는 구현 클래스 생성
   }

   public class test {
       public static void main(String [] args ){
        List<MyBookInterface> bookImpls = MyBook.getInstance();

        // 추후 구현된 클래스를 생성후 bookImpls에 추가
        MyBookInterface bookImpl = new MyBookImpl();
        bookImpls.add(bookImpl);
       }
   }
   ```
   이런 유연함으로 `서비스 제공자 프레임워크(service provider framework)`를 만드는 근간이 된다.  
   서비스 제공자 프레임워크에서의 `제공자(provider)`는 **서비스의 구현체**다.  
   구현체들을 클라이언트에 제공하는 역할을 프레임워크가 통제  
   > 서비스 제공자 프레임워크(service provider framework)
   * **핵심 컴포넌트**
   1. `서비스 인터페이스 (service interface)` : 구현체의 동작을 정의  
   ex . JDBC - Connection 
   2. `제공자 등록 API (provider registration API)` : 제공자가 구현체를 등록시 사용  
    ex . JDBC - DriverManager.registerDriver 
   3. 💥`서비스 접근 API (service access API)` : 클라이언트가 서비스의 인스턴스를 얻을때 사용
      * 클라이언트는 원하는 구현체의 조건을 명시할수있다.
      * 조건을 명시하지 않으면 기본 구현체 or 지원하는 구현체들을 하나씩 돌아가며 반환한다.
      * 공급자가 제공하는것보다 더 풍부한 서비스 인터페이스를 반환할 수 있다.
        * 브릿지 패턴(Bridge pattern) (https://lktprogrammer.tistory.com/35)
 
      ex . JDBC - DriverManager.getConnection    
   4. `서비스 제공자 인터페이스(service provider interface)` : `서비스 인터페이스`의 **인스턴스를 생성**하는 팩터리 객체를 설명한다.  
   만약, 없다면 각 구현체를 인스턴스로 생성할때 [리플렉션](#아이템-65-리플렉션보다는-인터페이스를-사용하라)을 사용해야 한다.   
    ex . JDBC - Driver
  
 
       
     
### **단점**  
1. **상속을 하려면 public이나 protected 생성자가 필요하니 정적 팩터리 메서드만 제공하면 하위 클래스를 만들 수 없다.**  
위에서 말한 [컬렉션 프레임워크의 유틸리티 구현 클래스](*-`java.util.Collections-인스턴스화-불가-클래스`)들은 `private 생성자만 있어서` 상속할 수 없다.   
아래 기능을 구현하기 위해서는 제약을 지켜야지만 가능 (오히려 위 제약이 장점;)  
   1. 상속보다 [컴포지션](#아이템-18-상속보다는-컴포지션을-사용하라)을 사용하도록 유도
   2. [불변타입](#아이템-17-변경-가능성을-최소화하라)으로 만들기     
2. **정적 팩터리 메서드는 프로그래머가 찾기 어렵다**  
생성자처럼 API 설명에 명확하게 드러나지 않아서   
사용자는 정적 팩터리 메서드 방식 클래스를 인스턴스화할 방법을 알아내야한다.  
-> 알려진 규약을 통해 정적 팩터리 메서드 이름을 지어야한다.
> 정적 팩터리 메서드 명명 방식

* *from* : 매개변수를 하나 받아서ㅓ 해당 타입의 인스턴스를 반환하는 형변환 메서드
``` java
Date d = Date.from(instant);
```
* *of* : 여러 매개변수를 받아 적합한 타입의 인스턴스를 반환하는 집계 메서드 
``` java
Set<Rank> faceCards = EnumSet.of(JACK, QUEEN, KING); 
// 반환 인스턴스를 Set<Rank> 로 명시
```
* *valueOf* : from과 of의 더 자세한 버전
``` java
BigInteger prime = BigInteger.valueOf(Integer.MAX_VALUE);
// 어떤 타입의 인스턴스를 반환하는것을 원하는지 더 자세히 명시함. 여기선 MAX_VALUE
```
* *instance* 또는 *getInstance* : (매개변수를 받는다면) 매개변수로 명시한 인스턴스를 반환하지만,   
  `같은 인스턴스임을 보장하지않는다.`
``` java
StackWalker luke = StackWalker.getInstance(options);
```
* *create* 혹은 *newInstance* : *instance* 또는 *getInstance*와 같지만,   
  `매번 새로운 인스턴스를 생성해 반환함을 보장한다.`
``` java
Object newArray = Array.newInstance(classObject, arrayLen);
// 매개변수로 받은 클래스와 길이에 해당하는 늘 새로운 인스턴스를 반환한다.
```
* *getType* : *getInstance*와 같으나, 생성할 클래스가 아닌 다른 클래스에 팩터리 메서드를 정의할 때 쓴다.   
  `"Type"은 팩터리 메서드가 반환할 객체의 타입을 써주면 된다.`
``` java
FileStore fs = Files.get"FileStore"(path);
// FileStore 클래스가 아닌 
// Files 클래스에 리턴값이 FileStore 인 팩터리 메서드가 정의되어 있음.
```
* *newType* : *newInstance*와 같으나, 생성할 클래스가 아닌 다른 클래스에 팩터리 메서드를 정의할 때 쓴다.   
  `"Type"은 팩터리 메서드가 반환할 객체의 타입을 써주면 된다.`
``` java
BufferdReader br = Files.new"BufferedReader"(path);
// BufferReader 클래스가 아닌 
// Files 클래스에 리턴값이 BufferReader 인 팩터리 메서드가 정의되어 있음.
```
* *type* : *getType* 과 *newType*의 간결한 버전  
``` java
List<Complaint> litany = Collections."list"(legacyLitany);
// Collections 유틸리티 클래스에서 list 인스턴스를 반환한다.
```

❗ 정리
```
정적 팩터리 메서드와 public 생성자는 각자의 쓰임새가 있으니 
상대적인 장단점을 이해하고 사용하는 것이 좋다!
하지만 정적 팩터리 메서드를 사용하는게 유리한 경우가 많으니까 무작정 생성자 쓰지는 말자!
```

---

## **아이템 2. 생성자에 매개변수가 많다면 빌더를 고려하라**
 정적 팩터리 메서드와 생성자의 제약 : `선택적 매개변수가 많을 때 적절히 대응하기는 어렵다는 것`
 > 식품 포장의 영양정보 클래스

 영양정보는 보통 20개가 넘는 선택항목으로 이루어진다.  
 하지만 대부분의 제품은 선택 항목의 대다수 값이 거의 0이다.

### `1.점층적 생성자 패턴(telescoping constructor pattern)`   
필수 매개변수만 받는 생성자, 필수 매개변수와 선택 매개변수 1개를 받는 생성자 .. 등등  
매개변수를 점점 늘려 생성자를 만드는 방식이다.
``` java
public class NutritionFacts {
    private final int servingSize;  // ml   / 필수
    private final int servings;     // 회   / 필수
    private final int calories;     // 칼로리 / 선택
    private final int fat;          // g    / 선택
    private final int sodium;       // mg   / 선택
    private final int carbohydrate; // g    / 선택

    public NutritionFacts(int servingSize, int servings){
        this(servingSize, servings, 0); // 아래 생성자 호출
    }

    public NutritionFacts(int servingSize, int servings, int calories){
        this(servingSize, servings, calories, 0); // 아래 생성자 호출
    }

    public NutritionFacts(int servingSize, int servings, int calories, int fat){
        this(servingSize, servings, calories, fat, 0); // 아래 생성자 호출
    }

    public NutritionFacts(int servingSize, int servings, int calories, int fat, int sodium){
        this(servingSize, servings, calories, fat, sodium, 0); // 아래 생성자 호출
    }

    public NutritionFacts(int servingSize, int servings, int calories, int fat, int sodium, int carbohydrate){
        this.servingSize = servingSize;
        this.servings = servings;
        this.calories = calories;
        this.fat = fat;
        this.sodium = sodium;
        this.carbohydrate = carbohydrate;
    }

}

```

이 클래스의 인스턴스를 만드려면 원하는 매개변수를 모두 포함한 생성자 중 가장 짧은것을 골라 호출하면 된다.
``` java
NutritionFacts cocaCola = new NutritionFacts(240, 8, 100, 0, 35, 27);
```
보통 이런 생성자는 사용자가 설정하길 원치않는 매개변수까지 포함하기 쉬운데, 어쩔수없기 그런 매개변수에도 값을 지정해야한다. 위 코드에서는 지방(fat)에 0을 넘겼다.  
**점층적 생성자 패턴은 매개변수 개수가 많아지면 클라이언트 코드를 작성하거나 읽기 어려워진다**  

클라이언트가 실수로 매개변수의 순서를 바꿔 건네줘도 컴파일러는 알아채지 못하고  
결국 [런타임에 엉뚱한 동작](#아이템-51-메서드-시그니처를-신중히-설계하라)을 할수있다! 


### `2.자바 빈즈 패턴(JavaBeans pattern)`  
매개변수가 없는 생성자로 객체를 만든 후,   
세터(setter) 메서드들을 호출해 원하는 매개변수의 값을 설정하는 방식   

``` java
public class NutritionFacts {
    // 매개변수들은 (기본값이 있다면) 기본값으로 초기화된다.
    private int servingSize = -1;   //필수 / 기본값 없음
    private int servings = -1;      //필수 / 기본값 없음
    private int calories = 0;
    private int fat = 0;
    private int sodium = 0;
    private int carbohydrate = 0;

    public NutritionFacts(){}

    //세터 메서드
    public void setServingSize(int val){ servingSize = val; }
    public void setServings(int val){ servings = val; }
    public void setCalories(int val){ calories = val; }
    public void setFat(int val){ fat = val; }
    public void setSodium(int val){ sodium = val; }
    public void setCarbohydrate(int val){ carbohydrate = val; }
}

-------------------------------------------

NutritionFacts cocacola = new NutritionFacts();
cocaCola.setServingSize(240);
cocaCola.setServings(8);
cocaCola.setCalories(100);
cocaCola.setSodium(35);
cocaCola.setCarbohydrate(27);
```
  `단점` : 객체하나를 만들기 위해서 메서드를 여러개 호출해야함 -> 위 처럼 5개 메서드 호출   
  [`-> 일관성이 깨지며 클래스를 불변으로 만들 수 없고 스레드 안정성을 얻기 힘들다.`](#아이템-17-변경-가능성을-최소화하라)

  객체가 완전히 생성되기 전까지 `일관성(consistency`이 무너진 상태에 놓이게 된다.  
  생성자가 매개변수없는 생성자니까! 매개변수의 유효성을 확인할수있는 방법이 생성시에는 없음  
  점층적 생성자 패턴에서는 *매개변수 유효성* 을 생성자에서 확인하면 일관성 유지가 가능했었다.  

  `단점 극복 방법` : 생성이 끝난 객체를 수동으로 *얼리고(freezing)* 얼리기 전에는 사용할수 없도록 한다.  
  하지만... `freeze` 메서드를 확실히 호출했는지 컴파일러가 보증할 방법이 없어 런타임 오류에 취약함

### `3. 빌더 패턴(Builder pattern)`   
점층적 생성자 패턴의 안정성과 자바빈즈 패턴의 가독성 겸비  
``` java
public class NutritionFacts {
    private final int servingSize;  // ml  
    private final int servings;     // 회  
    private final int calories;     // 칼로리
    private final int fat;          // g    
    private final int sodium;       // mg  
    private final int carbohydrate; // g    

    public static class Builder {
        // 필수 매개변수
        private final int servingSize; 
        private final int servings;

        // 선택 매개변수
        private final int calories      = 0; // 칼로리
        private final int fat           = 0; // g    
        private final int sodium        = 0; // mg  
        private final int carbohydrate  = 0; // g    

        public Builder(int servingSize, int servings){
            this.servingSize = servingSize;
            this.servings = servings;
        }

        public Builder calories(int val){
            calories = val;
            return this; // Builder 자신 반환
        }
        public Builder fat(int val){
            fat = val;
            return this; // Builder 자신 반환
        }
        public Builder sodium(int val){
            sodium = val;
            return this; // Builder 자신 반환
        }
        public Builder carbohydrate(int val){
            carbohydrate = val;
            return this; // Builder 자신 반환
        }
        
        public NutritionFacts build(){
            return new NutritionFacts(this); // NutritionFacts 생성자에 Builder 전달
        }
    }

    private NutritionFacts(Builder builder){
        servingSize = builder.servingSize;
        servings = builder.servings;
        calories = builder.calories;
        fat = builder.fat;
        sodium = builder.sodium;
        carbohydrate = builder.carbohydrate;
    }
}

```
NutritionFacts 클래스는 불변이며, 모든 매개변수의 기본값들을 한곳에 모아뒀다.  
`빌더의 세터 메서드`들은 `빌더 자신을 반환`하기 때문에 **연쇄적으로 호출**이 가능하다.  
-> *플루언트API(flient API) 또는 메서드 연쇄(method chaining)*  
-> 명명된 선택적 매개변수(named optional parameters) 흉내 낸 것 
``` java
NutritionFacts cocaCola = new NutritionFacts.Builder(240, 8) //필수 매개변수 세팅
                        .calories(100).sodium(35).carbohydrate(27) //선택 매개변수 세팅
                        .build(); // builer에 세팅된 매개변수로 NutritionFacts 객체 생성
```
필요한 객체를 직접 만드는 대신,   
필수 매개변수만으로 `생성자(혹은 정적 팩터리 메서드)`를 호출해 빌더 객체를 얻는다.  
빌더 객체가 제공하는 일종의 `세터메서드`로 원하는 선택 매개변수들을 설정한다.  
매개변수가 없는 `build 메서드`를 호출해 (보통 불변인) **객체**를 얻는다.

> 유효성 검사

잘못된 매개변수를 최대한 일찍 발견하려면 
* `빌더의 생성자`와 `메서드`에서 입력 매개변수를 검사하고, 
* `build 메서드가 호출하는 생성자`에서 여러 매개변수에 걸친 불변식(invariant)을 검사하자.
  

불변식을 보장하려면  
* [빌더로부터 매개변수를 복사한 후 해당 객체 필드들도 검사해야한다.](#아이템-50-적시에-방어적-복사본을-만들라)
->  검사 후 잘못된 점을 발견하면 어떤 매개변수가 잘못되었는지 자세히 알려주는 메세지를 담아 `IllegalArgumentException`을 던지면 된다.

*불변( )* 이란?  
어떠한 변경도 허용하지 않는다는 뜻
변경을 허용하는 가변(mutable) 객체와 구분하는 용도  
ex. String 객체

 *불변식(invariant)* 이란?  
 프로그램이 실행되는 동안, 혹은 정해진 기간 동안 반드시 만족해야하는 조건  
 변경을 허용할수는 있으나 주어진 조건 내에서만 허용한다는것  
 ex. 리스트의 크기는 반드시 0이상 : 음수값이 된다면 불변식이 깨진것

  -> 가변 객체에도 불변식은 존재할수있음. 


> 계층적으로 설계된 클래스와 함께 쓰이기 좋다.
``` java
// 피자의 다양한 종류를 표현하는 계층구조의 루트에 놓인 "추상 클래스"
// 추상 클래스는 추상 빌더
public abstract class Pizza {
    public enum Topping { HAM, MUSHROOM, ONION, PEPPER, SAUSAGE }
    final Set<Topping> toppings;

    abstract static class Builder<T extends Builder<T>> {
        // 비어있는 Topping 클래스에 대한 EnumSet 생성
        EnumSet<Topping> toppings = EnumSet.noneOf(Topping.class);

        public T addTopping(Topping topping){
            toppings.add(Objects.requireNonNull(topping)); // toppings이 null이라면 바로 NPE 발생 
            // addTopping 메서드를 쓸때 topping은 무조건 null아니면 안된다.
            
            return self(); 
            // 공통된 메서드를 사용할때 각 하위타입에 맞춰서 리턴을 시켜야하는데 
            // 그때 self메서드를 하위타입이 스스로 자신의 타입에 맞게 리턴시키도록 self메서드를 재정의 시키게한다.
        } 

        abstract Pizza bulid();

        // 하위 클래스는 이 메서드를 재정의(overriding)하여 "this" 반환해야함.
        protected abstract T self();
    }

    Pizza(Builder<?> builder){
        toppings = builder.toppings.clone(); //아이템50 참조
    }

}

```  

`Pizza.Builder 클래스`는 [재귀적 타입 한정(recursive type bound)](#아이템-30-이왕이면-제네릭-메서드로-만들라)을 이용하는 제네릭 타입이다.

abstract static class Builder `<T extends Builder<T>>`  
-> 자기 자신이 들어간 표현식을 사용하여 타입 매개변수의 허용범위를 한정한다.  
-> <T>는 Any?의 줄임말 = Any?>타입을 상속받은 것들이라면 다된다는 의미.(upper Bounded 되었다고함.)  
-> T는 Builder<T>의 제한을 받는 타입이여야한다.  
`즉! T는 Builder를 상속받은 타입이여야한다는것!`

피자라는 상위 클래스의 Builder 클래스의 요소들을 사용하기 위해서는   
뉴욕피자의 빌더에서 피자클래스의 빌더를 상속받아야지만 오버라이딩 및 사용이 가능하다? 그래서 `extends Pizza.Builder<Builder> ` 를 한거고?

나를 상속하려면 넌 여전히 내 타입이여야해! -> <T extends Builder<T>>

``` java
public static class Builder extends Pizza.Builder<Builder> { ... }
// 뉴욕피자의 빌더는 피자 클래스의 Builder 클래스를 상속받았기때문에 Builder의 타입으로 들어갈수있다.  
```
https://medium.com/@joongwon/java-java%EC%9D%98-generics-604b562530b3


```

```


여기에 `추상메서드인 self()`를 더해 하위클래스에서는 형변환하지 않고도 메서드 연쇄를 지원할수있다.  
-> self 타입이 없는 자바를 위한 우회 방법 `시뮬레이트한 셀프타입 관용구(simulated self-type)`

> Pizza 하위 클래스 : 뉴욕피자
``` java
public class NyPizza extends Pizza {
    public enum Size {SMALL, MEDIUM, LARGE};
    private final Size size;

    public static class Builder extends Pizza.Builder<Builder> {
        private final Size size; //사이즈는 필수

        public Builder(Size size){ // 생성자
            this.size = Object.requireNonNull(size); //size가 없으면 NPE
        }

        // 구현체 클래스를 반환하도록 선언
        // 하위 클래스의 메서드(build())가 상의 클래스의 메서드가 정의 한 반환 타입(Pizza) 이 아닌, 
        // 그 하위 타입(NyPizza)을 반환 : 공변환 타이핑 (convariant return typing) 
        @Override
        public NyPizza build(){
            return new NyPizza(this); // this는 Builder
        }

        @Override
        protected Builder self(){
            return this; // this 는 Builder
        }
    }

    private NyPizza(Builder builder){
        super(builder);
        size = builder.size;
    }
}

```
> Pizza 하위 클래스 : 칼초네피자
``` java
public class Calzone extends Pizza {
    private final boolean sauceInside;

    public static class Builder extends Pizza.Builder<Builder> {
        private boolean sauceInside = false; //기본값 //선택

        // 생성자 없음
        
        public Builder sauceInside(){
           sauceInside = true;
           return this;
        }

        // 구현체 클래스를 반환하도록 선언
        // 하위 클래스의 메서드(build())가 상의 클래스의 메서드가 정의 한 반환 타입(Pizza) 이 아닌, 
        // 그 하위 타입(Calzone)을 반환 : 공변환 타이핑 (convariant return typing) 
        @Override
        public Calzone build(){
            return new Calzone(this); // this는 Builder
        }

        @Override
        protected Builder self(){
            return this; // this 는 Builder
        }
    }

    private Calzone(Builder builder){
        super(builder);
        sauceInside = builder.sauceInside;
    }
}


```
`객체 생성 코드`
``` java
// SMALL사이즈의 햄,양파 뉴욕피자
NyPizza nyPizza = new NyPizza.Builder(SMALL).addTopping(ONION).addTopping(HAM).build();

// 소스가 들어간 햄 깔조네피자
Calzone calzone = new Calzone.Builder().addTopping(HAM).sauceInside().build();
```
위와 같이 빌더를 이용하면 가변인수(varargs) 매개변수를 여러개 사용할 수 있다. 각각을 적절한 메서드로 나눠 선언하면 된다.

`addToping()` : 매서드를 여러번 호출하도록 하고 각 호출때 넘겨진 매개변수들을 하나의 필드로 모음.

* 장점
  1.  빌더하나로 여러객체를 순회하면서 만들수 있다.
  2.  빌더에 넘기는 매개변수에 따라 다른 객체를 만들수도 있다.
  3.  객체마다 부여되는 일련번호와 같은 특정 필드는 빌더가 알아서 채우도록 할수도있다.
* 단점  
  1. 객체를 만드려면 빌더부터 만들어야한다. 성능에 민감할때는 문제가 될수도있다.
  2. 점층적 생성자 패턴보다는 코드가 장황해서 매개변수가 4개 이상은 되어야 값어치를 한다.   
   but, API는 시간이 지날수록 매개변수 늘어남.  


💥 정리  
생성자나 정적 팩터리가 처리해야 할 *매개변수가 많다면*  빌더 패턴을 선택하는것이 더 낫다!  
매개변수 중 다수가 필수가 아니거나.. 같은 타입이면 특히 더!  
점층적 생성자 보다는 클라이언트 코드를 읽고 쓰기가 훨씬 간결  
자바빈즈보다 훨씬 안전


### 참고 
``` java
----------------------------------------------------------------------------
EnumSet
----------------------------------------------------------------------------
1. EnumSet.noneOf
EnumSet<Topping> toppings = EnumSet.noneOf(Topping.class);
return toppings : []

1. EnumSet.allOf
EnumSet<Topping> toppings = EnumSet.allOf(Topping.class);
return toppings : [HAM, MUSHROOM, ONION, PEPPER, SAUSAGE]
----------------------------------------------------------------------------

----------------------------------------------------------------------------
Objects.requireNonNull : 명시성, 빠른 실패
----------------------------------------------------------------------------
public static <T> T requireNonNull(T obj) { //null이면 바로 NPE
        if (obj == null)
            throw new NullPointerException();
        return obj;
}

1. 명시성(explicity)
public class A {
    String name;
}

public class B {
    A a;

    public B(A a){
        this.a = Objects.requireNonNull(a); // a가 null이면 바로 NPE 터짐.
        // -> A 객체가 절대 null이면 안된다는것을 명시하는것임.
    }

}

2. 빠른 실패 (fail-fast) : 장애가 발생한 시점에서 즉시 파악할수 있음
A a = null;
B b = new B(a); // B 생성시점에 바로 NPE 발생

// 사용하지않는다면 생성시점까지는 오류발생하지않지만 setter 메서드에서 NPE
b.getA(); // NPE 발생

// java 9 
* Optional 과 비슷하게 사용가능 (null일수도 있고, 아닐수도 있는..)
requireNonNullElseGet(T obj, Supplier<? extends T> supplier); 
```

---


## **아이템 3. private 생성자나 열거 타입으로 싱글턴임을 보증하라**

`싱글턴(singleton)` : 인스턴스를 오직 하나만 생성할 수있는 클래스, but 클래스를 싱글턴으로 만들면 테스트하기가 어려울수있다. (싱글턴 인스턴스를 가짜(mock)구현 X)  
ex. [함수](#아이템-24-멤버-클래스는-되도록-static으로-만들라)와 같은 무상태 객체, 설계상 유일해야하는 시스템 컴포넌트  

### 싱글턴을 만드는 방식
1. **public static final 필드 방식의 싱글턴**
   ``` java
    public class Elvis {
        // 해당 코드가 public이므로 싱글턴임이 명확히 드러난다는것임!/
        // final 이므로 절대로 다른객체를 참조할수가없음!
        public static final Elvis INSTANCE = new Elvis();
        // 생성자는 private으로 감춘다.
        private Elvis() { ... }

        public void leaveTheBuilding() { ... }
    }
   ```
    생성자는 Elvis.INSTANCE를 초기화 할때 딱 `한번`만 호출된다.  
    public, protected 생성자가 없으므로 Evlis 클래스가 초기화 될때 만들어진 `INSTANCE가 전체 시스템에서 하나뿐`임이 보장된다.  
    -> 예외) [리플렉션API](#아이템-65-리플렉션보다는-인터페이스를-사용하라) 인 `AccessibleObject.setAccessible`을 사용해 private 생성자를 호출할 수있다.   
    하지만 이런 공격을 방어하려면 두번째 객체가 생성되려 할때 예외를 던지게 하면 된다.

2. **정적 팩터리 메서드 방식의 싱글턴**
   ``` java
   public class Elvis {
       private static final Elvis INSTANCE = new Elvis();
       private Elvis() { ... }
       public static Elvis getInstance() {
            return INSTANCE;
        }
        public void leaveTheBuilding() { ... }
   }
   ```
   `Elvis.getInstance`는 항상 같은 객체의 참조를 반환하므로 제2의 Elvis 인스턴스는 결코 만들어지지 않는다.
   * 장점  
       1. API를 바꾸지 않고도 싱글턴이 아니게 변경할 수 있음.   
       : 팩터리 메서드를 변경하여 호출하는 스레드 별로 다른 인스턴스를 반환할수 있다.
       ``` java
        public class Elvis {
            private static final Elvis INSTANCE = new Elvis();
            private Elvis() { ... }
            public static Elvis getInstance() {
                // return INSTANCE;
                return new Elvis(); // getInstance를 호출할때마다 Elvis new
            }
            public void leaveTheBuilding() { ... }
        }
       ```  
       2. 정적 팩터리 메서드를 [**제네릭 싱글턴 팩터리 메서드**](#아이템-30-이왕이면-제네릭-메서드로-만들라)로 만들수있다.
       3. 정적 팩터리의 메서드 참조를 공급자(supplier)로 사용할수 있다  
       ex. [`Elvis::getInstance` 를 `Supplier<Elvis>`로 사용](#아이템-43-람다보다는-메서드-참조를-사용하라) 

    이런 장점들이 필요하지 않다면 `public 필드 방식`이 좋다    

* 위의 두가지 방식(public, 정적 팩터리)으로 만든 싱글턴 클래스를 `직렬화`하려면 단순히 `Serializable`을 선언하는것만으로는 부족!  
[모든 인스턴스 필드를 *일시적(transient)* 이라고 선언하고 *readResolve* 메서드를 제공해야함.](#아이템-89-인스턴스-수를-통제해야-한다면-readresolve보다는-열거-타입을-사용하라)
    * 저것처럼 하지 않으면 직렬화된 인스턴스를 **역직렬화** 할때마다 *새로운 인스턴스*가 만들어진다
  > 가짜 Evlis의 탄생을 막기 위한 readResolve() 메서드 
    ``` java
    public class Elvis {
        private static final Elvis INSTANCE = new Elvis();
        private Elvis() { ... }
        public static Elvis getInstance() {
            return INSTANCE;
        }
        public void leaveTheBuilding() { ... }
        
        // 싱글턴입을 보장해주는 readResolve 메서드
        private Object readResolve(){
            // '진짜' Elvis를 반환하고 가짜 Elvis 는 가비지 컬렉터에 맡긴다. 
            return INSTANCE;
        }
    }
    ```


3. 👍 **열거 타입 방식의 싱글턴**   
   **원소가 하나뿐인 열거 타입을 선언하는 것 -> 가장 좋은 방법**
   ``` java
   public enum Elvis {
       INSTANCE; // INSATNCE 원소 하나인 Evlis Enum객체 생성
       public void leaveTheBuilding(){ ... }
   }
   ```
    public 필드 방식과 비슷하지만, 더 간결하고, 추가 노력없이 직렬화가 가능하다  
    아주 복잡한 직렬화 상황 또는 리플렉션 공격에도 제 2의 인스턴스가 생기는 일을 완벽히 막아준다.  
    * 예외 : 만드려는 싱글턴이 Enum외의 클래스를 *상속*하는 경우 이 방법은 사용 불가 (but 열거타입이 다른 인터페이스를 구현하도록 선언은 가능)

---
## 아이템 4. 인스턴스화를 막으려거든 private 생성자를 사용하라  
 가끔씩.. **정적 메서드와 정적 필드**만을 담은 클래스를 만들고 싶을때가 있다..(아직 저는 없고요 (￣y▽,￣)╭ )
 * `java.lang.Math`와 `java.util.Arrays` 처럼 기본 타입 값이나 배열 관련 메서드들을 모아 놓는 경우
 * `java.util.Collections` 처럼 특정 인터페이스를 구현하는 객체를 생성해주는 *정적 메서드* 또는 *정적 팩터리 메서드* 들을 모아 놓는 경우 (java8 : 해당 메서드들을 인터페이스에 넣을 수 있음)
 * `final 클래스와 관련한 메서드`들을 모아놓는 경우  
 final 클래스를 상속해서 하위 클래스에 메서드를 넣는것은 불가능

### 정적 멤버만 담은 유틸리티 클래스는 *인스턴스화를 하려고 설계한것이 아님!*

클래스에 생성자를 명시하지않으면 컴파일러가 자동으로 *매개변수가 없는 기본 생성자*를 만든다.  
-> 클라이언트 입장에서는 이 생성자가 자동으로 만든건지, 수동으로 만든건지 구분할수없으며, 실제로 생성자가 자동으로 만들어짐에 따라서 의도치않게 인스턴스화가 가능한 클래스가 API에서 종종 목격되기도 한다.

> 추상 클래스도 인스턴스화를 막을 수 없다.

하위클래스를 만들어 인스턴스화 하면 똑딱~
[심지어 추상클래스니까 상속해서 쓰는거라고 착각할 수도 있다](#아이템-19-상속을-고려해-설계하고-문서화하라-그러지-않았다면-상속을-금지하라)

### `인스턴스화를 막는 방법!`  
컴파일러가 기본생성자를 만드는 경우 -> 명시된 생성자가 없을 경우이다.  
기본 생성자를 만드는 경우를 없애야하기 때문에 `private 생성자`를 추가하면 **클래스의 인스턴스화를 막을수있다.**
``` java
public class UtilityClass {
    // private 생성자를 만들어서 컴파일러단에서 자동으로 기본 생성자가 만들어지는것을 막으며,
    // 외부에서 인스턴스화도 못하게 막는다.
    private UtilityClass(){ //생성자가 존재하지만 호출할수없다는것을 주석으로 달아두자
        throw new AssertionError();
    }
}
```
*  `인스턴스화 할 수 없음`  
명시적 생성자가 `private` 이기 때문에 클래스 바깥에서 접근할 수 없음 -> 외부에서 new 불가능  
*어떤 환경에도 클래스가 인스턴스화 되는 것을 무조건 막아줌*  
* `상속이 불가능 하다`  
  모든 생성자는 명시적이든, 묵시적이든 **상위클래스의 생성자를 호출하게 된다.**  
  -> `private`로 선언하게 되니 하위 클래스가 상위 클래스 생성자에 접근할 수 없음 = 상속 불가
  




    

 


---
## 아이템 5. 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라
 많은 클래스가 하나 이상의 자원에 의존한다.
 > 정적 유틸리티 클래스를 잘못 사용한 예 - 유연하지 않고 테스트하기 어렵다.
``` java
public class SpellChecker {
    private static final Lexicon dictionary = ...;

    // 인스턴스화 방지 
    private SpellChecker() { ... }

    public static boolean isValid(String word) { ... }
    public static List<String> suggestions(String typo){ ... }
}
```

위 클래스는 **맞춤법 검사기** 이며 해당 클래스는 사전에 의존한다.   
-> [정적 유틸리티 클래스](#아이템-4-인스턴스화를-막으려거든-private-생성자를-사용하라) 구현한것 (모든 요소가 다 정적(static)) 

> 싱글턴을 잘못 사용한 예 - 유연하지 않고 테스트하기 어렵다.
``` java
public class SpellChecker {
    private final Lexicon dictionary = ...;


}

```

---
참고
## `Final`
### `final변수` : 여러 컨텍스트에서 단 한번만 할당될 수 있는 entity를 정의할때 사용
1. 원시타입  
로컬 원시 변수에 final로 선언하면 한번 초기화된 변수 `변경할 수 없는 상수값`이 된다.   
``` java
public void test_final_primitive_variables(){
    final int x = 1;
    // x = 4; -> 변경 불가 , 한번 초기화 되었기때문에 변경 불가능
}
```
2. 객체 타입  
객체 변수에 final로 선언하면 그 변수에 다른 참조값을 지정할 수 없다. 한번 쓰여진 변수는 재 변경 불가능  
**단, 객체자체가 [ ](*불변( )*-이란?)하다는 의미가 아님!** -> 객체의 속성은 변경이 가능하다.
``` java
public void test_final_reference_variables(){
    final Pet pet = new Pet();
    // pet = new Pet(); // 다른 객체로 변경할수 없음
    
    pet.setAge(3); // 동일한 객체의 필드는 변경할수 있음
}
```

3. 메서드 인자  
메서드 인자에 final 키워드를 붙이면 메서드 안에서  
``` java
public class Pet {
    int age;
    public void setAge(final int age){
        age = age;
        // age = 1; // final 인자는 메서드 안에서 변경할 수 없음
    }
}
```
4. 멤버 변수  
클래스의 멤버 변수에 final로 선언하면 상수값이 되거나, write-once 필드로 한번만 쓰이게 된다.  
final로 선언 하면 초기화 되는 시점은 생성자 메서드가 끝나기 전에 초기화 된다.                       
단 `static` 유무에 따라 초기화 시점이 달라진다.  

    | 초기화 시점 | static final int x = 1 |static int x = 1|
    | ------ | ----------- |----------- |
    | ------ | 값과 함께 선언시 | 값과 함께 선언시 |
    | ------ | 정적 초기화 블록에서 (static initialization block) | 인스턴스 초기화 블록에서 (instance initialization block) | 
    | ------ |  |생성자 메서드에서 | 
    * 정적 초기화 블록 : 클래스 로드시 한번 블록 실행 
    * 인스턴스 초기화 블록  
      * 객체 생성할때마다 블록 실행
      * 부모 생성자 이후에 실행
      * 생성자보다 먼저 실행
   ``` java
   public void initializeBlockTest(){
       Cat.s_value = 5; // 정적 초기화 블록 호출 된다.
       sysout("s_value: "+ Cat.s_value);

       sysout("Cat 객체 생성1");
       Cat cat1 = new Cat();

       sysout("Cat 객체 생성2");
       Cat cat2 = new Cat();
       
   }

    public class Pet {
        public Pet(){
            sysout("super constructor: Pet");
        }
    }

    public class Cat extends Pet {
       final int i_value;
       static int s_value;

        // 인스턴스 초기화 블록
       {    
           sysout("인스턴스 초기화");
           i_value = 3;
           sysout("i_value: "+ i_value);
           sysout("s_value: "+ s_value);
       }

       // 정적 초기화 블록
       static {
           sysout("정적 초기화");
           s_value = 10;
           // sysout("i_value: "+ i_value); //static 블록에서 non-static 필드 접근 안된다.
           sysout("s_value: "+ s_value);
       }

       public Cat(){
           sysout("Constructor : Cat")
       }
   }
   ``` 
    1. static 블록이 가장 먼저 `딱 한번!` 호출되며 Cat을 new하지 않아도, 미리 s_value 접근이 가능하며 수정할수있고, cat을 new해도 후에 세팅한 s_value = 5 값이 new해도 유지된다.
    2. Cat 생성후 부모인 Pet 생성자 실행 이후에 Cat의 인스턴스 초기화 블록이 실행되고, 그 이후에 Cat의 생성자가 호출된다.  
    3. i_value는 `final`이기 때문에 인스턴스 초기화 블록에서 한번 초기화를 한상태면 다른곳에서 값이 절대로 변경될수없다.
    ```
    결과:
    static initializer block
    s_value: 10
    initializeBlockTest - s_value: 5

    Cat 객체 생성1
    super construtor : Pet
    instance initializer block
    i_value: 3
    s_value: 5
    contructor: Cat

    Cat 객체 생성2
    super construtor : Pet
    instance initializer block
    i_value: 3
    s_value: 5
    contructor: Cat
    ```

### `final 메서드` : 메서드를 final로 선언하면 상속받은 클래스에서 오버라이드가 불가능함. 
구현한 코드의 변경을 원하지 않을때 사용 (side-effect 가 존재하면 안되는 자바 코어 라이브러리에서 자주 선언)
``` java
public class Pet {
    public final void makeSound(){
        sysout("짖어봐");
    }
}

public class Dog extends Pet {
    // makeSound() final이기때문에 override 불가능!
    // public void makeSound(){
    //     sysout("멍멍");
    // }
}
```

### `final 클래스` :  클래스에 final을 선언하면 상속 자체가 되지않는다. 그냥 클래스 그대로 사용해야한다.  
즉, 절대 변경되지않는 상수들을 모아놓는 용도나 Util 형식의 클래스로 사용함.
``` java
public final class Pet { ... }

// Pet 클래스가 final로 선언되어있기때문에 상속이 불가능하다.
public class Dog extends Pet { ... }
```
1. 상수 클래스
``` java
public final Class Constants {
    public static final int SIZE = 10; // 딱 한개,  한번 10으로 세팅
}

// 상수값을 모아두는 Constants 클래스를 굳이 .. 상속? ㄴㄴ
public class SubConstants extends Constants {

}
```
2. Util 형식의 클래스  
자바 코어 라이브러리인 `String 클래스`임. 해당 클래스를 상속해서 override해버리면 아주 큰일납니다~ 그래서 `final`로 수정을 아예 막아놓았다.  
``` java
public final class String implements java.io.Serializable, Comparable<String>, CharSequence {
    ...
}
``` 

## `Static` 
메모리에 한번 할당 되어 프로그램이 종료될때 해제되는것

일반적으로 만드는 `class`는 `static 영역`에 생성, `new 연산`을 통해 생성한 객체는 `Heap 영역`에 생성된다.
 * `Heap 영역`의 메모리는 가비지 컬렉터(**Garbege Collector**) 를 통해 수시로 관리 받는다.

1. `Static 영역` 
   * 일반적으로 생성하는 class
   * 모든 객체가 공유하는 메모리 
   * 메모리가 계속 할당되므로 퍼포먼스 영향
2. `Heap 영역`
   * new 연산으로 생성 
   * 가비지 컬렉터(**Garbege Collector**) 를 통해 수시로 관리 받는다.

### `Static 변수`  : 클래스 변수이다. 객체를 생성하지 않고 접근이 가능하다.
``` java
public class MyCalculator {
    public static String appName = "MyCalculator";

    public static int add(int x, int y){
        return x + y;
    }
    
    public int min(int x, int y){
        return x - y;
    }
}

// static 메소드이기때문에 객체 생성전에도 호출이 가능함 
MyCalculator.add(4,6); // O
// non-static 메소드이기 때문에 객체 생성 전에는 메서드가 정의되어 있지 않기때문에 호출이 불가능함 
MyCalculator.min(4,2); // X

MyCalculator cal = new MyCalculator();
// 가능은 하지만, 이렇게 쓰는건은 static 메소드로 만든 의미가 없음. 권장하지 않음
cal.add(4,6); // O 
cal.min(4,2); // O
``` 

``` java
public class Person {
    private String name = "SH";

    public void printName(){
        sysout("이름은: "+ this.name);
    }    
}
```
Person 클래스를 100번 new를 통해 생성을 하게 되면, 
"SH"라는 값을 가지는 name이 메모리에 100개가 쌓이게 된다.  
-> 이런 경우에는 `static`을 통해 여러 객체가 하나의 *name*을 참조하게 한다!  
-> `static`값은 보통 `상수`의 값을 갖는 경우가 많아서 `public`으로 선언하고, 또한 변경되지않는 부분이 대다수라 `final`을 함께 사용한다.  
-> *public static final*

## 아이템 6. 불필요한 객체 생성을 피하라
## 아이템 7. 다 쓴 객체 참조를 해제하라
## 아이템 8. finalizer와 cleaner 사용을 피하라
## 아이템 9. try-finally보다는 try-with-resources를 사용하라
----  

# 3장 모든 객체의 공통 메서드
## 아이템 10. equals는 일반 규약을 지켜 재정의하라
## 아이템 11. equals를 재정의하려거든 hashCode도 재정의하라
## 아이템 12. toString을 항상 재정의하라
## 아이템 13. clone 재정의는 주의해서 진행하라
## 아이템 14. Comparable을 구현할지 고려하라
----
# 4장 클래스와 인터페이스
## 아이템 15. 클래스와 멤버의 접근 권한을 최소화하라
## 아이템 16. public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라
## 아이템 17. 변경 가능성을 최소화하라
## 아이템 18. 상속보다는 컴포지션을 사용하라
## 아이템 19. 상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라
## 아이템 20. 추상 클래스보다는 인터페이스를 우선하라
## 아이템 21. 인터페이스는 구현하는 쪽을 생각해 설계하라
## 아이템 22. 인터페이스는 타입을 정의하는 용도로만 사용하라
## 아이템 23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라
## 아이템 24. 멤버 클래스는 되도록 static으로 만들라
## 아이템 25. 톱레벨 클래스는 한 파일에 하나만 담으라
----
# 5장 제네릭
## 아이템 26. 로 타입은 사용하지 말라
## 아이템 27. 비검사 경고를 제거하라
## 아이템 28. 배열보다는 리스트를 사용하라
## 아이템 29. 이왕이면 제네릭 타입으로 만들라
## 아이템 30. 이왕이면 제네릭 메서드로 만들라
## 아이템 31. 한정적 와일드카드를 사용해 API 유연성을 높이라
## 아이템 32. 제네릭과 가변인수를 함께 쓸 때는 신중하라
## 아이템 33. 타입 안전 이종 컨테이너를 고려하라
---- 
# 6장 열거 타입과 애너테이션
## 아이템 34. int 상수 대신 열거 타입을 사용하라
## 아이템 35. ordinal 메서드 대신 인스턴스 필드를 사용하라
## 아이템 36. 비트 필드 대신 EnumSet을 사용하라
## 아이템 37. ordinal 인덱싱 대신 EnumMap을 사용하라
## 아이템 38. 확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라
## 아이템 39. 명명 패턴보다 애너테이션을 사용하라
## 아이템 40. @Override 애너테이션을 일관되게 사용하라
## 아이템 41. 정의하려는 것이 타입이라면 마커 인터페이스를 사용하라
---- 
# 7장 람다와 스트림
## 아이템 42. 익명 클래스보다는 람다를 사용하라
## 아이템 43. 람다보다는 메서드 참조를 사용하라
## 아이템 44. 표준 함수형 인터페이스를 사용하라
## 아이템 45. 스트림은 주의해서 사용하라
## 아이템 46. 스트림에서는 부작용 없는 함수를 사용하라
## 아이템 47. 반환 타입으로는 스트림보다 컬렉션이 낫다
## 아이템 48. 스트림 병렬화는 주의해서 적용하라
---- 
# 8장 메서드
## 아이템 49. 매개변수가 유효한지 검사하라
## 아이템 50. 적시에 방어적 복사본을 만들라
## 아이템 51. 메서드 시그니처를 신중히 설계하라
## 아이템 52. 다중정의는 신중히 사용하라
## 아이템 53. 가변인수는 신중히 사용하라
## 아이템 54. null이 아닌, 빈 컬렉션이나 배열을 반환하라
## 아이템 55. 옵셔널 반환은 신중히 하라
## 아이템 56. 공개된 API 요소에는 항상 문서화 주석을 작성하라
---- 
# 9장 일반적인 프로그래밍 원칙
## 아이템 57. 지역변수의 범위를 최소화하라
## 아이템 58. 전통적인 for 문보다는 for-each 문을 사용하라
## 아이템 59. 라이브러리를 익히고 사용하라
## 아이템 60. 정확한 답이 필요하다면 float와 double은 피하라
## 아이템 61. 박싱된 기본 타입보다는 기본 타입을 사용하라
## 아이템 62. 다른 타입이 적절하다면 문자열 사용을 피하라
## 아이템 63. 문자열 연결은 느리니 주의하라
## 아이템 64. 객체는 인터페이스를 사용해 참조하라
## 아이템 65. 리플렉션보다는 인터페이스를 사용하라
## 아이템 66. 네이티브 메서드는 신중히 사용하라
## 아이템 67. 최적화는 신중히 하라
## 아이템 68. 일반적으로 통용되는 명명 규칙을 따르라
---- 
# 10장 예외
## 아이템 69. 예외는 진짜 예외 상황에만 사용하라
## 아이템 70. 복구할 수 있는 상황에는 검사 예외를, 프로그래밍 오류에는 런타임 예외를 사용하라
## 아이템 71. 필요 없는 검사 예외 사용은 피하라
## 아이템 72. 표준 예외를 사용하라
## 아이템 73. 추상화 수준에 맞는 예외를 던지라
## 아이템 74. 메서드가 던지는 모든 예외를 문서화하라
## 아이템 75. 예외의 상세 메시지에 실패 관련 정보를 담으라
## 아이템 76. 가능한 한 실패 원자적으로 만들라
## 아이템 77. 예외를 무시하지 말라
---- 
# 11장 동시성
## 아이템 78. 공유 중인 가변 데이터는 동기화해 사용하라
## 아이템 79. 과도한 동기화는 피하라
## 아이템 80. 스레드보다는 실행자, 태스크, 스트림을 애용하라
## 아이템 81. wait와 notify보다는 동시성 유틸리티를 애용하라
## 아이템 82. 스레드 안전성 수준을 문서화하라
## 아이템 83. 지연 초기화는 신중히 사용하라
## 아이템 84. 프로그램의 동작을 스레드 스케줄러에 기대지 말라
----
# 12장 직렬화
## 아이템 85. 자바 직렬화의 대안을 찾으라
## 아이템 86. Serializable을 구현할지는 신중히 결정하라
## 아이템 87. 커스텀 직렬화 형태를 고려해보라
## 아이템 88. readObject 메서드는 방어적으로 작성하라
## 아이템 89. 인스턴스 수를 통제해야 한다면 readResolve보다는 열거 타입을 사용하라
## 아이템 90. 직렬화된 인스턴스 대신 직렬화 프록시 사용을 검토하라


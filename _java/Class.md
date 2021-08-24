## 초기화 블럭(Initialization Block)
```java
class Main{
    static{ /*클래스 초기화 블럭*/ }
    { /*인스턴스 초기화 블럭*/ }
}
```
### 1. 클래스 초기화 블럭
* 클래스 변수의 초기화
* 클래스가 처음 호출될 때, 1번 수행
### 2. 인스턴스 초기화 블럭
* 인스턴스 변수의 초기화
* 인스턴스 생성시 수행, 생성자보다 먼저 수행
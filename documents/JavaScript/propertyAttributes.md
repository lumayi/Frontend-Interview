# 프로퍼티 어트리뷰트

## 내부 슬롯과 내부 메서드

- 모든 객체는 [[Prototype]]이라는 내부 슬롯을 갖는다. 개발자가 직접 접근할 수 있도록 외부로 공개된 객체의 프로퍼티가 아니지만, **proto**를 통해 간접적으로 접근할 수 있다.

## 데이터 프로퍼티(Data Property)

자바스크립트 엔진은 프로퍼티를 생성할 때, 해당 4개의 값을 자동의로 정의한다.

1. [[Value]]
2. [[Writable]]
3. [[Enumerable]]
4. [[Configurable]]

해당 Attribute에 직접 접근할 수 는 없지만, Object.getOwnPropertyDescriptor()를 사용해 간접적으로 확인할 수 있다.

## 접근자 프로퍼티(Access Property)

1. [[Get]]
2. [[Set]]
3. [[Enumerable]]
4. [[Configurable]]

## 객체 변경 방지 3가지

1. preventExtensions()
2. seal()
3. freeze()

```javascript
Quiz.
[1] 프로퍼티와 애트리뷰트를 직접 정의하기 위해서 쓸 수 있는 메서드는?
[2] Configurable이 false인 경우, 제한되는 것은?
[3] Object.seal() 메서드는 애트리뷰트 재정의가 가능하다. (O/X)
```

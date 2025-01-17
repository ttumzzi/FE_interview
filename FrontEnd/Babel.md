# FrontEnd - Babel

## 설명

바벨이란 ES2015+ 코드를 적당한 하위 버전의 코드로 변환시켜주는 자바스크립트 트랜스파일러입니다.

### 1. Babel 컴파일러일까? 트랜스파일러일까?

#### 1-1. 컴파일

ex) java ⇒ bytecode, c ⇒ assembly

컴파일은 한 언어로 작성됨 소스 코드를 다른 언어로 변환하는 것을 의미 합니다.


### 2. 트랜스파일

ex) c++ ⇒ c, coffescript ⇒ javascript

- 트렌스파일은 한 언어로 작성된 소스 코드를 유사한 추상화 수준을 가진 다른 언어로 변환하는 것을 의미 합니다.  
- 어떤 특정 언어로 작성된 소스 코드를 다른 소스 코드로 변환하는 것입니다.
- 바벨 공식문서에서 '바벨은 자바스크립트 컴파일러입니다.' 소개합니다.
- 정확하게 보면 바벨은 소스 대 소스 컴파일러로 트랜스파일러라 볼수있지만 트랜스파일은 특정 종류의 컴파일이기 때문에 공식문서에서 컴파일러라고 소개하는 것은 문제가 되지 않는다고 생각합니다.

### 3. 바벨을 사용하는 이유

- 브라우저마다 사용하는 언어가 달라서 프론트에서 짠 코드를 이해하지 못하는 브라우저가 존재할 수도 있습니다.
- 바벨은 ES2015+로 작성한 코드들을 모든 브라우저에서 동작하도록 해주기 때문에 이러한 크로스 브라우징 이슈를 해결해 줄 수 있습니다.

## 요약

- 바벨은 ES2015 상위 버전 코드를 하위 버전의 코드로 변환시켜주는 자바스크립트 트랜스파일러입니다.
- React 에서는 JSX코드를 createElement 함수를 이용해 변환시켜 준다.
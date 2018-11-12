# Image Slider

### 교육 목표
이미지 슬라이더를 이용해서 단계별로 리팩토링을 거쳐 MVC + Observer를 익힌다.

### 교육 설명
1. dot 페이지네이션으로 이미지 위치 표시
2. 3초마다 오토슬라이드
3. 화살표를 이용해서 다음/이전 장으로 넘기기 가능
4. dot 페이지네이션으로 해당 위치 이미지로 넘기기 가능

---
## step 1
Native ES5로 function - prototype을 사용하지 않고 일반 함수로만 개발

### DOMParser

### call

### setInterval, setTimeout

---
## step 2
생성자 함수 1개 - prototype 1개로 리팩토링

### this

### prototype, \_\_proto__

### constructor

### bind

---
## step 3
기능 단위로 분리해서 생성자 함수 3개 - prototype 3개(MVC)로 리팩토링

### 디자인패턴: MVC, MVP, MVVM

###

---
## step 4
Model과 View를 더 작은 단위로 분리 및 상속을 사용해서 리팩토링

### 상속: call, Object.create()

### 

## step 5
모듈간의 의존성 문제가 생기면 콜백 함수를 사용해서 리팩토링

---
## step 6
옵저버 패턴을 적용해서 콜백 함수 대신 옵저버 모듈을 상속해서 리팩토링

### observer

### callback

---
## step 7
jquery를 사용해서 객체 간의 custom event를 발생하도록 리팩토링

### jquery custom event

---
## step 8
ES6를 사용해서 문법 리팩토링

### arrow function vs funciton

### babel

### webpack - es6 setting

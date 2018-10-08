# 1급 객체

1. 변수에 담을 수 있다.
2. 인자로 전달할 수 있다.
3. 반환값으로 전달할 수 있다.

위의 세가지 조건을 만족하면 1급 객체라고 한다.

## 일반 함수
```js
function sayHello(to) {
    console.log("Hello, " + to + ".");
}
sayHello("John");
// Hello, John.
```

## 1급 함수
```js
var sayHello = function(to) {
    console.log("Hello, " + to + ".");
}

sayHello("John");
// Hello, John.
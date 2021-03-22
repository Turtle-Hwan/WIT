week 01 react 01
===

Fetch 사용해서 html 문서 만들기
---

- [https://jsonplaceholder.typicode.com/posts/](https://jsonplaceholder.typicode.com/posts/) 를 fetch해서 `userId`가 1인 post만 body 내에 작성
- 비동기적으로 fetch하기

```jsx
fetch('https://jsonplaceholder.typicode.com/posts/')
  .then((response) => response.json())
  .then((json) => 으쌰으쌰);
```
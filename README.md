# React 상태관리 비교 Redux편

이전에 Redux를 이용해서 Todo list 등 미니 프로젝트에 사용해본 적이 있었다.
그때는 여러 블로그를 통해 배워가며 사용했었는데, 이번에는 [공식문서](https://ko.redux.js.org/)에 나와 있는 가이드대로 해볼 것이다.
<br/>

### Redux 시작하기

RTK(Redux Toolkit)을 추천한다고 적혀있다, 이전에는 Redux만 써봤는데 한 번 설치해보자

```node
# NPM
npm install @reduxjs/toolkit

# Yarn
yarn add @reduxjs/toolkit
```

<br/>

### Redux Toolkit은 무얼 하나요?

이전에 작성했던 액션 생성자와 액션 타입을 자동으로 생성하고 리듀서 코드가 더 짧고 이해하기 쉬어진다고 적혀있다.
이전 기억을 떠올려보면 액션들을 만들 때 마다 해당하는 타입도 만들어 줬어야 되고, 그것들을 switch문과 함께 합친 리듀서라는 것들도 만들어 주고 매우 반복적인 작업에 귀찮아했었던 거 같다.

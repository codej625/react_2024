# vite를 사용해서 프로젝트를 생성해보자.

<br />

```
CRA(create-react-app)는 자바스크립트 코드로 구성된 툴인 Webpack을 사용한다.
자바스크립트는 기본적으로 interpreted 언어이기 때문에 느리다.
코드의 양이 적다면 차이를 느끼기 어렵지만, 처리해야할 코드의 양이 방대해질 경우에는 그 단점이 확연히 드러난다. 

위와 같은 단점을 해결하기 위해
Go와 같은 저급언어(low-level language)를 활용해서 자바스크립트 툴을 개발하여
Esbuild를 기반으로 만들어진 빌드툴인 Vite를 사용하게 됬다.
```

<br />

1. 설치할 폴더를 만들고 밑에 스크립트를 사용하여 vite를 설치한다.
```
npm create vite@latest

or 

yarn create vite

or

pnpm create vite
```

<br />

2. 어떤 프로젝트를 만들지 선택한다.
```
vanilla, vanilla-ts,
vue, vue-ts,
react, react-ts,
preact, preact-ts,
lit, lit-ts,
svelte, svelte-ts
```

<br />

3. vite가 설치된 폴더로 이동하여 Node.js 프로젝트에 필요한 종속성을 설치한다.
```
cd vite-project

npm install

npm run dev
```
```
기본 포트는 3000이 아닌 5173이다.
```

### 1. new project with Vite, querySelectorAll, NodeList

- Vite 웹사이트 → **StackBlitz** 로 설치 안하고 로컬에서 바로 써볼 수 있음
- `yarn create vite` 로 프로젝트 생성.
- main.js 에서 내용 수정하면 수정한대로 프로젝트에 반영될거임
- className을 지정: className에 스트링을 할당할수도 있지만 h1.classList.add(’~~’) 로 여러개의 클래스네임 객체를 활용할 수 있음
- 자바스크립트는 언어. 이걸 사용하는 환경은 다양할 수 있음  
예) 터미널에서 node 를 사용하는건 nodejs 사용하는 것. 브라우저에서는 자바스크립트로 쓸 수 있는 몇몇 api 를 제공한다. 비슷하게 터미널에서는 node 가 제공하는 node의 api가 있다.   
예) document → 브라우저 api / require(’path’) 이 모듈은 nodejs에서 제공.
- insertBefore라는 api 사용하는 예제
- `document.querySelectorAll(”p”)` 를 콘솔로 찍어보면 **NodeList**를 반환한다. 이건 배열은 아니기 때문에 배열처럼 사용하려면 Array.from() 써야함
<img width="572" alt="111111" src="https://github.com/yellyB/sinabro-javascript/assets/50893303/0ec95a26-6321-457d-8a84-61b7b43c5006">


<br/><br/><br/>

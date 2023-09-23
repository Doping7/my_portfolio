# my_portfolio

## stack

yarn의 workspace기능을 활용한 ModoRepo로 구성.

- 추가적인 포트폴리오 요소가 나올 때마다 새로운 MicroService
로 구성하여 개발할 예정입니다.

React와 Next.js를 활용하여 프로젝트를 구성.

- React, next는 변하지 않으나 상태관리 라이브러리는 MicroService
마다 변경해가며 다양하게 사용할 예정.

## APP
Side Project들을 모두 취합하여 Routing을 통해 한 Web App에서 보여줄 수 있도록 구성할 Package입니다. 

- Next.js 13 이상으로 App Routing을 사용할 예정입니다.

- Landing Page의 경우 SSR를 활용할 수 있도록 할 예정.

## MicroService
실제 테마별 Project를 가지고 있을 Package입니다. 

- Project가 추가될 때마다 Package는 이 곳에 추가 됩니다.

- 따로 APP의 형태로 구성하지 않고 React 및 상태관리 Lib를 활용한 Component Lib의 형태로 구성할 예정입니다.

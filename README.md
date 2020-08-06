### Webpack4+를 이용한 Single File Component 프로덕션 모드 배포 방법(without Vue CLI)

https://blog.naver.com/mgveg/222031881408

### Vue CLI에서 프로덕션 모드 체킹

Vue CLI에선 기본적으로 모드 설정이 되어 있고, 3개의 모드가 있다.

>>>+ development
>>>+ production
>>>+ text

환경 변수들은 process.env에 정의되어 있다. (환경 변수: 실행 모드에 따라 선택되는 변수.)

기본적으로 2개의 환경변수 NODE_ENV, BASE_URL가 있다. 

>>>+ NODE_ENV: 앱이 실행되는 모드. 3개의 기본 모드 "development", "production", "test"가 있다.
>>>+ BASE_URL: vue.config.js의 publicPath 옵션에 해당하고 앱이 배포되는 기본 경로

그리고 루트 디렉토리에 ".env.local" 파일을 만들어, 사용자가 정의한 변수를 추가할 수 있습니다.

### Vue Router

https://blog.naver.com/mgveg/221920917734

### Vuex

https://blog.naver.com/mgveg/222052235513

-----

### Vue에서 컴포넌트 템플릿을 정의하는 7가지 방법

<https://github.com/FEDevelopers/tech.description/wiki/Vue%EC%97%90%EC%84%9C-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-%ED%85%9C%ED%94%8C%EB%A6%BF%EC%9D%84-%EC%A0%95%EC%9D%98%ED%95%98%EB%8A%94-7%EA%B0%80%EC%A7%80-%EB%B0%A9%EB%B2%95>

### Editor

<https://codesandbox.io/>

<https://codepen.io/>

### 테스트 코드가 필요한 이유
https://joshua1988.github.io/vue-camp/testing/overview.html

### Vue/CLI unit-jest 설치 방법
https://cli.vuejs.org/core-plugins/unit-jest.html#injected-commands

https://joshua1988.github.io/vue-camp/testing/vue-test-util.html

### Jest 소개
https://joshua1988.github.io/vue-camp/testing/jest-testing.html#jest-%EC%86%8C%EA%B0%9C

# webpack-pug-sass

Vue.js v2.0 앱 프로토타이핑 제작을 위한 Webpack & `vue-loader` 프로젝트 템플릿.

### 사용법

[vue-cli(한국어 번역)](https://github.com/vuejs-kr/vue-cli)를 사용한 템플릿.

``` bash
# 글로벌 vue-cli 개발 모듈 설치
$ npm install -g vue-cli
# vue-cli 프로젝트 템플릿 초기화
$ vue init yamoo9/webpack-pug-sass my-project
$ cd my-project
$ npm install
$ npm run dev
```

### 명령어 목록

- `npm run dev`: 핫-리로드(hot-reload)를 지원하는 Webpack + `vue-loader` 개발용 명령.
- `npm run build`: HTML/CSS/JS 압축 빌드, 배포용 명령.
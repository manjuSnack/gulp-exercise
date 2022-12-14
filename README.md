# Gulp Exercise

Gulp에 대한 개발자 환경을 설정하는 방법의 학습한 내용을 기술하였습니다.
😰

# 설치

```BASH
$ cd ~
$ mkdir gulp
$ cd gulp
$ mkdir src/img src/js src/patials src/scss src/templates
$ touch index.pug .babelrc .gitignore gulpfile.babel.js
$ cd src
$ touch js/main.js js/util.js partials/header.pug partials/footer.pug scss/style.scss scss/_reset.scss scss/_variable.scss templates/layout.pug
$ npm init
```

Package.json 생성 후

```BASH
$ npm i gulp @babel/{register,core,preset-env} gulp-pug del@4.1.1 gulp-webserver gulp-image@6.2.1 sass gulp-sass node-sass@6.0 gulp-autoprefixer gulp-csso gulp-bro babelify uglifyify gulp-gh-pages

```

# 설명

<!-- Table -->

| API              | 설명                                                                                            |
| ---------------- | ----------------------------------------------------------------------------------------------- |
| gulp             | Gulp에 대한 개발자에 도움이 되는 환경설정을 위한 API                                            |
| gulp-pug         | Compile 과정 중 .pug를 .html로 확장자 변경하여 저장하기 위한 API                                |
| del              | Compile 과정 중 기존에 파일들이 저장된 dest와 .publish 폴더 혹 파일 삭제하기 위한 API           |
| gulp-webserver   | 개발용 서버를 https://localhost:포트번호 로 이용하기 위한 API                                   |
| gulp-image       | Compile 과정 중 PNG, JPG, GIF, SVG 확장자인 이미지의 용량을 압축해 최적화하여 저장하기 위한 API |
| gulp-sass        | Compile 과정 중 .scss를 .css로 확장자를 변경하여 저장하기 위한 API                              |
| sass             | node.js에서 sass 라이브러리 이용하기 위한 API                                                   |
| gulp-autorefixer | 오래된 브라우저와의 호환 등을 이용하기 위한 API                                                 |
| gulp-csso        | Compile 과정 중 .scss에서 .css로 저장될 css 파일의 용량을 최소화하여 압축하기 위한 API          |
| gulp-bro         | Compile 과정 중 javascript 파일을 저장하며 파일의 용량을 최소화하여 압축하기 위한 API           |
| babelify         | Compile 과정 중 babel의 기능으로 작성된 확장자가 .js인 파일을 Vanilla js로 변경하기 위한 API    |
| gulp-gh-pages    | Github에 해당 프로젝트의 Homepage를 개설해 배포하는 기능을 가진 API                             |

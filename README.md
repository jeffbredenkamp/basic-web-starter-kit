# basic-web-starter-kit
A simple gulp web starter kit.

## Getting Started

### Installation and usage

1. git clone https://github.com/jeffbredenkamp/basic-web-starter-kit.git
2. Install NPM packages
```
npm install
```

* NPM modules - npm install (install all plugins)
* Gulp build task - gulp (run all tasks)
* Gulp Sass task - gulp prod-build (run Sass task)
* Gulp script task - gulp minifyjs (run script task)
* Gulp image task - gulp minifyimg (run image task)

## Gulp Plugins

* gulp
* gulp-dart-sass
* gulp-imagemin
* gulp-rename
* gulp-sourcemaps
* gulp-uglify

## File Structure

```
Content-Visual-Language
│   gulpfile.js
│   index.html
│   package-lock.json
│   package.json
│   README.md 
│
└───dist
│   │
│   └───css
│   │
│   └───img
│   │
│   └───js
│   
└───src
│   │
│   └───img
│   │
│   └───js
│   │   main.js
│   │
│   └───scss
│   │   main.scss
```
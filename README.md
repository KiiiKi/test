# good_list

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

### 试一下vue-cli的打包、发布、预览
1. 改\config\index.js的build。assetsPublicPath为"./"
2. cmd进文件夹，npm run build打包
3. 改文件夹下的.gitignore，删掉dist一行
4. github desktop导入
5. 库的setting里，在github pages的sourse处选择master branch
3.打开https://kiiiki.github.io/test/dist 也就是 https://用户名.github.io/仓库名/dist

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

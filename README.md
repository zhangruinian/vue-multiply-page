# woyou

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
```
* [多页设置参考](https://www.jianshu.com/p/0a30aca71b16)
* pages文件夹下面 新建页面之后要重新npm run start
* pages文件夹下 index为例 index.html和index.js文件要同名
* build 下配置修改 assetsPublicPath: './',
* 页面跳转直接 <a href="index.html">跳转html</a> 自动寻找相应的html文件

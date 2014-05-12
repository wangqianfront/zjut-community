# zjut-community [![Build Status](https://secure.travis-ci.org/wangqianfront/nodeclub.png?branch=master)](http://travis-ci.org/cnodejs/nodeclub) [![依赖模块状态](https://david-dm.org/cnodejs/nodeclub.png)](http://david-dm.org/cnodejs/nodeclub)

基于nodejs的zjut-community社区系统

## 介绍

ZJUT Community ZJUT Community 是一个用nodejs开发的开源技术社区。。

## 安装部署

```bash
// install node npm mongodb
// run mongod
$ npm install
$ cp config.default.js config.js
// modify the config file as yours
$ node app.js
```

热部署
```bash
$ npm install forever -g
```
```
$ forever start -w app.js
```

## TEST

```bash
$ make test
```

jscoverage

```bash
$ make test-cov
```

* jscoverage: [**31%**](http://fengmk2.github.com/coverage/nodeclub.html)

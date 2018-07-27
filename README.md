# egg-qiniu-upload

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/mj-egg-qiniu.svg?style=flat-square
[npm-url]: https://npmjs.org/package/mj-egg-qiniu
[travis-image]: https://img.shields.io/travis/eggjs/mj-egg-qiniu.svg?style=flat-square
[travis-url]: https://travis-ci.org/eggjs/mj-egg-qiniu
[codecov-image]: https://img.shields.io/codecov/c/github/eggjs/mj-egg-qiniu.svg?style=flat-square
[codecov-url]: https://codecov.io/github/eggjs/mj-egg-qiniu?branch=master
[david-image]: https://img.shields.io/david/eggjs/mj-egg-qiniu.svg?style=flat-square
[david-url]: https://david-dm.org/eggjs/mj-egg-qiniu
[snyk-image]: https://snyk.io/test/npm/mj-egg-qiniu/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/mj-egg-qiniu
[download-image]: https://img.shields.io/npm/dm/mj-egg-qiniu.svg?style=flat-square
[download-url]: https://npmjs.org/package/mj-egg-qiniu

<!--
Description here.
-->
## 说明
取自egg-qiniu-upload，因无法自定义上传文件名称，所以自己微调以后传了一个
## 依赖说明

### 依赖的 egg 版本

egg-qiniu-upload 版本 | egg 1.x
--- | ---
1.x | 😁
0.x | ❌

### 依赖的插件
<!--

如果有依赖其它插件，请在这里特别说明。如

- security
- multipart

-->

## 开启插件

```js
// config/plugin.js
exports.qiniuUpload = {
  enable: true,
  package: 'egg-qiniu-upload',
};
```

## 使用场景

- Why and What: 描述为什么会有这个插件，它主要在完成一件什么事情。
尽可能描述详细。
- How: 描述这个插件是怎样使用的，具体的示例代码，甚至提供一个完整的示例，并给出链接。

## 详细配置

请到 [config/config.default.js](config/config.default.js) 查看详细配置项说明。

## 单元测试

<!-- 描述如何在单元测试中使用此插件，例如 schedule 如何触发。无则省略。-->

## 提问交流

请到 [egg issues](https://github.com/eggjs/egg/issues) 异步交流。

## License

[MIT](LICENSE)

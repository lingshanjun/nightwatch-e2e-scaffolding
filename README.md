# nightwatch-e2e-scaffolding
使用nightwatch.js搭建前端e2e自动化测试脚手架


## 说明

### 运行测试
```
npm run e2e
```
默认会启动`chrome`浏览器测试。

如要启动其他的浏览器进行测试，则需传入参数，如下所以
```
npm run e2e -- firefox
```

## TODO

1. `npm run e2e` 传参配置更加灵活性 修改`nightwatch.conf.js`文件

2. 兼容多浏览器情况设置

3. 更多的test用例demo
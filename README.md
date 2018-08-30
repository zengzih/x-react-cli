<p align="center"><img width="160" src="https://github.com/codexu/x-build/blob/x-build4.1/src/assets/images/logo.png?raw=true" alt="x-build"></p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.2.0-blue.svg">
</p>

<h1 align="center">x-build-cli</h1>

命令行工具：`x-build-cli`，将此项安装到本地全局环境下，可以通过指令`x-build init`快速初始化一个最新版本的`x-build`项目。

<p align="center">
  <img width="580" src="https://github.com/codexu/_images/blob/master/x-bulid/x-build-cli.gif?raw=true">
</p>

## 起步

```
  /* npm 安装 */
  npm install x-build-cli -g
```

```
  /* 初始化x-build项目 (简写为: x i) */
  x-build init
  // 输入项目名称
  // 输入初始版本
  // 输入server端口
  // 使用pug(jade)模版引擎？(Y/N)
  // 使用px2rem布局?(Y/N)
```

## 参考文档

x-build文档: [https://github.com/codexu/x-build](https://github.com/codexu/x-build)

## update

`v1.2.1` `18.07.08` : 默认端口改为'8080'

`v1.2.0` `18.06.04` : 增加是否使用pug模版引擎、是否使用rem布局选项。

`v1.1.11` `18.05.28` : 使用inquirer替换co，现在拥有更美观的输入环境。

`v1.1.10` `18.05.27` : 优化输入方式,目前可以填写项目名\版本号\端口号选项

`v1.1.9` `18.05.22` : x-build4.3.0切换到master，以后从master拉区最新的x-build。

`v1.1.8` `18.05.21` : 增加简洁命令`x`

`v1.1.7` `18.05.18` : 将依赖安装后上传至npm

`v1.1.1` `18.05.17` : 调整控制台提示信息

`v1.1.0` `18.05.17` : 正确生成功配置package.json，默认name为[项目名称]，版本号为1.0.0
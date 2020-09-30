<h1 align="center">Cocos 资料大全</h1>

**本文定期更新，欢迎提交 PR，托管在[Cocos-Resource Github](https://github.com/fusijie/Cocos-Resource)。如果下载跳转地址异常，说明原始下载包已被官方移除。**

<!--TOC BEGIN-->

- [Cocos 文档相关](#cocos-%E6%96%87%E6%A1%A3%E7%9B%B8%E5%85%B3)
  - [Cocos2d-x 中英文发布说明](#cocos2d-x-%E4%B8%AD%E8%8B%B1%E6%96%87%E5%8F%91%E5%B8%83%E8%AF%B4%E6%98%8E)
  - [Cocos2d-x 官方文档](#cocos2d-x-%E5%AE%98%E6%96%B9%E6%96%87%E6%A1%A3)
  - [Cocos2d-x API 手册](#cocos2d-x-api-%E6%89%8B%E5%86%8C)
  - [Cocos Creator 官方文档](#cocos-creator-%E5%AE%98%E6%96%B9%E6%96%87%E6%A1%A3)
  - [Cocos Creator API 手册](#cocos-creator-api-%E6%89%8B%E5%86%8C)
  - [Cocos Creator 3D 官方文档](#cocos-creator-3d-%E5%AE%98%E6%96%B9%E6%96%87%E6%A1%A3)
  - [Cocos Creator 3D API 手册](#cocos-creator-api-3d-%E6%89%8B%E5%86%8C)
- [Cocos 引擎下载](#cocos-%E5%BC%95%E6%93%8E%E4%B8%8B%E8%BD%BD)
  - [Cocos2d-x 引擎下载](#cocos2d-x-%E5%BC%95%E6%93%8E%E4%B8%8B%E8%BD%BD)
  - [Cocos2d-js 引擎下载](#cocos2d-js-%E5%BC%95%E6%93%8E%E4%B8%8B%E8%BD%BD)
  - [Cocos2d-js Lite 引擎下载](#cocos2d-js-lite-%E5%BC%95%E6%93%8E%E4%B8%8B%E8%BD%BD)
  - [Quick-cocos2d-x 引擎下载](#quick-cocos2d-x-%E5%BC%95%E6%93%8E%E4%B8%8B%E8%BD%BD)
- [Cocos Creator 下载](#cocos-creator-%E4%B8%8B%E8%BD%BD)
  - [Cocos Creator 引擎下载](#cocos-creator-%E5%BC%95%E6%93%8E%E4%B8%8B%E8%BD%BD)
  - [Cocos Creator v2 下载](#cocos-creator-v2-%E4%B8%8B%E8%BD%BD)
  - [Cocos Creator v1 下载](#cocos-creator-v1-%E4%B8%8B%E8%BD%BD)
  - [Cocos Creator 3D 下载](#cocos-creator-3d-%E4%B8%8B%E8%BD%BD)
- [Cocos 配套工具下载](#cocos-%E9%85%8D%E5%A5%97%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD)
  - [Cocos 下载](#cocos-%E4%B8%8B%E8%BD%BD)
  - [Cocos Studio 下载](#cocos-studio-%E4%B8%8B%E8%BD%BD)
  - [Cocos Framework 下载](#cocos-framework-%E4%B8%8B%E8%BD%BD)
  - [Cocos Simuator 下载](#cocos-simuator-%E4%B8%8B%E8%BD%BD)
  - [Cocos IDE 下载](#cocos-ide-%E4%B8%8B%E8%BD%BD)
- [Cocos 版本关系说明](#cocos-%E7%89%88%E6%9C%AC%E5%85%B3%E7%B3%BB%E8%AF%B4%E6%98%8E)
  - [Cocos2d-x 与 Cocos Studio 版本对应关系](#cocos2d-x-%E4%B8%8E-cocos-studio-%E7%89%88%E6%9C%AC%E5%AF%B9%E5%BA%94%E5%85%B3%E7%B3%BB)
  - [Cocos2d-x 与 NDK 版本对应关系](#cocos2d-x-%E4%B8%8E-ndk-%E7%89%88%E6%9C%AC%E5%AF%B9%E5%BA%94%E5%85%B3%E7%B3%BB)
- [Cocos Android 相关下载](#cocos-android-%E7%9B%B8%E5%85%B3%E4%B8%8B%E8%BD%BD)
  - [Android NDK 下载](#android-ndk-%E4%B8%8B%E8%BD%BD)
  - [Android Studio 下载](#android-studio-%E4%B8%8B%E8%BD%BD)
  - [Android ADT Bundle 下载](#android-adt-bundle-%E4%B8%8B%E8%BD%BD)
- [Cocos 第三方游戏工具下载](#cocos-%E7%AC%AC%E4%B8%89%E6%96%B9%E6%B8%B8%E6%88%8F%E5%B7%A5%E5%85%B7%E4%B8%8B%E8%BD%BD)
  - [Cocos Creator 插件](#cocos-creator-%E6%8F%92%E4%BB%B6)
  - [位图字体工具](#%E4%BD%8D%E5%9B%BE%E5%AD%97%E4%BD%93%E5%B7%A5%E5%85%B7)
  - [粒子编辑工具](#%E7%B2%92%E5%AD%90%E7%BC%96%E8%BE%91%E5%B7%A5%E5%85%B7)
  - [物理编辑工具](#%E7%89%A9%E7%90%86%E7%BC%96%E8%BE%91%E5%B7%A5%E5%85%B7)
  - [场景编辑工具](#%E5%9C%BA%E6%99%AF%E7%BC%96%E8%BE%91%E5%B7%A5%E5%85%B7)
  - [纹理图集工具](#%E7%BA%B9%E7%90%86%E5%9B%BE%E9%9B%86%E5%B7%A5%E5%85%B7)
  - [瓦片地图编辑工具](#%E7%93%A6%E7%89%87%E5%9C%B0%E5%9B%BE%E7%BC%96%E8%BE%91%E5%B7%A5%E5%85%B7)
  - [声音特效编辑工具](#%E5%A3%B0%E9%9F%B3%E7%89%B9%E6%95%88%E7%BC%96%E8%BE%91%E5%B7%A5%E5%85%B7)
  - [背景音乐编辑工具](#%E8%83%8C%E6%99%AF%E9%9F%B3%E4%B9%90%E7%BC%96%E8%BE%91%E5%B7%A5%E5%85%B7)
  - [GIF 动画帧导出工具](#gif-%E5%8A%A8%E7%94%BB%E5%B8%A7%E5%AF%BC%E5%87%BA%E5%B7%A5%E5%85%B7)
  - [骨骼动画编辑工具](#%E9%AA%A8%E9%AA%BC%E5%8A%A8%E7%94%BB%E7%BC%96%E8%BE%91%E5%B7%A5%E5%85%B7)
  - [3D 模型工具](#3d-%E6%A8%A1%E5%9E%8B%E5%B7%A5%E5%85%B7)
  - [体素编辑工具](#%E4%BD%93%E7%B4%A0%E7%BC%96%E8%BE%91%E5%B7%A5%E5%85%B7)

<!--TOC END-->

## Cocos 文档相关

### Cocos2d-x 中英文发布说明

- GitBook 地址：[http://fusijie.github.io/Cocos2dx-Release-Note](http://fusijie.github.io/Cocos2dx-Release-Note)

- Github 地址：[https://github.com/fusijie/Cocos2dx-Release-Note](https://github.com/fusijie/Cocos2dx-Release-Note)

### Cocos2d-x 官方文档

- 在线版：[点击进入](https://docs.cocos.com/cocos2d-x/manual/zh)

### Cocos2d-x API 手册

- 在线版：[点击进入](http://www.cocos2d-x.org/docs/api-ref/index.html)

- 离线版：
  | Cocos2d-x 版本 | 下载地址 | 支持语言 |
  |:---:|:---:|:---:|
  |v3.15 |[点击下载](https://pan.baidu.com/s/1gfimQxP) | C++/JS/Lua |
  |v3.14 |[点击下载](https://pan.baidu.com/s/1jHVV1dG) | C++/JS/Lua |
  |v3.13 |[点击下载](https://pan.baidu.com/s/1boJs9zx) | C++/JS/Lua |
  |v3.12 |[点击下载](https://pan.baidu.com/s/1dEI82UP) | C++/JS/Lua |
  |v3.11 |[点击下载](https://pan.baidu.com/s/1nvp2iz3) | C++/JS/Lua |
  |v3.10 |[点击下载](https://pan.baidu.com/s/1kUfpCmr) | C++/JS/Lua |
  |v3.9 |[点击下载](https://pan.baidu.com/s/1eQRSDH4) | C++/JS/Lua |
  |v3.8 |[点击下载](https://pan.baidu.com/s/1hqXUhdq) | C++/JS/Lua |
  |v3.7 |[点击下载](https://pan.baidu.com/s/1kUuiUJt) | C++/JS/Lua |
  |v3.6 |[点击下载](https://pan.baidu.com/s/1eQEQKrK) | C++/JS/Lua |
  |v3.5 |[点击下载](https://pan.baidu.com/s/1eQjbJ0Y) | C++/JS/Lua |
  |v3.4 |[点击下载](https://pan.baidu.com/s/1kTh3VJT) | C++/JS/Lua |
  |v3.3 |[点击下载](https://pan.baidu.com/s/1qW2WA1A) | C++/JS/Lua |
  |v3.2 |[点击下载](https://pan.baidu.com/s/1kT3ODJx) | C++/JS/Lua |
  |v3.1 |[点击下载](https://pan.baidu.com/s/1bn0Hevt) | C++/JS/Lua |
  |v3.0 |[点击下载](https://pan.baidu.com/s/1gdYBU6n) | C++/JS/Lua |
  |v2.2.6 |[点击下载](https://pan.baidu.com/s/1pJJnFwZ) | C++/JS/Lua |
  |v2.2.3 |[点击下载](https://pan.baidu.com/s/1pKhOXcR) | C++/JS/Lua |

### Cocos Creator 官方文档

- 英文版：[点击进入](https://docs.cocos.com/creator/manual/en)

- 中文版：[点击进入](https://docs.cocos.com/creator/manual/zh)

### Cocos Creator API 手册

- 英文版：[点击进入](https://docs.cocos.com/creator/api/en)

- 中文版：[点击进入](https://docs.cocos.com/creator/api/zh)

### Cocos Creator 3D 官方文档

- 中文版：[点击进入](https://docs.cocos.com/creator3d/manual/zh/)

### Cocos Creator 3D API 手册

- 英文版：[点击进入](https://docs.cocos.com/creator3d/api/en/)

- 中文版：[点击进入](https://docs.cocos.com/creator3d/api/zh/)

## Cocos 引擎下载

_从 v3.7 开始，Cocos2d-js 合并入 Cocos2d-x。_

### Cocos2d-x 引擎下载

| 文件名                  |                               下载链接                                |
| :---------------------- | :-------------------------------------------------------------------: |
| cocos2d-x-4.0.zip       |       [点击下载](http://cocos2d-x.org/filedown/cocos2d-x-v4.0)        |
| cocos2d-x-3.17.2.zip    |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.17.2)     |
| cocos2d-x-3.17.1.zip    |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.17.1)     |
| cocos2d-x-3.17.zip      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.17.zip)    |
| cocos2d-x-3.16.zip      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.16.zip)    |
| cocos2d-x-3.15.1.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.15.1.zip)   |
| cocos2d-x-3.15.zip      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.15.zip)    |
| cocos2d-x-3.15rc0.zip   |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.15rc0.zip)  |
| cocos2d-x-3.14.1.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.14.1.zip)   |
| cocos2d-x-3.14.zip      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.14.zip)    |
| cocos2d-x-3.14.1rc0.zip | [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.14.1rc0.zip) |
| cocos2d-x-3.13.1.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.13.1.zip)   |
| cocos2d-x-3.13.zip      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.13.zip)    |
| cocos2d-x-3.12.zip      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.12.zip)    |
| cocos2d-x-3.11.1.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.11.1.zip)   |
| cocos2d-x-3.11.zip      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.11.zip)    |
| cocos2d-x-3.10.zip      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.10.zip)    |
| cocos2d-x-3.9.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.9.zip)    |
| cocos2d-x-3.9rc0.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.9rc0.zip)   |
| cocos2d-x-3.9beta0.zip  | [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.9beta0.zip)  |
| cocos2d-x-3.8.1.zip     |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.8.1.zip)   |
| cocos2d-x-3.8.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.8.zip)    |
| cocos2d-x-3.8-rc0.zip   |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.8-rc0.zip)  |
| cocos2d-x-3.8beta0.zip  | [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.8beta0.zip)  |
| cocos2d-x-3.7.1.zip     |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.7.1.zip)   |
| cocos2d-x-3.7.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.7.zip)    |
| cocos2d-x-3.7rc1.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.7rc1.zip)   |
| cocos2d-x-3.7rc0.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.7rc0.zip)   |
| cocos2d-x-3.7beta0.zip  | [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.7beta0.zip)  |
| cocos2d-x-3.6.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.6.zip)    |
| cocos2d-x-3.6beta0.zip  | [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.6beta0.zip)  |
| cocos2d-x-3.6alpha0.zip | [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.6alpha0.zip) |
| cocos2d-x-3.5.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.5.zip)    |
| cocos2d-x-3.5-tizen.zip | [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.5-tizen.zip) |
| cocos2d-x-3.5rc0.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.5rc0.zip)   |
| cocos2d-x-3.5beta0.zip  | [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.5beta0.zip)  |
| cocos2d-x-3.4.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.4.zip)    |
| cocos2d-x-3.4rc1.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.4rc1.zip)   |
| cocos2d-x-3.4rc0.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.4rc0.zip)   |
| cocos2d-x-3.4beta0.zip  | [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.4beta0.zip)  |
| cocos2d-x-3.3.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.3.zip)    |
| cocos2d-x-3.3rc2.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.3rc2.zip)   |
| cocos2d-x-3.3rc1.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.3rc1.zip)   |
| cocos2d-x-3.3rc0.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.3rc0.zip)   |
| cocos2d-x-3.3beta0      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.3beta0)    |
| cocos2d-x-3.2.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.2.zip)    |
| cocos2d-x-3.2rc0.zip    |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.2rc0.zip)   |
| cocos2d-x-3.2alpha0.zip | [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.2alpha0.zip) |
| cocos2d-x-3.1.1.zip     |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.1.1.zip)   |
| cocos2d-x-3.1.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.1.zip)    |
| cocos2d-x-3.1rc0        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.1rc0)     |
| cocos2d-x-3.0-cn        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.0-cn)     |
| cocos2d-x-3.0rc2-cn     |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-3.0rc2-cn)   |
| cocos2d-x-2.2.6.zip     |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-2.2.6.zip)   |
| cocos2d-x-2.2.4.zip     |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-2.2.4.zip)   |
| cocos2d-x-2.2.5.zip     |   [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-x-2.2.5.zip)   |

### Cocos2d-js 引擎下载

| 文件名                           |                                    下载链接                                    |
| :------------------------------- | :----------------------------------------------------------------------------: |
| cocos2d-js-v3.7beta0.zip         |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.7beta0.zip)     |
| cocos2d-js-v3.6.1.zip            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.6.1.zip)       |
| cocos2d-js-v3.6.zip              |       [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.6.zip)        |
| cocos2d-js-v3.6-beta.zip         |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.6-beta.zip)     |
| cocos2d-js-v3.5.zip              |       [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.5.zip)        |
| cocos2d-js-v3.4-beta0.zip        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.4-beta0.zip)     |
| cocos2d-js-v3.3.zip              |       [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.3.zip)        |
| cocos2d-js-v3.3-rc0.zip          |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.3-rc0.zip)      |
| cocos2d-js-v3.3-beta.zip         |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.3-beta.zip)     |
| cocos2d-js-v3.2.zip              |       [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.2.zip)        |
| cocos2d-js-v3.2-rc0.zip          |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.2-rc0.zip)      |
| cocos2d-js-v3.1.zip              |       [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.1.zip)        |
| cocos2d-js-v3.1-beta.zip         |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.1-beta.zip)     |
| cocos2d-js-v3.0.zip              |       [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.0.zip)        |
| cocos2d-js-v3.0-pre.zip          |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.0-pre.zip)      |
| cocos2d-js-v3.0-rc3.zip          |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.0-rc3.zip)      |
| cocos2d-js-v3.0-rc2.zip          |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.0-rc2.zip)      |
| cocos2d-js-v3.0-rc1.zip          |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.0-rc1.zip)      |
| cocos2d-js-v3.0-rc0-hotfix.zip   |  [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.0-rc0-hotfix.zip)  |
| cocos2d-js-v3.0-rc0.zip          |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.0-rc0.zip)      |
| cocos2d-js-v3.0-beta.zip         |     [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.0-beta.zip)     |
| cocos2d-js-v3.0-alpha2-zip-cncdn | [点击下载](http://www.cocos2d-x.org/filedown/cocos2d-js-v3.0-alpha2-zip-cncdn) |

### Cocos2d-js Lite 引擎下载

- 在线生成：[http://cocos2d-x.org/filecenter/jsbuilder](http://cocos2d-x.org/filecenter/jsbuilder/)

### Quick-cocos2d-x 引擎下载

_Quick-cocos2d-x 大致可以分为三个阶段：v2.x， v3.x 以及现在还在维护的 quick 社区版_

| 文件名                           |                                         下载链接                                          |
| :------------------------------- | :---------------------------------------------------------------------------------------: |
| quick-cocos2d-x-community-v3.7.7 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.7.7_Release)  |
| quick-cocos2d-x-community-v3.7.6 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.7.6_Release)  |
| quick-cocos2d-x-community-v3.7.5 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.7.5_Release)  |
| quick-cocos2d-x-community-v3.7.4 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.7.4_Release)  |
| quick-cocos2d-x-community-v3.7.3 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.7.3_Release)  |
| quick-cocos2d-x-community-v3.7.2 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.7.2_Release)  |
| quick-cocos2d-x-community-v3.7.1 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.7.1_Release)  |
| quick-cocos2d-x-community-v3.7.0 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.7.0_Release)  |
| quick-cocos2d-x-community-v3.6.5 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.6.5_Release)  |
| quick-cocos2d-x-community-v3.6.4 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.6.4_Release)  |
| quick-cocos2d-x-community-v3.6.3 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.6.3_release)  |
| quick-cocos2d-x-community-v3.6.2 |  [点击下载](https://github.com/u0u0/Quick-Cocos2dx-Community/releases/tag/3.6.2_Release)  |
| quick-cocos2d-x-community-v3.6.1 | [点击下载](https://github.com/iTyran/Quick-Cocos2dx-Community/releases/tag/3.6.1_Release) |
| quick-cocos2d-x-community-v3.6   |  [点击下载](https://github.com/iTyran/Quick-Cocos2dx-Community/releases/tag/3.6_release)  |
| quick-cocos2d-x-v3.3             |     [点击下载](https://github.com/dualface/v3quick/releases/tag/quick-cocos2d-x-v3.3)     |
| quick-cocos2d-x-v3.3rc1          |   [点击下载](https://github.com/dualface/v3quick/releases/tag/quick-cocos2d-x-v3.3rc1)    |
| quick-cocos2d-x-v3.3rc0          |   [点击下载](https://github.com/dualface/v3quick/releases/tag/quick-cocos2d-x-v3.3rc0)    |
| quick-cocos2d-x-v3.3alpha3       |   [点击下载](https://github.com/dualface/v3quick/releases/tag/quick-cocos2d-x-v3alpha3)   |
| quick-cocos2d-x-v3.0alpha2       |  [点击下载](https://github.com/dualface/v3quick/releases/tag/quick-cocos2d-x-3.0alpha2)   |
| quick-cocos2d-x-v2.2.6           |     [点击下载](https://github.com/chukong/quick-cocos2d-x/releases/tag/2.2.6-release)     |
| quick-cocos2d-x-v2.2.5-plus      |  [点击下载](https://github.com/chukong/quick-cocos2d-x/releases/tag/2.2.5-plus-release)   |
| quick-cocos2d-x-v2.2.5           |     [点击下载](https://github.com/chukong/quick-cocos2d-x/releases/tag/2.2.5-release)     |
| quick-cocos2d-x-v2.2.4           |     [点击下载](https://github.com/chukong/quick-cocos2d-x/releases/tag/2.2.4-release)     |
| quick-cocos2d-x-v2.2.3rc         |       [点击下载](https://github.com/chukong/quick-cocos2d-x/releases/tag/2.2.3-rc)        |
| quick-cocos2d-x-v2.2.1rc         |       [点击下载](https://github.com/chukong/quick-cocos2d-x/releases/tag/2.2.1-rc)        |
| quick-cocos2d-x-v2.1.5           | [点击下载](https://github.com/chukong/quick-cocos2d-x/releases/tag/stable-2.1.5-20130827) |
| quick-cocos2d-x-v2.1.4-20130821  | [点击下载](https://github.com/chukong/quick-cocos2d-x/releases/tag/stable-2.1.4-20130821) |
| quick-cocos2d-x-v2.1.4-20130808  | [点击下载](https://github.com/chukong/quick-cocos2d-x/releases/tag/stable-2.1.4-20130808) |

## Cocos Creator 下载

**Cocos Creator 采用引擎开源，编辑器不开源的方式发行**

### Cocos Creator 引擎下载

- Github 开源：[https://github.com/cocos-creator/engine](https://github.com/cocos-creator/engine)

### Cocos Creator v2 下载

**从 v2.3.2 及之后的版本 Cocos Creator 引入了 Cocos Dashboard 来管理引擎版本和项目，不再提供单独的下载路径**

| 文件名                   |                                下载链接                                |
| :----------------------- | :--------------------------------------------------------------------: |
| CocosCreator_v2.3.1_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.3.1_win)  |
| CocosCreator_v2.3.1_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.3.1_mac)  |
| CocosCreator_v2.3.0_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.3.0_win)  |
| CocosCreator_v2.3.0_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.3.0_mac)  |
| CocosCreator_v2.2.2_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.2.2_win)  |
| CocosCreator_v2.2.2_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.2.2_mac)  |
| CocosCreator_v2.2.1_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.2.1_win)  |
| CocosCreator_v2.2.1_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.2.1_mac)  |
| CocosCreator_v2.2.0_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.2.0_win)  |
| CocosCreator_v2.2.0_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.2.0_mac)  |
| CocosCreator_v2.1.4_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.1.4_win)  |
| CocosCreator_v2.1.4_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.1.4_mac)  |
| CocosCreator_v2.1.3_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.1.3_win)  |
| CocosCreator_v2.1.3_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.1.3_mac)  |
| CocosCreator_v2.1.2_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.1.2_win)  |
| CocosCreator_v2.1.2_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.1.2_mac)  |
| CocosCreator_v2.1.1_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.1.1_win)  |
| CocosCreator_v2.1.1_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.1.1_mac)  |
| CocosCreator_v2.1.0_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.1.0_win)  |
| CocosCreator_v2.1.0_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.1.0_mac)  |
| CocosCreator_v2.0.10_win | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.10_win) |
| CocosCreator_v2.0.10_mac | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.10_mac) |
| CocosCreator_v2.0.9_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.9_win)  |
| CocosCreator_v2.0.9_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.9_mac)  |
| CocosCreator_v2.0.8_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.8_win)  |
| CocosCreator_v2.0.8_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.8_mac)  |
| CocosCreator_v2.0.7_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.7_win)  |
| CocosCreator_v2.0.7_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.7_mac)  |
| CocosCreator_v2.0.6_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.6_win)  |
| CocosCreator_v2.0.6_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.6_mac)  |
| CocosCreator_v2.0.5_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.5_win)  |
| CocosCreator_v2.0.5_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.5_mac)  |
| CocosCreator_v2.0.4_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.4_win)  |
| CocosCreator_v2.0.4_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.4_mac)  |
| CocosCreator_v2.0.2_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.2_win)  |
| CocosCreator_v2.0.2_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.2_mac)  |
| CocosCreator_v2.0.1_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.1_win)  |
| CocosCreator_v2.0.1_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.1_mac)  |
| CocosCreator_v2.0.0_win  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.0_win)  |
| CocosCreator_v2.0.0_mac  | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v2.0.0_mac)  |

### Cocos Creator v1 下载

| 文件名                        |                                  下载链接                                   |
| :---------------------------- | :-------------------------------------------------------------------------: |
| CocosCreator_v1.10.2_win      |   [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.10.2_win)    |
| CocosCreator_v1.10.2_mac      |   [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.10.2_mac)    |
| CocosCreator_v1.10.1_win      |   [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.10.1_win)    |
| CocosCreator_v1.10.1_mac      |   [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.10.1_mac)    |
| CocosCreator_v1.10.0_win      |   [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.10.0_win)    |
| CocosCreator_v1.10.0_mac      |   [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.10.0_mac)    |
| CocosCreator_1.9.3_win        |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_1.9.3_win)     |
| CocosCreator_v1.9.3_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.9.3_mac)    |
| CocosCreator_v1.9.2_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.9.2_win)    |
| CocosCreator_v1.9.2_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.9.2_mac)    |
| CocosCreator_v1.9.1_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.9.1_win)    |
| CocosCreator_v1.9.1_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.9.1_mac)    |
| CocosCreator_v1.9.0_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.9.0_win)    |
| CocosCreator_v1.9.0_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.9.0_mac)    |
| CocosCreator_v1.9.0-rc1_mac   |  [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.9.0-rc1_mac)  |
| CocosCreator_v1.8.2_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.8.2_win)    |
| CocosCreator_v1.8.2_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.8.2_mac)    |
| CocosCreator_v1.8.1_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.8.1_win)    |
| CocosCreator_v1.8.1_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.8.1_mac)    |
| CocosCreator_v1.8.0_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.8.0_win)    |
| CocosCreator_v1.8.0_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.8.0_mac)    |
| CocosCreator_v1.7.2_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.7.2_win)    |
| CocosCreator_v1.7.2_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.7.2_mac)    |
| CocosCreator_v1.7.0_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.7.0_win)    |
| CocosCreator_v1.7.0_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.7.0_mac)    |
| CocosCreator_v1.6.2_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.6.2_win)    |
| CocosCreator_v1.6.2_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.6.2_mac)    |
| CocosCreator_v1.6.1_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.6.1_win)    |
| CocosCreator_v1.6.1_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.6.1_mac)    |
| CocosCreator_v1.6.0_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.6.0_win)    |
| CocosCreator_v1.6.0_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.6.0_mac)    |
| CocosCreator_v1.5.2_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.5.2_mac)    |
| CocosCreator_v1.5.2_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.5.2_win)    |
| CocosCreator_v1.5.1_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.5.1_mac)    |
| CocosCreator_v1.5.1_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.5.1_win)    |
| CocosCreator_v1.5.0_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.5.0_mac)    |
| CocosCreator_v1.5.0_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.5.0_win)    |
| CocosCreator_v1.4.2_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.4.2_mac)    |
| CocosCreator_v1.4.2_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.4.2_win)    |
| CocosCreator_v1.4.1_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.4.1_mac)    |
| CocosCreator_v1.4.1_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.4.1_win)    |
| CocosCreator_v1.4.0_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.4.0_mac)    |
| CocosCreator_v1.4.0_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.4.0_win)    |
| CocosCreator_v1.3.3_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.3.3_mac)    |
| CocosCreator_v1.3.3_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.3.3_win)    |
| CocosCreator_v1.3.2_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.3.2_mac)    |
| CocosCreator_v1.3.2_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.3.2_win)    |
| CocosCreator_v1.3.1_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.3.1_mac)    |
| CocosCreator_v1.3.1_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.3.1_win)    |
| CocosCreator_v1.3.0_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.3.0_mac)    |
| CocosCreator_v1.3.0_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.3.0_win)    |
| Creator-Lua-Support-1.1.3-mac | [点击下载](http://www.cocos2d-x.org/filedown/Creator-Lua-Support-1.1.3-mac) |
| Creator-Lua-Support-1.1.3-win | [点击下载](http://www.cocos2d-x.org/filedown/Creator-Lua-Support-1.1.3-win) |
| CocosCreator_v1.2.2_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.2.2_mac)    |
| CocosCreator_v1.2.2_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.2.2_win)    |
| CocosCreator_v1.2.1_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.2.1_mac)    |
| CocosCreator_v1.2.1_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.2.1_win)    |
| CocosCreator-Lua-v1.0         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator-Lua-v1.0)     |
| CocosCreator_v1.2.0_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.2.0_mac)    |
| CocosCreator_v1.2.0_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.2.0_win)    |
| CocosCreator_v1.1.2_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.1.2_mac)    |
| CocosCreator_v1.1.2_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.1.2_win)    |
| CocosCreator_v1.1.1_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.1.1_win)    |
| CocosCreator_v1.1.1_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.1.1_mac)    |
| CocosCreator_v1.1.0_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.1.0_win)    |
| CocosCreator_v1.1.0_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.1.0_mac)    |
| CocosCreator_v1.0.3_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.0.3_win)    |
| CocosCreator_v1.0.3_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.0.3_mac)    |
| CocosCreator_v1.0.2_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.0.2_mac)    |
| CocosCreator_v1.0.2_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.0.2_win)    |
| CocosCreator_v1.0.1_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.0.1_mac)    |
| CocosCreator_v1.0.1_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.0.1_win)    |
| CocosCreator_v1.0.0_win_en    |  [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.0.0_win_en)   |
| CocosCreator_v1.0.0_win       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.0.0_win)    |
| CocosCreator_v1.0.0_mac_en    |  [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.0.0_mac_en)   |
| CocosCreator_v1.0.0_mac       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v1.0.0_mac)    |
| CocosCreator_v0.7.1_win_en    |  [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v0.7.1_win_en)   |
| CocosCreator_v0.7.1_mac_en    |  [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v0.7.1_mac_en)   |
| CocosCreator_v0.7.0_mac.zip   |  [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v0.7.0_mac.zip)  |
| CocosCreator_v0.7.0_win.zip   |  [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator_v0.7.0_win.zip)  |

### Cocos Creator 3D 下载

| 文件名                    |                                下载链接                                 |
| :------------------------ | :---------------------------------------------------------------------: |
| CocosCreator3D-v1.0.4-win |  [点击下载](https://cocos2d-x.org/filedown/CocosCreator3D-v1.0.4_win)   |
| CocosCreator3D-v1.0.4-mac |  [点击下载](https://cocos2d-x.org/filedown/CocosCreator3D-v1.0.4_mac)   |
| CocosCreator3D-v1.0.3-win |  [点击下载](https://cocos2d-x.org/filedown/CocosCreator3D_v1.0.3_win)   |
| CocosCreator3D-v1.0.3-mac |  [点击下载](https://cocos2d-x.org/filedown/CocosCreator3D_v1.0.3_mac)   |
| CocosCreator3D-v1.0.2-win | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator3D-v1.0.2-win) |
| CocosCreator3D-v1.0.2-mac | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator3D-v1.0.2-mac) |
| CocosCreator3D-v1.0.1-win | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator3D-v1.0.1-win) |
| CocosCreator3D-v1.0.1-mac | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator3D-v1.0.1-mac) |
| CocosCreator3D-v1.0.0-win | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator3D-v1.0.0-win) |
| CocosCreator3D-v1.0.0-mac | [点击下载](http://www.cocos2d-x.org/filedown/CocosCreator3D-v1.0.0-mac) |

## Cocos 配套工具下载

### Cocos 下载

| 文件名                                  |                                       下载链接                                        |
| :-------------------------------------- | :-----------------------------------------------------------------------------------: |
| CocosForWin-v3.10.exe                   |          [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v3.10.exe)          |
| CocosForMac-v3.10-Update.pkg            |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v3.10-Update.pkg)       |
| CocosForWin-v2.3.3.exe                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.3.exe)          |
| CocosForWin-v3.10-Update.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v3.10-Update.exe)       |
| CocosForMac-v3.10.dmg                   |          [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v3.10.dmg)          |
| CocosForWinWithFramework-v2.3.2.3.exe   |  [点击下载](http://www.cocos2d-x.org/filedown/CocosForWinWithFramework-v2.3.2.3.exe)  |
| CocosForMacWithFramework-v2.3.3.dmg     |   [点击下载](http://www.cocos2d-x.org/filedown/CocosForMacWithFramework-v2.3.3.dmg)   |
| CocosForWinWithFramework-v2.3.3.exe     |   [点击下载](http://www.cocos2d-x.org/filedown/CocosForWinWithFramework-v2.3.3.exe)   |
| CocosForMacWithFramework-v2.3.2.3.dmg   |  [点击下载](http://www.cocos2d-x.org/filedown/CocosForMacWithFramework-v2.3.2.3.dmg)  |
| CocosForWinWithFramework-v2.3.2.exe     |   [点击下载](http://www.cocos2d-x.org/filedown/CocosForWinWithFramework-v2.3.2.exe)   |
| CocosForMacWithFramework-v2.3.2.dmg     |   [点击下载](http://www.cocos2d-x.org/filedown/CocosForMacWithFramework-v2.3.2.dmg)   |
| CocosForWin-v2.2.5.exe                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.2.5.exe)          |
| CocosForMac-v2.3.3.dmg                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.3.dmg)          |
| CocosForWin-v2.3.2.3.exe                |        [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.2.3.exe)         |
| CocosForWin-v2.1.5.exe                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.1.5.exe)          |
| CocosForWin-v2.2.9-Update.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.2.9-Update.exe)      |
| CocosForMac-v2.3.1.2-Update.pkg         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.1.2-Update.pkg)     |
| CocosForWin--v2.3.0.exe                 |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin--v2.3.0.exe)         |
| CocosForWin-v2.2.6-Update.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.2.6-Update.exe)      |
| CocosForWin-v2.1.5-Update.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.1.5-Update.exe)      |
| CocosForWin-v2.2.6.exe                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.2.6.exe)          |
| CocosForWin-v2.3.3-Update.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.3-Update.exe)      |
| CocosForWin-v2.3.1.1.exe                |        [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.1.1.exe)         |
| CocosForWin-v2.2.5-Update.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.2.5-Update.exe)      |
| CocosForWin-V2.2.8.exe                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-V2.2.8.exe)          |
| CocosForWin-v2.3.2Beta.exe              |       [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.2Beta.exe)        |
| CocosForWin-v2.2.1.exe                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.2.1.exe)          |
| CocosForWin-v2.3.1.1-Update.exe         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.1.1-Update.exe)     |
| CocosForWin-v2.1.exe                    |          [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.1.exe)           |
| CocosForMac-v2.1.dmg                    |          [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.1.dmg)           |
| CocosForMac-v2.3.3-Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.3-Update.pkg)      |
| CocosForMac-v2.3.2.3-Update.pkg         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.2.3-Update.pkg)     |
| CocosForWin-v2.1.2Beta.exe              |       [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.1.2Beta.exe)        |
| CocosForMac-v2.3.2Beta1.dmg             |       [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.2Beta1.dmg)       |
| CocosForMac-v2.3.2.3.dmg                |        [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.2.3.dmg)         |
| CocosForMac-v2.3.1.dmg                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.1.dmg)          |
| CocosForMac-v2.3.2.dmg                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.2.dmg)          |
| CocosForMac-v2.3.1.1.dmg                |        [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.1.1.dmg)         |
| CocosForMac-v2.2.1.dmg                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.2.1.dmg)          |
| CocosForMac-v2.2.5.dmg                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.2.5.dmg)          |
| CocosForMac-v2.2.6.dmg                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.2.6.dmg)          |
| CocosForMac-V2.2.8.dmg                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-V2.2.8.dmg)          |
| CocosForMac-v2.1.5.dmg                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.1.5.dmg)          |
| CocosForWin-V2.3.0.exe                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-V2.3.0.exe)          |
| CocosForMac_v2.3.0.dmg                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac_v2.3.0.dmg)          |
| CocosForWin-v2.3.1.2.exe                |        [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.1.2.exe)         |
| CocosForMac_v2.3.2Beta.dmg              |       [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac_v2.3.2Beta.dmg)        |
| CocosForWin-v2.3.1.exe                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.1.exe)          |
| CocosForMac-v2.1.2Beta.dmg              |       [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.1.2Beta.dmg)        |
| CocosForWin-v2.3.2.3-Update.exe         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.2.3-Update.exe)     |
| CocosForMac-v2.1.5-Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.1.5-Update.pkg)      |
| CocosForWin-v2.2.9.exe                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.2.9.exe)          |
| CocosForWin-v2.3.2.exe                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.2.exe)          |
| CocosForMac-v2.3.1.2.dmg                |        [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.1.2.dmg)         |
| CocosForWin-V2.2.8-Update.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-V2.2.8-Update.exe)      |
| CocosForMac-v2.3.2Beta.dmg              |       [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.2Beta.dmg)        |
| CocosForWin-V2.3.0-Update.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-V2.3.0-Update.exe)      |
| CocosForWin-v2.3.1.2-Update.exe         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.1.2-Update.exe)     |
| CocosForWin-v2.2.1-Update.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.2.1-Update.exe)      |
| CocosForWin-v2.2.1-Update-WithNet45.exe | [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.2.1-Update-WithNet45.exe) |
| CocosForMac-V2.3.0.dmg                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-V2.3.0.dmg)          |
| CocosForMac_v2.3.2.dmg                  |         [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac_v2.3.2.dmg)          |
| CocosForMac_v2.3.2-Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac_v2.3.2-Update.pkg)      |
| CocosForWin-v2.1-Update.exe             |       [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.1-Update.exe)       |
| CocosForMac-v2.3.2-Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.2-Update.pkg)      |
| CocosForWin-v2.3.2-Update.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.2-Update.exe)      |
| CocosForMac-v2.2.1-Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.2.1-Update.pkg)      |
| CocosForWin--v2.3.0-Update.exe          |     [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin--v2.3.0-Update.exe)      |
| CocosForMac-v2.3.1.1-Update.pkg         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.1.1-Update.pkg)     |
| CocosForMac_v2.3.0_Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac_v2.3.0_Update.pkg)      |
| CocosForWin-v2.3.1-Update.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.3.1-Update.exe)      |
| CocosForMac-v2.3.1-Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.3.1-Update.pkg)      |
| CocosForMac-v2.2.9-Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.2.9-Update.pkg)      |
| CocosForMac-V2.3.0-Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-V2.3.0-Update.pkg)      |
| CocosForMac-V2.2.8-Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-V2.2.8-Update.pkg)      |
| CocosForMac-v2.2.6-Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.2.6-Update.pkg)      |
| CocosForMac-v2.2.5-Update.pkg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.2.5-Update.pkg)      |
| CocosForWin-v2.1.5-UpdateWithDotNet.exe | [点击下载](http://www.cocos2d-x.org/filedown/CocosForWin-v2.1.5-UpdateWithDotNet.exe) |
| CocosForMac-v2.1-Update.pkg             |       [点击下载](http://www.cocos2d-x.org/filedown/CocosForMac-v2.1-Update.pkg)       |
| Cocos-v1.0-preview-win32.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/Cocos-v1.0-preview-win32.exe)       |
| Cocos-v1.0-preview-mac64.dmg            |      [点击下载](http://www.cocos2d-x.org/filedown/Cocos-v1.0-preview-mac64.dmg)       |
| Cocos-v1.0-preview-win64.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/Cocos-v1.0-preview-win64.exe)       |

### Cocos Studio 下载

| 文件名                               |                                      下载链接                                      |
| :----------------------------------- | :--------------------------------------------------------------------------------: |
| CocosStudioForWin-v2.0.6.exe         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-v2.0.6.exe)     |
| CocosStudio_v1.0.0.0_Beta.dmg        |    [点击下载](http://www.cocos2d-x.org/filedown/CocosStudio_v1.0.0.0_Beta.dmg)     |
| CocosStudio_v1.6.0.0.exe             |       [点击下载](http://www.cocos2d-x.org/filedown/CocosStudio_v1.6.0.0.exe)       |
| CocosStudioForMac-v2.0.2.dmg         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-v2.0.2.dmg)     |
| CocosStudioForMac-v2.0.5.dmg         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-v2.0.5.dmg)     |
| CocosStudioForMac-v2.0.6.dmg         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-v2.0.6.dmg)     |
| CocosStudioForWin-v2.1.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-v2.1.exe)      |
| CocosStudioForWin-v2.1.exe           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-v2.1.exe)      |
| CocosStudio_v1.5.0.1.exe             |       [点击下载](http://www.cocos2d-x.org/filedown/CocosStudio_v1.5.0.1.exe)       |
| CocosStudioForMac-v2.1.dmg           |      [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-v2.1.dmg)      |
| CocoStudio(2DX3.0)\_v1.4.0.1.exe     |  [点击下载](<http://www.cocos2d-x.org/filedown/CocoStudio(2DX3.0)_v1.4.0.1.exe>)   |
| CocosStudioForMac-v2.1-Beta.dmg      |   [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-v2.1-Beta.dmg)    |
| CocoStudio_v1.4.0.1.exe              |       [点击下载](http://www.cocos2d-x.org/filedown/CocoStudio_v1.4.0.1.exe)        |
| CocosStudioForWin-v2.1-Beta.exe      |   [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-v2.1-Beta.exe)    |
| CocosStudio_v1.5.0.0.exe             |       [点击下载](http://www.cocos2d-x.org/filedown/CocosStudio_v1.5.0.0.exe)       |
| CocosStudioForWin-v2.0.0.0-Beta0.exe | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-v2.0.0.0-Beta0.exe) |
| CocosStudioForWin-v2.0.5.exe         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-v2.0.5.exe)     |
| CocosStudioForWin-v2.0.2.exe         |     [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-v2.0.2.exe)     |
| CocosStudioForMac-v2.1-Update.pkg    |  [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-v2.1-Update.pkg)   |
| CocosStudioForMac-v2.0.5-Update.pkg  | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-v2.0.5-Update.pkg)  |
| CocosStudioForMac-2.0.0.0-Alpha.dmg  | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-2.0.0.0-Alpha.dmg)  |
| CocosStudioForMac-2.0.0.0-Beta0.dmg  | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-2.0.0.0-Beta0.dmg)  |
| CocoStudio_v1.0.0.0_Alpha1.dmg       |    [点击下载](http://www.cocos2d-x.org/filedown/CocoStudio_v1.0.0.0_Alpha1.dmg)    |
| CocoStudio(2DX2.2.3)\_v1.4.0.1.exe   | [点击下载](<http://www.cocos2d-x.org/filedown/CocoStudio(2DX2.2.3)_v1.4.0.1.exe>)  |
| CocosStudioForMac-v2.0.0.0-Beta0.dmg | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-v2.0.0.0-Beta0.dmg) |
| CocosStudioForWin_v2.0.0.0_Alpha.exe | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin_v2.0.0.0_Alpha.exe) |
| CocosStudio_v1.6.0.0_store.exe       |    [点击下载](http://www.cocos2d-x.org/filedown/CocosStudio_v1.6.0.0_store.exe)    |
| CocosStudioForWin-v2.0.6-Update.exe  | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-v2.0.6-Update.exe)  |
| CocosStudioForMac-v2.0.6-Update.pkg  | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-v2.0.6-Update.pkg)  |
| CocosStudioForWin-v2.1-Update.exe    |  [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-v2.1-Update.exe)   |
| CocosStudioForWin-v2.0.5-Update.exe  | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-v2.0.5-Update.exe)  |
| CocosStudioForWin-v2.0.2-Update.exe  | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-v2.0.2-Update.exe)  |
| CocosStudioForMac-v2.0.2-Update.pkg  | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-v2.0.2-Update.pkg)  |
| CocosStudioForMac_v2.0.0.0_Alpha.dmg | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac_v2.0.0.0_Alpha.dmg) |
| CocosStudioForMac_2.0.0.0_Alpha.dmg  | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac_2.0.0.0_Alpha.dmg)  |
| CocosStudioForMac-2.0.0.0_Alpha.dmg  | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForMac-2.0.0.0_Alpha.dmg)  |
| CocosStudioForWin-2.0.0.0-Beta0.exe  | [点击下载](http://www.cocos2d-x.org/filedown/CocosStudioForWin-2.0.0.0-Beta0.exe)  |

### Cocos Framework 下载

| 文件名                             |                                     下载链接                                     |
| :--------------------------------- | :------------------------------------------------------------------------------: |
| CocosFramework-V3.7.1-Mac.pkg      |   [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-V3.7.1-Mac.pkg)    |
| CocosFramework-v3.6.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.6.exe)       |
| CocosFramework-v3.5.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.5.exe)       |
| CocosFramework-v3.4rc1-windows.exe | [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.4rc1-windows.exe) |
| CocosFramework-V3.9-Windows.exe    |  [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-V3.9-Windows.exe)   |
| CocosFramework-v3.6.pkg            |      [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.6.pkg)       |
| CocosFramework-V3.8-Windows.exe    |  [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-V3.8-Windows.exe)   |
| CocosFramework-V3.8.1-Windows.exe  | [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-V3.8.1-Windows.exe)  |
| CocosFramework-V3.9-Mac.pkg        |    [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-V3.9-Mac.pkg)     |
| CocosFramework-V3.9-Mac.pkg        |    [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-V3.9-Mac.pkg)     |
| CocosFramework-V3.8-Mac.pkg        |    [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-V3.8-Mac.pkg)     |
| CocosFramework-v3.7.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.7.exe)       |
| CocosFramework-V3.7.1-Windows.exe  | [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-V3.7.1-Windows.exe)  |
| CocosFramework-V3.8.1-Mac.pkg      |   [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-V3.8.1-Mac.pkg)    |
| CocosFramework-v3.4-windows.exe    |  [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.4-windows.exe)   |
| CocosFramework-v3.4-mac.pkg        |    [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.4-mac.pkg)     |
| CocosFramework-v3.5.pkg            |      [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.5.pkg)       |
| CocosFramework-v3.7.pkg            |      [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.7.pkg)       |
| CocosFramework-v3.4rc1-mac.pkg     |   [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.4rc1-mac.pkg)   |
| CocosFramework-v3.4.2-windows.exe  | [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.4.2-windows.exe)  |
| CocosFramework-v3.4.2-mac.pkg      |   [点击下载](http://www.cocos2d-x.org/filedown/CocosFramework-v3.4.2-mac.pkg)    |
| CocosFrameworkSamples_v3.8.zip     |   [点击下载](http://www.cocos2d-x.org/filedown/CocosFrameworkSamples_v3.8.zip)   |
| CocosFrameworkSamples_v3.9.zip     |   [点击下载](http://www.cocos2d-x.org/filedown/CocosFrameworkSamples_v3.9.zip)   |

### Cocos Simuator 下载

| 文件名                     |                                 下载链接                                 |
| :------------------------- | :----------------------------------------------------------------------: |
| CocosSimulatorWin_v1.0.exe | [点击下载](http://www.cocos2d-x.org/filedown/CocosSimulatorWin_v1.0.exe) |
| CocosSimulatorMac_v1.0.pkg | [点击下载](http://www.cocos2d-x.org/filedown/CocosSimulatorMac_v1.0.pkg) |

### Cocos IDE 下载

| 文件名                                    |                                        下载链接                                         |
| :---------------------------------------- | :-------------------------------------------------------------------------------------: |
| cocos-code-ide-win64-1.0.0-rc1.exe        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.0-rc1.exe)     |
| cocos-code-ide-win64-1.0.0-beta-zip-cncdn | [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.0-beta-zip-cncdn) |
| cocos-code-ide-win32-1.2.0.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.2.0.exe)       |
| cocos-code-ide-mac64-1.2.0.dmg            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-mac64-1.2.0.dmg)       |
| cocos-code-ide-win64-1.2.0.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.2.0.exe)       |
| cocos-code-ide-2.0.0-beta.dmg             |       [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-2.0.0-beta.dmg)       |
| cocos-code-ide-2.0.0-beta.exe             |       [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-2.0.0-beta.exe)       |
| cocos-code-ide-mac64-1.1.0.dmg            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-mac64-1.1.0.dmg)       |
| cocos-code-ide-win64-1.0.2.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.2.exe)       |
| cocos-code-ide-win64-1.0.2.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.2.exe)       |
| cocos-code-ide-mac64-1.0.0-rc2.dmg        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-mac64-1.0.0-rc2.dmg)     |
| cocos-code-ide-mac64-1.0.0-rc1.dmg        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-mac64-1.0.0-rc1.dmg)     |
| cocos-code-ide-mac64-1.0.0-beta-zip-cncdn | [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-mac64-1.0.0-beta-zip-cncdn) |
| cocos-code-ide-win64-1.0.0-rc2.zip        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.0-rc2.zip)     |
| cocos-code-ide-win64-1.0.0-rc1.zip        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.0-rc1.zip)     |
| cocos-code-ide-win32-1.0.0-beta-zip-cncdn | [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.0-beta-zip-cncdn) |
| cocos-code-ide-win64-1.1.0.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.1.0.exe)       |
| cocos-code-ide-win32-1.0.0-rc1.zip        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.0-rc1.zip)     |
| cocos-code-ide-win32-1.1.0.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.1.0.exe)       |
| cocos-code-ide-mac64-1.0.1.dmg            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-mac64-1.0.1.dmg)       |
| cocos-code-ide-mac64-1.0.2.dmg            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-mac64-1.0.2.dmg)       |
| cocos-code-ide-win64-1.0.1.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.1.exe)       |
| cocos-code-ide-win32-1.0.0-rc1.exe        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.0-rc1.exe)     |
| cocos-code-ide-win32-1.0.2.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.2.exe)       |
| cocos-code-ide-mac64-1.0.0-rc0.dmg        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-mac64-1.0.0-rc0.dmg)     |
| cocos-code-ide-win32-1.0.1.exe            |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.1.exe)       |
| cocos-code-ide-1.1.0-update.zip           |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-1.1.0-update.zip)      |
| cocos-code-ide-1.0.2-update.zip           |      [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-1.0.2-update.zip)      |
| cocos-code-ide-win64-1.0.0-rc2.exe        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.0-rc2.exe)     |
| cocos-code-ide-win32-1.0.0-rc2.zip        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.0-rc2.zip)     |
| cocos-code-ide-win32-1.0.0-rc2.exe        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.0-rc2.exe)     |
| cocos-code-ide-win64-1.0.0-rc0.zip        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.0-rc0.zip)     |
| cocos-code-ide-win32-1.0.2-beta.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.2-beta.zip)    |
| cocos-code-ide-mac64-1.0.2-beta.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-mac64-1.0.2-beta.zip)    |
| cocos-code-ide-win64-1.0.0-final.exe      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.0-final.exe)    |
| cocos-code-ide-win64-1.0.0-rc0.exe        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.0-rc0.exe)     |
| cocos-code-ide-mac64-1.0.0-rc0.zip        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-mac64-1.0.0-rc0.zip)     |
| cocos-code-ide-win32-1.0.0-rc0.zip        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.0-rc0.zip)     |
| cocos-code-ide-win64-1.0.2-beta.zip       |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.2-beta.zip)    |
| cocos-code-ide-win32-1.0.0-final.exe      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.0-final.exe)    |
| cocos-code-ide-mac64-1.0.0-final.dmg      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-mac64-1.0.0-final.dmg)    |
| cocos-code-ide-win32-1.0.0-rc0.exe        |    [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.0-rc0.exe)     |
| cocos-code-ide-win32-1.0.0-final.zip      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win32-1.0.0-final.zip)    |
| cocos-code-ide-win64-1.0.0-final.zip      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos-code-ide-win64-1.0.0-final.zip)    |
| cocos-intellij-plugin-2.0.0-beta.zip      |   [点击下载](http://www.cocos2d-x.org/filedown/cocos-intellij-plugin-2.0.0-beta.zip)    |

## Cocos 版本关系说明

### Cocos2d-x 与 Cocos Studio 版本对应关系

_此部分数据来自[CocoaChina: Cocos Studio 和 Cocos2d-x 版本对应关系](http://www.cocoachina.com/bbs/read.php?tid-182077-keyword-%B0%E6%B1%BE%B6%D4%D3%A6.html)，数据可能不完整，仅提供参考。_

- Studio 2.x

|       CocosStudio 版本       | Cocos2d-x 版本 | Cocos2d-js 版本 | 备注                                                                                |
| :--------------------------: | :------------: | :-------------: | :---------------------------------------------------------------------------------- |
| v2.1.5<br>v2.1.2beta<br>v2.1 |   v3.4final    |    v3.3 rc0+    | Cocos 新增 JSON 格式导出，Cocos2d-JS 仅支持此格式，v2.1 更名 Cocos                  |
|           v2.1beta           |   v3.4beta0    |     不支持      | 已分离出 reader，可以将 reader 拉取到其他版本 Cocos2d-x，以支持新版本的 CocosStudio |
|            v2.0.6            |   v3.3final    |     不支持      |
|            v2.0.5            |    v3.3rc2     |     不支持      |
|            v2.0.2            |    v3.3rc2     |     不支持      |
|          v2.0beta0           |    v3.3rc0     |      v3.1       |

- Studio 1.x

| CocosStudio 版本 | Cocos2d-x v3 版本 | Cocos2d-x v2 版本 | Cocos2d-js 版本 |
| :--------------: | :---------------: | :---------------: | :-------------: |
|     1.6.0.0      |        3.2        |       2.2.5       |       3.1       |
|     1.5.0.1      |        3.2        |       2.2.5       |     3.0 RC2     |
|     1.5.0.0      |        3.0        |       2.2.4       |     3.0 RC2     |
|     1.4.0.1      |        3.0        |       2.2.3       |     3.0 RC2     |
|     1.4.0.0      |        3.0        |       2.2.3       |     3.0 RC2     |
|     1.3.0.1      |      3.0rc1       |       2.2.3       |    3.0 Alpha    |
|     1.3.0.0      |      3.0rc0       |       2.2.3       |
|     1.2.0.1      |      3.0beta      |       2.2.2       |
|     1.1.0.0      |                   |       2.2.1       |
|     1.0.0.2      |                   |       2.2.0       |
|     1.0.0.1      |
|     1.0.0.0      |

### Cocos2d-x 与 NDK 版本对应关系

| Cocos2-x 版本 |     NDK 版本     | 备注                                                                                                                                                |
| :-----------: | :--------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
|     v3.0      | r8e / r9d / r10c | 因为 Android 5.0 某些问题，建议使用 r10c，不建议使用 r9d，原因可见[此贴](http://discuss.cocos2d-x.org/t/build-android-base-on-ndk-r10c/18543)，下同 |
|     v3.1      |    r9d / r10c    |
|     v3.2      |    r9d / r10c    | 直接使用 r10c 会编译失败，必须先根据[此 PR](https://github.com/cocos2d/cocos2d-x/pull/7526)修改                                                     |
|  v3.3 及以上  |       r10c       |

### Cocos Creator 与 NDK 版本对应关系

| Cocos Creator 版本 | NDK 版本 | 备注 |
| :----------------: | :------: | :--: |
|    v2.0.7 以下     |   r10c   |      |
|   v.2.0.7 及以上   |   r16    |      |

## Cocos Android 相关下载

### Android NDK 下载

| NDK 版本 |                          下载地址                           | 提取码 |                平台                 |
| :------: | :---------------------------------------------------------: | :----: | :---------------------------------: |
|   r8e    |         [点击下载](http://pan.baidu.com/s/1c0SCvug)         |        | Windows 32/64 Mac 32/64 Linux 32/64 |
|   r9d    |         [点击下载](http://pan.baidu.com/s/1kUiDdmZ)         |        | Windows 32/64 Mac 32/64 Linux 32/64 |
|   r10c   |         [点击下载](http://pan.baidu.com/s/1dEabLVr)         |        | Windows 32/64 Mac 32/64 Linux 32/64 |
|   r19c   | [点击下载](https://pan.baidu.com/s/1nvcpsyrNA9aGeVdi6blMRQ) |  m6gn  |    Windows 32/64 Mac 64 Linux 64    |

其他 NDK 版本可从[这里](https://developer.android.com/ndk/downloads/older_releases.html?hl=zh-cN)下载。

### Android Studio 下载

_从 Cocos2d-x v3.7 开始支持使用 Android Studio。_

- [点击下载](https://github.com/inferjay/AndroidDevTools#android-studio)

### Android ADT Bundle 下载

- [点击下载](https://github.com/inferjay/AndroidDevTools#adt-bundle)

## Cocos 第三方游戏工具下载

### Cocos Creator 插件

**Cocos Creator 插件可以在 `扩展->扩展商店` 中购买使用，这里只列举了一小部分。**

|             工具名             |                                               下载地址                                               | 授权 |  支持平台   |
| :----------------------------: | :--------------------------------------------------------------------------------------------------: | :--: | :---------: |
|            Excel2js            |                           [进入官网](https://github.com/fusijie/excel2js)                            | 开源 | Windows/Mac |
|      行为树可视化编辑插件      |            [进入官网](https://github.com/linhaiwei123/cocos-creator-behavior-tree-editor)            | 开源 | Windows/Mac |
|      Unpack TextureAtlas       |                   [进入官网](https://github.com/zilongshanren/unpack-textureatlas)                   | 开源 | Windows/Mac |
|        Hot-update-tools        |    [进入官网](https://github.com/tidys/CocosCreatorPlugins/tree/master/packages/hot-update-tools)    | 开源 | Windows/Mac |
|     色相、亮度、饱和度插件     |                         [进入官网](https://forum.cocos.com/t/creator/42328)                          | 开源 | Windows/Mac |
| processOn 可视化状态机编辑插件 |                    [进入官网](https://forum.cocos.com/t/processon-20170315/44030)                    | 开源 | Windows/Mac |
|           Quick-open           |                        [进入官网](https://github.com/pandamicro/quick-open/)                         | 开源 | Windows/Mac |
|         Quick-preview          |                        [进入官网](https://github.com/2youyou2/quick-preview)                         | 开源 | Windows/Mac |
|         CreatorConsole         |                       [进入官网](https://github.com/jeason1997/CreatorConsole)                       | 开源 | Windows/Mac |
|             Bugly              |      [进入官网](https://github.com/tidys/CocosCreatorPlugins/tree/master/packages/plugin-bugly)      | 开源 | Windows/Mac |
|           439WebSdk            | [进入官网](https://github.com/tidys/CocosCreatorPlugins/tree/master/packages/plugin-4399-web-js-sdk) | 开源 | Windows/Mac |
|          excel-killer          |      [进入官网](https://github.com/tidys/CocosCreatorPlugins/tree/master/packages/excel-killer)      | 开源 | Windows/Mac |
|          res-compress          |      [进入官网](https://github.com/tidys/CocosCreatorPlugins/tree/master/packages/res-compress)      | 开源 | Windows/Mac |
|         cc-inspector+          |  [进入官网](https://github.com/tidys/CocosCreatorPlugins/blob/master/doc/cc-inspector-v2/index.md)   | 付费 | Windows/Mac |

### 位图字体工具

|     工具名     |                        下载地址                         | 授权 |  支持平台   |
| :------------: | :-----------------------------------------------------: | :--: | :---------: |
|     BMFont     |  [进入官网](http://www.angelcode.com/products/bmfont)   | 免费 |   Windows   |
|   Fonteditor   |     [进入官网](http://code.google.com/p/fonteditor)     | 开源 | Windows/Mac |
| Glyph Designer |     [进入官网](http://glyphdesigner.71squared.com/)     | 付费 |     Mac     |
|     Hiero      | [进入官网](https://github.com/libgdx/libgdx/wiki/Hiero) | 免费 | Windows/Mac |

### 粒子编辑工具

|      工具名       |                                         下载地址                                          | 授权 | 支持平台 |
| :---------------: | :---------------------------------------------------------------------------------------: | :--: | :------: |
|  ParticleCreator  | [进入官网](https://itunes.apple.com/us/app/particle-creator-for-cocos2d/id564925232?mt=8) | 免费 |   iOS    |
| Particle Designer |                    [进入官网](http://particledesigner.71squared.com/)                     | 收费 |   Mac    |
| Particle Universe |            [进入官网](http://www.ogre3d.org/tikiwiki/Particle+Universe+plugin)            | 免费 | Windows  |
|  Particle Editor  |                [进入官网](http://onebyonedesign.com/flash/particleeditor/)                | 免费 |  Online  |
|    Particle2dx    |                     [进入官网](http://www.effecthub.com/particle2dx)                      | 免费 |  Online  |

### 物理编辑工具

|    工具名     |                          下载地址                          | 授权 |  支持平台   |
| :-----------: | :--------------------------------------------------------: | :--: | :---------: |
| PhysicsBench  | [进入官网](https://sourceforge.net/projects/physicsbench/) | 免费 | Windows/Mac |
| PhysicsEditor |    [进入官网](https://www.codeandweb.com/physicseditor)    | 付费 | Windows/Mac |
| VertexHelper  |  [进入官网](https://github.com/jfahrenkrug/VertexHelper)   | 开源 |     Mac     |

### 场景编辑工具

|    工具名     |                      下载地址                       | 授权 |  支持平台   |
| :-----------: | :-------------------------------------------------: | :--: | :---------: |
| CocosBuilder  | [进入官网](https://github.com/cocos2d/CocosBuilder) | 开源 |     Mac     |
| SpriteBuilder |      [进入官网](http://www.spritebuilder.com/)      | 开源 |     Mac     |
|   Cocoshop    |   [进入官网](https://github.com/andrew0/cocoshop)   | 开源 |     Mac     |
|  LevelHelper  |      [进入官网](http://www.gamedevhelper.com/)      | 付费 |     Mac     |
|   FairyGUI    |        [进入官网](http://www.fairygui.com/)         | 开源 | Windows/Mac |

### 纹理图集工具

|       工具名        |                       下载地址                       |   授权    |  支持平台   |
| :-----------------: | :--------------------------------------------------: | :-------: | :---------: |
| DarkFunction Editor |     [进入官网](http://darkfunction.com/editor/)      |   免费    | Windows/Mac |
|    TexturePacker    | [进入官网](https://www.codeandweb.com/texturepacker) |   付费    | Windows/Mac |
|       Zwoptex       |       [进入官网](https://zwopple.com/zwoptex/)       | 免费/付费 |     Mac     |
|      SpriteUV       |         [进入官网](http://www.spriteuv.com/)         |   免费    |   Windows   |
|       TinyPNG       |           [进入官网](https://tinypng.com/)           | 免费/付费 |   Online    |

### 瓦片地图编辑工具

|      工具名      |               下载地址                | 授权 |  支持平台   |
| :--------------: | :-----------------------------------: | :--: | :---------: |
|    iTileMaps     |  [进入官网](https://www.klemix.com/)  | 免费 |     iOS     |
| Tiled Map Editor | [进入官网](http://www.mapeditor.org/) | 开源 | Windows/Mac |

### 声音特效编辑工具

|    工具名    |                        下载地址                        | 授权 |      支持平台      |
| :----------: | :----------------------------------------------------: | :--: | :----------------: |
|     cfxr     |       [进入官网](http://thirdcog.eu/apps/cfxr/)        | 开源 |        Mac         |
|     bfxr     |            [进入官网](http://www.bfxr.net/)            | 免费 | Windows/Mac/Online |
|   Labchirp   | [进入官网](http://labbed.net/software.php?id=labchirp) | 免费 |      Windows       |
| Sound Studio |           [进入官网](http://felttip.com/ss/)           | 免费 |        Mac         |

### 背景音乐编辑工具

|   工具名   |                      下载地址                       | 授权 |  支持平台   |
| :--------: | :-------------------------------------------------: | :--: | :---------: |
| GarageBand | [进入官网](http://www.apple.com/cn/mac/garageband/) | 付费 |     Mac     |
|   Reaper   |      [进入官网](http://www.cockos.com/reaper/)      | 付费 | Windows/Mac |
|   Ardour   |           [进入官网](http://ardour.org/)            | 免费 | Windows/Mac |

### GIF 动画帧导出工具

|      工具名      |                    下载地址                     | 授权 |  支持平台   |
| :--------------: | :---------------------------------------------: | :--: | :---------: |
| UleadGifAnimator | [进入官网](http://www.crsky.com/soft/4010.html) | 免费 |   Windows   |
|     ShoeBox      |    [进入官网](http://renderhjs.net/shoebox/)    | 免费 | Windows/Mac |

### 骨骼动画编辑工具

|   工具名    |                  下载地址                   | 授权 |  支持平台   |
| :---------: | :-----------------------------------------: | :--: | :---------: |
|    Spine    | [进入官网](http://zh.esotericsoftware.com/) | 收费 | Windows/Mac |
| Dragonbones |  [进入官网](http://dragonbones.github.io/)  | 开源 | Windows/Mac |
|   Spriter   |   [进入官网](http://www.brashmonkey.com/)   | 付费 | Windows/Mac |

### 3D 模型工具

|    工具名     |                                              下载地址                                               | 授权 |  支持平台   |
| :-----------: | :-------------------------------------------------------------------------------------------------: | :--: | :---------: |
| FBX-Converter | [进入官网](https://www.autodesk.com/developer-network/platform-technologies/fbx-converter-archives) | 免费 | Windows/Mac |

### 体素编辑工具

|   工具名    |                   下载地址                    | 授权 |  支持平台   |
| :---------: | :-------------------------------------------: | :--: | :---------: |
| MagicaVoxel |    [进入官网](https://ephtracy.github.io/)    | 免费 | Windows/Mac |
|   QUBICLE   | [进入官网](http://www.minddesk.com/index.php) | 付费 | Windows/Mac |
|  VoxelShop  |   [进入官网](https://blackflux.com/node/11)   | 免费 | Windows/Mac |

更新时间：2020-04-23 14:19:13

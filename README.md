# 基于 TSDX 脚手架 进行 React Component 开发

## 环境要求

NodeJs 18.x

## 开发方法

1、 进入根目录，安装依赖 `npm i` 或者 `yarn`

2、 启动组件开发服务，`npm start` 此时，组件打包服务启动，会监听 src 目录下的文件，自动打包到 dist 目录

3、 组件打包基于 rollup 打包，tsdx.config.js 文件覆盖了少量 rollup 配置

## 本地调试

1、 进入 example 目录， 安装依赖 `npm i` 或者 `yarn`

2、 启动组件开发服务，`npm start` 会启动一个标准的 react 开发服务器，支持文件热更新

3、 开发服务基于 parcel 包括 index.tsx 中的 `../.` 目录指向到 外层的 dist/index.js 目录 使用的就是 parcel 的 [aliasing](https://github.com/jaredpalmer/tsdx/pull/88/files)

## 参考文档

[https://juejin.cn/post/6844904162497757192](https://juejin.cn/post/6844904162497757192)

## 案例

# deno-base

> 参考[Deno 运行时入门教程：Node.js 的替代品](http://www.ruanyifeng.com/blog/2020/01/deno-intro.html)

> deno 是 node 的替代品，支持 Typescript，会使用 tsc 引擎转为 js，再使用 v8 引擎运行 js

## 安装

> 因为官网比较难下载，故保存至 exe

### 可执行文件安装

> 将可执行文件放至 C:\Program Files\deno\ 并添加环境变量（环境变量 =》系统变量 =》path =》 添加 C:\Program Files\deno\ ）


### 运行

* 查看版本
    ~~~
    deno --version
    ~~~

* 运行
    ~~~
    deno run test.ts
    deno run test.js
    ~~~


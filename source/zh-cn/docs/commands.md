---
title: 命令
---

## create

```bash
$ doric create [ProjectName]
```

新建一个Doric项目，项目名为`ProjectName`。

## dev

```bash
$ doric dev
```
开始开发Doric页面，此时终端会输出二维码。可通过[Doric Playground]()扫码查看页面效果

## build

```bash
$ doric build
```

进行代码打包，此时输出JS bundle文件至 `bundle` 目录下。 

## clean

```bash
$ doric clean
```

清理编译缓存文件。此时会删除`build`和`bundle`文件夹中内容
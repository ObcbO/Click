# CLICK

## 简介

这是一款带有 设置最大值最小值 改变点击频率概率 的防检测连点器
代码可能有些繁琐，欢迎给出意见

## 如何使用？

你可以使用 `java -jar click.jar`来使用此软件
也可以使用 启动参数 来启动软件(见下)

## 启动参数

- `-Dmax=`: 最大值 单位:ms 要求: ≠0 >0
- `-Dmin=`: 最小值 单位:ms 要求: ≠0 >0
- `-Dp=`: 改变间隔ms的概率 单位:% 要求:>0 <=100

只有3个参数都输入才运行后就开始连点, 否则就只是填写已输入参数

> 例子: `java -Dmax=20 -Dmin=10 -jar click.jar` 会帮你填写max和min的值
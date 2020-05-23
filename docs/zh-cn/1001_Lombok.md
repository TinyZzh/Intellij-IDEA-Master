# 1. Lombok插件

Lombok是一个可以通过简单的注解的形式来帮助开发者简化消除一些必须有但显得很臃肿的Java代码的工具。支持主流的Java IDE（例如：Intellij IDEA、Eclipse等）

<div align="center"><img src="./images/1001/1.png" alt="图1"/></div>

## 1.1. Intellij IDEA Plugin

Intellij IDEA Plugin **[下载地址](https://plugins.jetbrains.com/plugin/6317-lombok)**

Lombok本身是在Java标准允许范围内的编译扩展工具。让开发者从Getter、Setter等`臃肿`代码中解脱出来。各平台各IDE的支持，经过多年的发展和修复，已经基本可用。

* 个人或内部项目**推荐**使用。
* 开源项目**不推荐**使用 [<sup>1</sup>](#refer-anchar-1)。

> 至`Kotlin 1.4`和`Lombok 1.18.12`版本为止，两者仍存在兼容问题。

## 1.2. 设置并启用`Lombok`

### 1.2.1. 项目启用`Annotation Processors`特性

<div align="center"><img src="./images/1001/3.png" alt="图1"/></div>

### 1.2.2. `Lombok`插件参数配置

<div align="center"><img src="./images/1001/2.png" alt="图1"/></div>

## 1.3. 引用

* [Lombok](https://projectlombok.org/)
* [Lombok特性](https://projectlombok.org/features/all)
* [Github](https://github.com/mplushnikov/lombok-intellij-plugin)

---
<div id="refer-anchar-1"></div>
[1] 虽然目前有不少开源项目使用Lombok。但是仁者见仁智者见智，求同存异。
<!--
 * @Author: your name
 * @Date: 2021-08-14 16:11:40
 * @LastEditTime: 2021-08-14 20:11:26
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /animation/README.md
-->
# animation
动画相关

# 搭建项目
组件库  ant-design【react】  vant /element 【vue】

1. 初始化
npm init -y    ==>package.json

2. 安装webpack webpack-cli
【webpack-cli 是执行 webpack 的工具。webpack 4.x 版本以后，剥离出了 webpack-cli ，所以这里我们需要单独下载它。】

yarn add webpack webpack-cli -D    ===》生成node_moudles和安装webpack/webpack-cli


https://juejin.cn/post/6844903891981565959

3. 新建目录
根目录添加如下
docs                 文档相关
examples              页面内容示例
src                   存放入口文件以及各种辅助文件。
scripts文件夹          打包工具的配置文件
index.html
test                  存放单元测试文件，合格的单元测试也是一个成熟的开源项目必备的。
type                 存放声明文件，方便引入 typescript 写的项目中，需要在 package.json
                    中指定 typing 字段的值为 声明的入口文件才能生效

.travis.yml         持续集成（CI）的配置文件，它的作用就是在代码提交时，根据该文件执行对应脚本，成熟的开源项目必备之一。
logo.svg           ElementUI 的图标，使用了 svg 格式，合理使用 svg 文件，可以大大减少图片大小。
LICENSE            开源许可证，ElementUI 使用的是 MIT 协议，使用 ElementUI 进行二次开发的开发者建议注意该文件
Makefile           在 .github 文件夹下的贡献指南中提到过，组件开发规范中的第一条：通过 make new 创建组件目录结构，
                   包含测试代码、入口文件、文档。其中 make new 就是 make 命令中的一种。make 命令是一个工程化编译工具，而 Makefile 定义了一系列的规则来制定文件变异操作，常常使用 Linux 的同学应该不会对 Makefile 感到陌生。

4.代码规范

遵循饿了么前端的 [ESLint](https://github.com/ElemeFE/eslint-config-elemefe) 即可



-- 生成hmtl模板
-- 删除上一次的dist文件
-- 自动添加浏览器前缀
-- 使用sass预编译器
-- 转换ES6,7,8,9语法为ES5
-- 大于10k文件打包到dist，小于10k转换为base64
-- 兼容vue-- 拷贝静态文件
-- 热更新
-- 区分当前环境
-- 多线程打包
-- 缓存未改变模块
-- g-zip压缩
-- 获取本机ip
-- 打包大小分析
-- 压缩css
-- 检查端口是否存在




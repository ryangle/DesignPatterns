# 设计模式 Design Patterns

使用面向对象的方式开发软件时，设计模式是非常重要的。用好了他，就能够实现最重要的两个目标：高内聚（Cohesion），低耦合（Coupling）。

本项目采用`.NET Interactive Notebooks`编写，示例代码在.Net 6中完成测试。

## 享用方法

1. 安装[vscode](https://code.visualstudio.com/)
2. 打开vscode，安装C#插件
3. 安装```.NET Interactive Notebooks```插件
4. `git clone https://github.com/ryangle/DesignPatterns.git`
5. 在DesignPatterns目录下执行命令```code .```即可打开vscode
6. 开始一边阅读一边调试，愉快的享用吧。

## 模式的分类

1. 创建型模式（Creating Pattern）

   * 简单工厂、工厂模式
   * 抽象工厂模式
   * 单例模式
   * 建造者模式
   * 原型模式
   
2. 结构模式（Structural Pattern）

   * 适配器模式
   * 合成模式
   * 装饰模式
   * 代理模式
   * 享元模式
   * 门面模式
   * 桥梁模式

3. 行为模式（Behavioral Pattern）

   * 责任链模式
   * 命令模式
   * 解释器模式
   * 迭代器模式
   * 中介模式
   * 备忘录模式
   * 观察者模式
   * 状态模式
   * 策略模式
   * 模板方法模式
   * 访问者模式


## 关于.NET Interactive Notebooks

1. 使用环境：vs code，安装C#、.NET Interactive Notebooks插件
2. 创建文档：命令->输入notebook->.NET Interactive:Create new blank notebook->Create as .ipynb->C#
3. 两种存储格式：ipynb存储为json格式的文本，dib存储为类似markdown格式的文本。ipynb可以在github上执行，目前dib的还不行。
4. C#代码中有默认引用的包和默认使用的命名空间
5. 如何引用Nuget包，使用Magic Command：#! #r
6. 其他常用Magic Command: #!who #!whos #!html #!about  #!share #!value 等等
7. 如何自定义Magic Command
8. 更多好玩功能

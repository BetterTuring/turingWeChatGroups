# 《你不知道的 JavaScript（上卷）》 阅读计划

__—— 图灵前端技术群阅读计划（第1期）__

<br>

##### 领读人：Faremax

##### 答疑时间安排：每周五 20:00—22:00

##### 计划阅读总时长：一个月

##### 每天阅读用时：2.5小时

##### 本书特色

- 本书内容包括两大部分：作用域和闭包（共5章）、this 和对象原型（共6章）
- 深入作用域和闭包的每个细节，详细解释其实现原理
- 你可以一次性学习 ES5 和 ES6 相关语法，对比学习，加深理解

##### 适合读者

- 了解 JavaScript 基础（变量、运算符、语句），想继续提高 JavaScript 技能的你
- 具有 JavaScript 使用经验，想深入学习 JavaScript 细节的你
- 具有前端开发经验，想让 JavaScript 编码技能融会贯通的你

###### 图灵社区本书网址：<a href="http://www.ituring.com.cn/book/1488">http://www.ituring.com.cn/book/1488</a>
###### 图灵阅读计划网址：<a href="https://github.com/BetterTuring/turingWeChatGroups">https://github.com/BetterTuring/turingWeChatGroups</a>

<br>

### 阅读建议

<div style="margin-top:10px"></div>

本群里可能有基础相对弱的朋友，希望大家可以多做练习，不要怯于提问。希望大牛们也能对新人简单的问题不吝赐教。阅读图书、共同进步是我们建立群的初心，和谐的阅读氛围靠大家共同建设。

### 相关资源

<div style="margin-top:10px"></div>

本书第一部分：[作用域和闭包](https://github.com/getify/You-Dont-Know-JS/tree/1ed-zh-CN/scope%20%26%20closures)  
本书第二部分：[this 和对象原型](https://github.com/getify/You-Dont-Know-JS/tree/1ed-zh-CN/this%20%26%20object%20prototypes)

ES6 转码: [babel](https://babeljs.io/)  
MDN 手册: [MDN](https://developer.mozilla.org/zh-CN/)  
ECMAScript8.0: [ECMAScript8.0](http://www.ecma-international.org/ecma-262/8.0/)

<br>

## 阅读规划

<div style="margin-top:15px"></div>

本书篇幅比较短，对于基础较好/时间较多的朋友一周读完都是有可能的。但我希望大家可以用一个月精读这本好书，通过对本书的阅读和我们的讨论真正地理解、掌握 JavaScript 的原理。也希望前端新人可以努力一下，跟上大牛的步伐。

### 第一部分 作用域和闭包（包括附录A—D）

<div style="margin-top:10px"></div>

#####  计划时长：2周

#### 重点内容

1. 作用域基本概念和原理  
什么是作用域，作用域的作用，以及 JavaScript 的作用域的特点
2. 词法作用域  
理解什么是词法作用域，词法作用域的特征
3. 函数作用域和块作用域  
函数作用域是什么，块作用域如何向下兼容
4. 变量提升  
变量提升的意义和特点，哪些申明具有提升的特性，会导致出现什么问题
5. 闭包  
闭包的什么，有什么好处和坏处，如何合理地使用闭包

#### 难点内容

1. 理解作用域和作用域链
2. 注意区分 ES5 和 ES6 语法
3. 充分掌握闭包的意义

### 第二部分 this和对象原型（包括附录A）

<div style="margin-top:10px"></div>

##### 计划时长：2周

#### 重点内容

1. 对象  
包括对象的定义方式，对象的属性和方法，Object静态方法，对象的特性（可扩展性、密封性、冻结性）和属性的特性（可枚举性、可写性、可配置性）
2. this 对象  
this 的意义，this 动态改变
3. 类  
该部分属于 ES6 语法，理解类定义方式和继承方式
4. 原型  
原型和原型链的关系，对象继承的各种方式及其特点
5. 行为委托  
委托理论及控件类的意义，以及使用方式

#### 难点内容

1. 理解原型链和继承的关系
2. 区分多种继承方式及其特点

#### 补充

- 可以实现 `_instanceof()` 或 `_new()` 函数简单实现 instanceof 或 new 关键字的功能
- 试比较作用域链和原型链，找出它们之间的异同





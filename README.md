[TOC]
# 前端开发手册（完善中）
## 一、编程规约
### （一）命名风格
1. 【强制】代码命名严禁使用拼音或英文拼音混合方式，更不允许直接使用中文命名，惯例词除外。 
2. 【强制】类名使用 UpperCamelCase 风格，遵守驼峰形式。
3. 【强制】方法名、参数名、成员变量、局部变量使用 lowerCamelCase 风格，遵守驼峰形式。
4. 【强制】常量命名统一使用全部大写，原本驼峰处（单词间隔处）使用下划线隔开，力求语义表达完整。
5. 【强制】React 组件文件、对应 less、sass 文件以及外层的文件夹，统一使用 UpperCamelCase 风格，遵守驼峰形式。
6. 【强制】
7. 【强制】
8. 【强制】杜绝不规范、不通用的缩写。
9. 【强制】非类文件的直接文件夹名称，统一全部使用小写。
10. 【强制】如果使用了设计模式，在文件名以及类名上体现出设计模式，如 RequestProxy，HumanFactory。
11. 【强制】如果使用专门文件定义了枚举对象或者常量对象，在文件命名或者 export 出来的对象命名上予以体现，如 KeyBindEnum，ErrorCodeConstants。


### （二）常量定义
1. 【强制】如果当前环境支持 let、const，则不允许使用 var 定义变量。
2. 【强制】禁止使用魔法值，统一使用有语义的常量来代替。
3. 【强制】如果有常量类型的枚举，事先定义枚举对象，并在对象中罗列出所有的枚举常量细类。
4. 【强制】不要在一个常量文件里面维护所有的常量，不同类别常量进行区分，如 ErrorCodeConstants，StatusCodeConstants。
5. 

### （三）控制语句
1. 【强制】

### （四）注释规约
### （五）代码风格
1. 【强制】类文件使用 ES6 风格来定义 class，并添加内部方法，禁止使用 function. prototype 来添加原型方法。
2. 【强制】

### （六）其他

## 二、异常处理
## 三、数据打点
## 四、工程架构


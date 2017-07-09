# Markdown学习 
[TOC]

![来自有道云笔记](http://note.youdao.com/favicon.ico)

[简明教程](http://note.youdao.com/iyoudao/?p=2411)

[进阶教程](http://note.youdao.com/iyoudao/?p=2445)

[mermaid 画图](http://knsv.github.io/mermaid/)

[mermaid 在线编辑器](http://knsv.github.io/mermaid/live_editor/)

***

# - 基础：
## 字体:
***这是粗斜体***

**这是粗体**

*这是斜体*


## 高亮:
~~~c
    if else malloc
~~~
~~~python
print "sss"
import io
try catch
def asdf
~~~

## 引用:
> **这是一个引用。** — QT

## 标题:
# 一级标题 
## 二级标题
#### …………
###### 六级标题 

## 列表:
- 无序
- 列表

1. 有序
2. 列表

## 清单:
- [ ] **清单1**
  - [ ] 事项1
  - [ ] 未完成
- [x] **已完成**

## 表格:
| 时间 | 地点 | 人物 |
| :--- | ---: | :--: |
|早    | 家   | 小明 |
|午    | 学校 | 小王 |
|晚    | 餐厅 | 小红 |


## 公式:
```math
E = mc^2

a^2 + b^2 + 2ab = ( a+b)^2
```

***
# - 进阶:
## 流程图:
[**点此进入详细语法**](http://knsv.github.io/mermaid/#flowcharts-basic-syntax)
```
graph TD
A[Christmas] --> B(Go shopping)
B --> C{Let me think}
C --> |One| D[Laptop]
C --> |Two| E[iPhone]
C --> |Three| F[Car]
G(Money) --> C
```
## 序列图:
```
sequenceDiagram
    loop every day
        Alice->>John: Hello John, how are you ?
        John-->>Alice:Great!
        end
```

## 甘特图:
[**点此进入详细语法**](http://knsv.github.io/mermaid/#styling39)
```
gantt
dateFormat YYYY-MM-DD
title 产品计划表
section 初期阶段
明确需求: 2017-06-26,10d
section 中期阶段
跟进开发: 2017-07-06,15d
section 后期阶段
走查测试: 2017-07-16,9d
```
---
marp: true
theme: NKU-Beamer
paginate: true
size: 4:3
header: 学号：1000000
footer: 南开大学数学科学学院
title: Marp custom themes
math: mathjax
---
<!-- _class: title -->

# NKU-Beamer 主题

<br/>

## 基于 Beam 主题的实现
报告人：XXX
学号：1000000


![NKU校徽](./NKU_Symbol.png)


---
<!--_class: contents-->
# 目录


1. 关于该模板的说明 
2. 基本语法
3. CSS更改说明
4. 参考文献
---

# 模板基本说明
该模板改编自 Marp 社区的 Beam 主题，感谢原作者的辛勤付出，相较于原版主题该主题改动如下：

- 主题色改为 NKU 相关的颜色主题，例如经典的南开紫；
- 新增目录页 `contents` ，并定制为有序列表方案；
- 新增致谢页 `final` ，为简洁起见仅更改二级标题。若二级标题使用字体 `Edwardian Script ITC` 在你的设备上没有，可以直接在CSS文件中更改；
- 字体增加中文字体；
- 底部栏更改颜色及内容；




---
# 基本语法
# 一级标题
## 二级标题
### 三级标题

```python
# python代码
import numpy as np
print('hello world!')

```

> 你可以在这里引用一些内容——不是鲁迅说的

> 天地之功不可仓卒，艰难之功当累日月。——《国语》


----
# 基本语法
1. 有序列表

- 无序列表

#### 表格

|内容|说明|
|:---:|:---:|
|你好|再见|

#### 公式
$$
\int_a^b f(x)\mathrm{d}x = F(b)-F(a)
$$


---
<!-- _class: tinytext -->
# 参考文献

-  `<!-- _class: tinytext -->` 未改动，用于撰写参考文献的内容；

- 目前没有类似 BibTeX 这样的引用方式，建议还是直接手敲。

[1] 作者，期刊，篇目名，日期


----

<!---_class: final--->
## Thanks

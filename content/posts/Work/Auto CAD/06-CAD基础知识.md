---
title: "Auto CAD - 基础知识介绍"
subtitle: ""
date: 2021-12-01T20:15:26+08:00
lastmod: 2021-12-01T20:15:26+08:00
author: "守正"
slug: "cad_basics"
tags: ["Auto CAD"]
categories: ["Work"]
featuredImage: 'https://cdn.chiga.ga/Posts/Work/AutoCAD/06_CAD_basics/Cover.jpg'
---

本文为`Auto CAD`的入门知识，包括快捷命令的使用，以及需要注意的一些准则；

<!--more-->

将本文的知识点得以应用，熟练掌握，提升一定是来源于不断的练习，熟能生巧，然后再进阶学习[Auto CAD - 使用技巧和疑难杂症解决办法](/possts/cad-skills-problem)。

## 命令大全

### 绘图命令
|名称|快捷命令|完整命令|
|:--:|:--:|:--:|
|直线|L|LINE|
|构造线|XL|XLINE|
|多段线|	PL|PLINE|
|矩形|REC|RECTANG|
|正多边形|POL|POLYGON|
|圆|C|CIRCLE|
|修订云线|REVC|REVCLOUD|
|样条曲线|SPL|SPLINE|
|椭圆|EL|ELLIPSE|
|创建块|B|BLOCK|
|编辑块|BE|BEDIT|
|图案填充|H|HATCH|
|编辑填充|HE|HATCHEDIT|
|单行文字|DT|TEXT|
|多行文字|T|MTEXT|
|多行线|ML|MLINE|
|定数等分|DIV|DIVIDE|
|定距等分|ME|MEASURE|
|创建边界|BO|BOUNDARY|

### 修改命令

|名称|快捷命令|完整命令|
|:--:|:--:|:--:|
|删除|E|ERASE|
|移动|M|MOVE|
|复制|CO|COPY|
|镜像|MI|MIRROR|
|偏移|O|OFFSET|
|旋转|RO|ROTATE|
|缩放|SC|SCALE|
|拉伸|S|STRETCH|
|修剪|TR|TRIM|
|延伸|EX|EXTEND|
|打断|BR|BREAK|
|圆角|F|FILLET|
|分解|X|EXPLODE|
|格式刷|MA|MATCHPROP|
|对齐|AL|ALIGN|
|图层管理|LA|LAYER|

### 标注命令

|名称|快捷命令|完整命令|
|:--:|:--:|:--:|
|线性标注|DLI|DIMLINEAR|
|对齐标注|DAL|DIMALIGNED|
|弧长标注|DAR|DIMARC|
|角度标注|DAN|DIMANGULAR|
|半径标注|DRA|DIMRADIUS|
|直径标注|DDI|DIMDIAMETER|
|引线标注|LE|QLEADER|
|快速标注|QDIM||
|重新关联|DRE|DIMREASSOCIATE|
|解除关联|DRE->D|DIMDISASSOCIATE|

### 样式命令

|名称|快捷命令|完整命令|
|:--:|:--:|:--:|
|文字样式|ST|STYLE|
|标注样式|D|DIMSTYLE|

### 视图命令

|名称|快捷命令|完整命令|
|:--:|:--:|:--:|
|抓手（平移）|P|PAN|
|局部放大|Z|ZOOM|
|显示全图|Z+E|ZOOM|

### 查询命令

|名称|快捷命令|完整命令|
|:--:|:--:|:--:|
|面积测量|AA|AREA|
|距离测量|DI|DIST|
|显示特性数据|LI|LIST|
|快速选择|QSE|QSELECT|



## 常用命令操作

### 直线

- **命令：** `LINE`
- **快捷命令：** `L`
- **操作方法：** 输入`L` --> 空格 --> 指定第一个点 --> 指定下一个点 --> 空格完成，当然你也可以无休止的画下去。
- **提示：** 每条线是独立的；

### 多段线

- **命令：** `PLINE`
- **快捷命令：** `PL`
- **操作方法：** 输入`PL` --> 空格 --> 指定起点 --> 指定下一个点 --> …… --> 空格完成，当然你也可以无休止的画下去。
- **提示：** 所画的线条是连成一个整体。

### 矩形

- **命令：** `RECTANG`
- **快捷命令：** `REC`
- **操作方法一：** 输入`REC` --> 空格 --> 指定第一个角点 --> 指定另一个角点 --> 空格完成。
- **操作方法二：** 输入`REC` --> 空格 --> 指定第一个角点 --> 输入`D` --> 空格 --> 输入横向长度 --> 空格 --> 输入纵向长度 --> 空格完成。

### 圆

- **命令：** `CIRCLE`
- **快捷命令：** `C`
- **操作方法：** 输入`C` --> 空格 --> 点一点 --> 输入直径 --> 空格或者拉鼠标，点左键确定。

### 复制

- **命令：** `COPY`
- **快捷命令：** `CO` / `CP`
- **操作方法：** 输入`CO` 或 `CP` --> 空格 --> 选择物体 --> 空格 --> 选择基准点 --> 选择要复制到什么地方 --> 空格结束。

### 移动

- **命令：** `MOVE`
- **快捷命令：** `M`
- **操作方法：** 输入`M` --> 空格 --> 选择物体 --> 空格 --> 选择基准点 --> 选择要移动到什么地方 --> 空格结束。

### 偏移

- **命令：** `OFFSET`
- **快捷命令：** `O`
- **操作方法：** 输入`O` --> 空格 --> 输入偏移的距离 --> 空格 --> 选择要偏移的物体 --> 在要偏移的方向上点鼠标。

### 格式刷

- **命令：** `MATCHPROP`
- **快捷命令：** `MA`
- **操作方法：** 输入`MA` --> 空格 --> 选择基准图形 --> 选择被刷的图形。

### 查看属性

- **命令：** `PROPERTIES`
- **快捷命令：** `MO` / `PR` / `CRTL + 1`
- **操作方法：** 输入`mo` --> 选择物体。

### 阵列

- **命令：** `ARRAY`
- **快捷命令：** `AR`
- **操作方法：** 输入`AR` --> 空格 --> 出现对话框。

### 延长

- **命令：** `EXTEND`
- **快捷命令：** `EX`
- **操作方法一：** 输入`EX` --> 空格 --> 选择需要延长的线；
- **操作方法二：** 输入`EX` --> 空格 --> 选择延长的截止线 --> 空格 --> 选择需要延长的线；
- **小技巧：** 输入`EX` --> 空格 --> 按住`shift`变成剪切功能，可以灵活运用；

### 剪切

- **命令：** `TRIM`
- **快捷命令：** `TR`
- **操作方法一：** 输入`TR` --> 空格 --> 选择需要剪切的线；
- **操作方法二：** 输入`TR` --> 空格 --> 选择剪切的截止线 --> 空格 --> 选择需要剪切的线；
- **小技巧：** 输入`TR` --> 空格 --> 按住`shift`变成延长功能，可以灵活运用；

### 删除

- **命令：** `ERASE`
- **快捷命令：** `E`
- **快捷命令：** `Delete`
- **操作方法：** 输入`E` --> 空格 --> 选择图形 --> 空格。

### 后退

- **命令：** `U`
- **快捷命令：** `CTRL + Z`
- **操作方法：** 输入`U` --> 空格。只要`CAD`没关过，可以一直反悔到打开图纸时的状态

### 炸开

- **命令：** `EXPLODE`
- **快捷命令：** `X`
- **操作方法：** 输入`X` --> 空格 --> 选择物体。

### 拉伸

- **命令：** `STRETCH`
- **快捷命令：** `S`
- **操作方法：** 输入`S` --> 用右下往左上的方式拉出一个框让左边的竖线或者上边的横线与被拉部分相交，空格 --> 选择一个基本点，输入距离或者指定下一点。

### 镜像

- **命令：** `MIRROR`
- **快捷命令：** `MI`
- **操作方法：**  输入`MI` 选择要镜像的物体，选择「镜子」的第一点，选择「镜子」的第二点，空格，得到了一个以你选择的两点为对称轴的图像。

通常是垂直或水平方向镜像，左右镜像则「第一点」与「第二点」为上下关系，上下镜像则「第一点」与「第二点」为左右关系；

## 制图习惯以及技巧

### 经常存盘

记了那么多快捷命令后，在正式开始画图前，还得牢记并运用最重要的一个快捷键`CTRL + S`；

突然断电、死机或者是`CAD`的“温馨提示”：**发生致命错误**；在崩溃的同时还会让你的作品及灵感消失得无影无踪；

在`AutoCAD`中，我们也可以让`CAD`自动存盘：点击「工具」--> 「选项」，出现「选项」对话框，进入「文件」选项卡，设置「自动保存路径」，然后在「打开和保存」选项卡里设置「自动保存」及保存时间间隔。

{{< admonition type=warning title=注意 open=true >}}
不要把时间间隔设得太短，保存的时候会卡顿，频繁保存容易影响操作，一般设10分钟就可以了，重点是养成随手按`CTRL + S`的好习惯，当操作完一步停下来思考的时候下意识就按一下`CTRL + S`。
{{< /admonition >}}

### 多看提示

`AutoCAD`软件是一套比较人性化的软件，每一步操作都会有提示指导;

就算某个命令你原来从未使用过，只要根据提示一步一步做下去，也能完成操作;

`AutoCAD`软件的提示行区域高度，一般要两到三行，这样就能完全看到每一步的提示;

多看提示的好处：可以学习从未用过的命令，学习同一命令的多种用法。

### 巧用快捷命令

`AutoCAD`有很多方便我们使用的快捷方法，且同一个命令往往又有好几种使用方式，如点击菜单、点击工具图标、输入键盘命令、回车、空格键重复命令等方式；

对于快捷命令切记不用死记硬背，应当是在使用的过程中，一步一步加强，形成惯性思维，达到想要操作某个命令的时候，手下意识就按出快捷命令，且只需要记住一些常用的快捷命令就行，不经常用到的即便是通过点击图标或者通过菜单来操作也不会有太大影响；

{{< admonition type=tip title=提示 open=true >}}
掌握快捷命令有一个简便方法，就是在点击菜单或图标时，命令行都会出现该命令的完整命令，如果命令行显示不完整，可以通过按`F2`打开命令窗口查看，然后就可以试着输入完整命令的前一至两个字母，一般那就是该命令的缩写。
{{< /admonition >}}


### 良好习惯

1. 尽量多使用多段线(`PLINE`)作图而少用直线(`LINE`)，因为多段线是一个整体，在以后选择或二次修改时会更加方便；
2. 尽量使用单行文字而不是多行文字，单行文字易于修改内容和格式刷操作等；
3. 用好图层(`LAYER`)功能，把不同类型的图形分配到不同的图层中，以便以后分类整理，特别是用到布局出图，图层是重点；
4. 在创建新图块的时候，请将图形对象置于`0`图层，颜色`bylock`，这样后面想要修改图块的图层颜色等参数直接选中设置即可，不用`BE`命令，进入到块编辑器操作；
5. 灵活运用块定义(`BLOCK`)功能，在二次选择或者修改的时候会更加轻松，选择的时候一次就可以选中整个图形，避免了漏选，在编辑的时候，用`BE`命令，进入到块编辑器，修改保存后所有位置同一个块都被修改了，提高效率；
6. 常用的作图界限、尺寸、标注样式、文字样式等要做好模板，以便快速调用，规范作图；
7. 不要炸开！不要炸开！不要炸开！(`EXPLODE`)填充样式、标注等；
8. 除必须情况外，请不要分解（炸开）图块；
9. 尽量不要使用奇奇怪怪的字体，过于花哨很影响出图的美观，且传输至其他电脑里时容易产生乱码；
10. 模型空间只用来作图，布局空间放置图框，设置标注等排版出图用；
11. 熟悉各种快捷命令，左手不离键盘，右手不离鼠标。

### 精确作图

1. 在模型空间严格按`1:1`作图，在布局空间根据出图规格调整合适比例；
2. 灵活运用点捕捉功能，不要以为自己眼力过人，随便一点就能点中直线的端点，那是不可能的。
3. 该横平竖直的线就得保证平顺，该闭合的线一定要用命令闭合(`CLOSE`)，该相交的点必须用捕捉功能相交，而不是凭感觉；
4. 对于已知的长度，我们可以用键盘直接输入，保证画的线等图形尺寸为整数，禁止凭感觉拖，全是小数点。
5. 灵活运用正交模式（`F3`）与捕捉模式（`F8`）。

{{< admonition type=tip title=提示 open=true >}}
在作图过程中按下`shift`键可以临时切换正交模式的开启与关闭；

**注意：** 按住`shift`的时候不要滑动鼠标的滚轮；
{{< /admonition >}}

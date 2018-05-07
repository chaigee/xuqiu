# 1.引言

## **1.1目的**

为明确软件需求、规划项目、确认进度、组织软件开发并测试而撰写本文档。同时，详细分析项目总体需求，可以作为软件开发工作的基础和依据以及确认测试和验收的依据。

## **1.2背景**

本次待开发的软件为备忘录app，由爱叫什么叫什么队团队提出并开发。

## **1.3参考资料**

1、邹欣.构建之法[M].第三版.人民邮电出版社,2017

# 2.项目概述

## **2.1产品描述**

我们团队的项目是备忘录app，简单而又实用的日常生活软件，目标是解决用户多忘事的烦恼。用户可以通过备忘录app提前分配任务至具体时间段，提醒用户及时完成任务以防用户丢三落四，同时可以利用便签功能随时作笔记。最后，根据用户的软件使用记录生成一系列的总结表，让用户更直观地了解自己近段时间的备忘与任务情况。

## **2.2产品功能**

本产品主要有以下功能，随着版本更新，功能可能会有增删。

- 便签。简单地分类笔记
- 将要备忘的事务转换成任务并可分配到具体时间进行提醒
- 结算一段时间内的任务，获得任务完成记录
- 将记录总结成图表形式，直观了解备忘记录完成情况

## **2.3用户场景**

根据需求定义如下典型用户与典型场景：

**1.** 阿兵——学渣

| **名字** | **阿兵** |
| --- | --- |
| 性别、年龄 | 男、18 |
| 身份 | 大一学生 |
| 生活/工作情况 | 目前成绩不太理想 |
| 用户偏好 | 咸鱼，打游戏 |
| 典型场景 | 老师布置的作业在同学没有提醒的情况下经常忘记完成 |
| 典型描述 | 平时分？不存在的，都已经被扣光了。 |

**2.** 阿升——学霸

| **名字** | **阿升** |
| --- | --- |
| 性别、年龄 | 男、20 |
| 身份 | 大三学生 |
| 生活/工作情况 | 成绩优异，准备考研 |
| 用户偏好 | 看书，泡图书馆 |
| 典型场景 | 专注泡馆而忘记时间导致失约（冷落了女朋友） |
| 典型描述 | 咕咕咕，我是没有感情的鸽子。 |

**3.** 阿庆——上班族

| **名字** | **阿庆** |
| --- | --- |
| 性别、年龄 | 女、22 |
| 身份 | 白领 |
| 生活/工作情况 | 有车有房，单身 |
| 用户偏好 | 上网，交友 |
| 典型场景 | 老板给的工作量太多啦，一时半会不能全部完成 |
| 典型描述 | 何时才能停止无止境地加班 |

## **2.4一般约束**

**1.** 开发环境约束：

- 开发工具：Hbuilder
- 开发语言：HTML5+CSS+JavaScript
- 开发测试浏览器：Google chrome

**2.** 时间约束：开发周期短，两个月的开发时间需要开发者合理规划时间，做到多项任务并发。

**3.** 技术约束：团队成员在相关技术水平方面存在一定的欠缺，缺乏相关的项目经验，需要在开发中并发学习多种技术和能力。

**4.** 其它约束：开发期间，团队成员还有别的学习任务，对项目进度造成一定程度上的影响。

## **2.5假设与依据**

本项目是否能够成功实施，主要取决于以下的条件：

- 团队成员的积极合作配合，为了项目的开发和实施，对个人时间进行合理规划同时为团队做出合理牺牲，配合队友完成任务
- 开发过程中遇到的技术问题可以及时得到同学或者老师的指导和帮助

# 3.具体需求

## **3.1功能图**
![dfsdf](https://github.com/chaigee/xuqiu/blob/master/pic/1.jpg)

## **3.2功能需求**

**主页面：** 用户可在此页面跳转到其它功能页面或者退出。
![dfsdf](https://github.com/chaigee/xuqiu/blob/master/pic/2.png)

**便签页面：** 简单地备忘笔记，并记录当前时间。右下角的&quot;+&quot;功能可添加便签。


**任务页面**

- **今日：** 当前分配好且需要完成的任务页面。（临时任务除外）


- **结算与分享**


- **未来：** 进行分配任务的页面


- **历史记录**


- **设置页面**


- **总结页面**


## **3.3外部接口需求**

### **3.3.1用户接口**

无特殊需求。

### **3.3.2硬件接口**

手机系统需要Android 7.0及以上

### **3.3.3软件接口**

无特殊需求。

### **3.3.4通信接口**

无特殊需求。

## **3.4属性**

### **3.4.1可用性**

- 界面简洁美观，操作简单
- 系统稳定，无bug
- 涉及删除操作时，会有相关提醒

### **3.4.2安全性**

- 数据备份，防止用户丢失数据，及时恢复数据

### **3.4.3可维护性**

- 使用Github进行源码管理，便于维护与修复

#
# 4.验证验收表标准

## **4.1文档验收标准**

文档编写符合国际文档编写规范

- 项目选题报告
- 软件需求规格说明书

## **4.2软件验收标准**

软件一切功能正常，运行流畅、不卡顿、不闪退，适配于大部分Android手机。

## **4.3界面验收标准**

| 序号 | 界面名称 | 界面描述 |
| --- | --- | --- |
| 1 | 主页面 | 标题栏显示&quot;备忘录&quot;，页面有五个按钮分别为&quot;便签&quot;、&quot;任务&quot;、&quot;设置&quot;、&quot;总结&quot;、&quot;退出&quot; |
| 2 | 便签页面 | 标题栏显示&quot;便签&quot;，标题栏左边有&quot;&lt;&quot;按钮（用于返回上一层页面）；标题栏下方有搜索栏，页面则包含各个便签，并根据时间对其进行分类；页面右下角有&quot;+&quot;按钮（用于添加新便签） |
| 3 | 任务-今日页面 | 标题栏显示&quot;任务&quot;，标题栏左边有&quot;&lt;&quot;按钮（用于返回上一层页面）；标题栏下方有3个小标题栏分别为&quot;今日&quot;、&quot;未来&quot;、&quot;历史记录&quot;，当前小标题栏指向&quot;今日&quot;，点击可跳转至指定页面；页面包含各个时间段的任务；任务下方有个结算按钮，点击跳转至结算页面 |
| 4 | 任务-未来页面 | 标题栏显示&quot;任务&quot;，标题栏左边有&quot;&lt;&quot;按钮（用于返回上一层页面）；标题栏下方有3个小标题栏分别为&quot;今日&quot;、&quot;未来&quot;、&quot;历史记录&quot;，当前小标题栏指向&quot;历史记录&quot;，点击可跳转至指定页面；页面从上至下包含日期选择（日历或者下拉列表选择）、选择的时间、&quot;添加&quot;按钮（用于添加任务与时间段） |
| 5 | 任务-历史记录页面 | 标题栏显示&quot;任务&quot;，标题栏左边有&quot;&lt;&quot;按钮（用于返回上一层页面）；标题栏下方有3个小标题栏分别为&quot;今日&quot;、&quot;未来&quot;、&quot;历史记录&quot;，当前小标题栏指向&quot;历史记录&quot;，点击可跳转至指定页面；页面从上至下有根据时间进行排序得出的时间列，时间列旁有个&quot;+&quot;按钮（点击弹出具体任务信息） |
| 6 | 结算页面 | 任务-今日的子页面，页面从上至下是一个大大的圆圈包含&quot;√&quot;、任务信息、&quot;分享&quot;按钮（点击从页面下方弹出QQ微信的logo） |
| 7 | 设置页面 | 标题栏显示&quot;设置&quot;，标题栏左边有&quot;&lt;&quot;按钮（用于返回上一层页面）；页面包含各个设置 |
| 8 | 总结页面 | 标题栏显示&quot;总结&quot;，标题栏左边有&quot;&lt;&quot;按钮（用于返回上一层页面）；页面包含各个时间段与关于该时间段的图表，图表下方有关于图表的描述 |

## **4.4功能验收标准**

需求四象限标准如图：

# 工作分配

|   | 陈海升（队长） | 詹振根 | 黄志明 | 李加兵 | 梁旖 | 艾晓晗 |
| --- | --- | --- | --- | --- | --- | --- |
| 比例 | 12.5% | 25% | 25% | 12.5% | 12.5% | 12.5% |

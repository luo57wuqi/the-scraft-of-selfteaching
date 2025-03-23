# **luo57wuqi的学习笔记**--为什么

## VBS的效率

我是从一个VBS文件帮我解决接近坏的磁盘。他只能插上电脑阅读2s，也就是打开后1s就不能打开。我很担心坏了，于是想办法，知道里面都有哪些文件。于是我问了23年出炉的AI写了一个VBS脚本，那时候1s把文件目录读取出来，那种感觉TM的效率真高。半s就把我copy的1h的问题接近了。

## 代码的数据抓取

24年我开始使用小红书去做音乐号赚钱，过程中有的作品就是来自于采集同行点赞和浏览高，和已经接到广告的同行的作品。然后分析他们的标题，开头梗。在生财有数的知识文档中我发现有一个博主使用油猴脚本去抓取数据，可是代码不全，运行全是错误。到那时我注意到博主说你让AI帮你写代码，具体如何调试输入2999的生财会员才能查看。

可是我这个不服输的劲头，我零星的知道了辅助开发者工具的元素选择器的内容给AI。于是我开始使用kimi个GPT，因为代码比较少可是我赋值过去的网页元素很多，所以kimi可以解决。而gpt3可以写代码的整理和速度很块。在3天的赋值元素和油猴脚本调试后，我的采集代码总算处出来了。下滑，不重复采集，导出csv等功能

## 代码的有什么用

我看了很多文章，大多来之公众号。有个大佬说，如果一个问题自己遇到了，而别人没有提供解决办法，为什么不自己去做，当时额话题似乎是代码有关。但是我记住了。后来在一个编程老师的文章里面，24年看到的，他说编程不仅仅是代码，编程是你把一个问题的产生了更高效率的工作流后，你可以把这个流程给别人，解放自己去做更多有意思的事情，而不是把人束缚在那里。（25-3-16）在《the-scraft-of-self-teaching》中我看到一个读者故事

```
在这个过程中，我觉得最有意思的是，电脑里面的所有事情，都是我能控制的。只要思路和做法正确，就一定能得到自己想要的结果。我开始喜欢上这个过程。当我能够从头到尾控制一件事情时，我会觉得非常爽。

当然了，一开始，磕磕巴巴总是难免的。我总是会遇到一些我解决不了的问题。绞尽脑汁，反复尝试也都是错的。内心很烦躁。于是我学会了一个非常重要的技能：「通过某种方式，使用谷歌搜索」。我学会了如何根据自己的问题，搜索答案。后来我发现，我遇到的大部分问题，别人都有遇到过，网上都有现成的答案。我在这个时刻真正感觉到了互联网是一个神奇的地方。

在这个过程中，我也深深体会到英语的重要性。在计算机领域，大部分有价值的信息都是英文的，不会英文将吃大亏。对于英文的要求，也不是很高，够用就行，因为我是一个连四级英语都没考过的同学，现在也能无障碍地用英语，并且还在不断地用，不断地学。有人说：「英语是一个程序员的天花板」，我非常认同。
```

我进一步感知到，代码其实更多是在写代码的过程中，不断提高自己分析问题和解决问题的能力。另外那种有力量的自信感是肾很多事情很难赋予的感受，我可以操控我的电脑，就像我24-10-25-3这几个月，学习爬虫后，我逐渐的感受到，这种技能代理的能力。以及思维中，分析来龙去脉的能力。我很认同这个读者的分析，手把手教学，能够做出作品的感受，这不就是我自洽和追求的最开心的的事情吗。

```
在界面上看到直观的变化，实际观察到程序的执行结果，令人欢欣鼓舞。我就是这样，从需求出发，像拼乐高一样，完成了自己第一个作品。从做自己想做的事情出发，反向去了解和储备知识，让我把之后遇到的每一个项目，都当成是一次令人愉悦的学习过程。这其中很关键的一点，就是实时反馈：修改->执行，又修改->执行，再修改->执行。
```

如这个作者的分享，每次写完demo，不断属性，就越容易发现，前一版本很差，比如在写一个自动化填写表单出现的下拉框，自己其实不会，在AI的帮助下我知道内嵌网页和下拉选择和ajax的下列表如何去使用js操作元素。在做一个分配的js代码中，我又发现分配思路写代码就几行，但是如何分配权重，从一开始说需求，到后来理解这个名字数字的权重如何编程名字字符串数组的generate过程后，可以提出自己的算法---最小的样本，均相混合的样本，然后重复样本到名字200个，比AI写出来的跟满足需求。



## 比较上传文本

```
ssH 没有链接收集网络失败了---
1 检测问题
    1. 检查 SSH 连接
    运行以下命令测试 SSH 连接：
    ssh -T git@github.com
    成功连接：显示 Hi 用户名! You've successfully authenticated。
    连接失败：提示超时或权限错误。
    ssh: connect to host github.com port 22: Connection timed out-----校园网的问题
2 换成ssh 
	git remote set-url origin git@github.com:用户名/仓库名.git 设置ssh传输
	ssh -T git@github.com 验证
2 换http  重新设置代理
我的梯子的端口是 17890
git config --global http.proxy http://127.0.0.1:7890
git config --global https.proxy http://127.0.0.1:7890

git remote set-url origin https://github.com/用户名/仓库名.git  the-scraft-of-selfteaching
git remote set-url origin https://github.com/luo57wuqi/the-scraft-of-selfteaching.git

3 检测代理
```

```
如果找到你自己的梯子代理
1 去安装的梯子的应用查看---我自己的梯子应用和官网没有
2 去安装梯子的exe所在的文件夹，找到以 一个config的文件，记事本打开---里面可能有端口设置的 信息

1 设置端口00没有设置无法访问国外资源---当然得有梯子（还有配置host DSNip ，不过我还不会）
git config --global http.proxy http://127.0.0.1:7890
git config --global https.proxy http://127.0.0.1:7890
设置 git的获取https,http请求使用的端口代理 http://127.0.0.1:7890 和https://127.0.0.1:782 

2 取消配置 代理（如果你的代理端口是错误的，找到你自己梯子的端口后再 使用 1cmd 命令 设置）
git config --global --unset http.proxy 
git config --global --unset https.proxy

3 检测是否 已经设置好代理了
git config --global --edit
里面有你设置的 端口 就说明设置config成功了

4 检测能否获取github的数据
git clone https://github.com/github/gitignore.git


```

[]()

```
检测代理
原来是需要重新设置代理

cmd 打开不是poweshell
curl -x http://127.0.0.1:17890 https://github.com

C:\Users\luojuan\qingyun\resources\static\clash>curl -x http://127.0.0.1:17890 https://github.com
curl: (35) Recv failure: Connection was aborted

C:\Users\luojuan\qingyun\resources\static\clash>git config --global http.proxy http://127.0.0.1:7890

C:\Users\luojuan\qingyun\resources\static\clash>git config --global https.proxy http://127.0.0.1:7890

C:\Users\luojuan\qingyun\resources\static\clash>curl -x http://127.0.0.1:17890 https://github.com








<!DOCTYPE html>
<html
  lang="en"
```

![image-20250316230919332](D:/%E7%BC%96%E7%A8%8Bjupyter/%E5%93%8E%E8%87%AA%E5%AD%A6%E6%98%AF%E9%97%A8%E6%89%8B%E8%89%BA/%E4%B8%8A%E6%89%8B%E5%86%99%E7%A8%8B%E5%BA%8F/the-craft-of-selfteaching/images/image-20250316230919332.png)

```
commit 739ea4d0ea90099fb5a292ffd0a163db99d62551
Author: luo57wuqi <3206178825@qq.com>
Date:   Sun Mar 16 17:44:36 2025 +0800

    我克隆成功了自学是门手艺这个代码了，哈哈
q

git log 按下 q 退出查看日志 
```


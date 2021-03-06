# Python-Project
A series of python projects，持续更新。。。
此仓库中放置的一系列的python小项目，均是我本人亲自敲过的，有的来自书本，有的来自网络搜集，敲这些项目是为了提高自己的编程能力以及对python的掌握。
“世事洞明皆学问，人情练达即文章”，熟能生巧，勤能补拙，加油

简书：https://www.jianshu.com/p/039156321e30

## 1. 数据可视化

在这个项目中你将学到：
* 如何生成数据集以及如何对其进行可视化；
* 如何使用matplotlib创建简单的图表，以及如何使用散点图来探索随机漫步过程；
* 如何使用Pygal来创建直方图，以及如何使用直方图来探索同时掷两个面数不同的骰子的结果

## 2. 下载数据

在这个项目中你将学到：
* 如何使用网上的数据集；
* 如何处理CSV和JSON文件，以及如何提取你感兴趣的数据；
* 如何使用matplotlib来处理以往的天气数据，包括如何使用模块 datetime ，以及如何在同一个图表中绘制多个数据系列；
* 如何使用Pygal绘制呈现各国数据的世界地图，以及如何设置Pygal地图和图表的样式。
* 如何使用模块json来访问以JSON格式存储的交易收盘价数据，并使用Pygal绘制图形以探索价格变化的周期性，以及如何将Pygal图形组合成数据仪表盘
有了使用CSV和JSON文件的经验后，你将能够处理几乎任何要分析的数据。大多数在线数
据集都可以以这两种格式中的一种或两种下载。学习使用这两种格式为学习使用其他格式的数据
做好了准备。

## 3. 使用API
在这个项目中，你将学到：

* 如何使用API来编写独立的程序，它们自动采集所需的数据并对其进行可视化；
* 如何在图表中添加可单击的链接
* 在图表中添加添加自定义工具提示
* 使用GitHub API来探索GitHub上星级最高的Python项目；
* 如何使用requests包来自动执行GitHub API调用，以及如何处理调用的结果

## 4. 解析iTunes播放列表
目标是找到音乐收藏中重复的乐曲，确定播放列表之间共同的音轨，绘制音轨时长的分布图，以及歌曲评分和时长之间的关系图。
学习到的内容有：
- XML和属性列表(p-list)文件：
- Python 列表和字典
- 使用Python 的set duix
- 直方图和散点图
- 创建和保存数据文件

## 5.万花尺
使用Python来创建动画，就像万花尺一样绘制曲线，我们的spiro.py程序将用Python和参数方程来描述程序的万花尺齿轮的运动，并绘制曲线——螺旋线，我们可以将完成的画图保存为PNG图像文件，并用命令行选项来指定参数或者生成随机曲线。学习到的内容有：
- 使用Turtle模块创建图形
- 使用参数方程
- 利用数学方程来生成曲线
- 用线段来画曲线
- 用定时器来生成图像动画
- 将图形保存为图像文件

## 6. Conway 生命游戏

这个项目将创建一个 N×N 的细胞网格，通过应用 Conway 生命游戏的规则，模拟系统随时间的演进。你将显示每个时间段的游戏状态，并提供一些方式将输出保存到文件。你会设置系统的初始状态，要么是随机分布，要么是预先设计的图案。该模拟由以下几部分组成：
*  在一维或两维空间中定义的属性；
*  在模拟中的每一步，改变这种属性的数学规则；
*  随着系统的演进，显示或记录系统状态的方式。
在 Conway 生命游戏中的细胞可以处于 ON 或 OFF 状态。游戏从一个初始状态开始，其中每个细胞分配一个状态，数学规则决定其状态如何随时间而改变。Conway生命游戏中令人惊奇的是，只有 4 个简单的规则，系统演进会产生行为极其复杂的图案，仿佛它们是活的。图案包括“滑翔机”，即在网格上滑动，“眨眼”，即闪烁ON 和 OFF，甚至还有复制图案

该项目包含的一些主要概念：
*  利用 matplotlib imshow 来展示数据的二维网格；
* 利用 matplotlib 生成动画；
*  使用 numpy 数组；
*  将%运算符用于边界条件；
* 设置值的随机分布。
## 7. 类鸟群：仿真鸟群
本项目将利用 Reynolds 的 3 个规则，创建一个类鸟群，模拟 N 只鸟的群体行为，并画出随着时间的推移，它们的位置和运动方向。我们还会提供一个方法，向鸟群中添加一只鸟，以及一种驱散效果，可以用于研究群体的局部干扰效果。
模拟类鸟群的三大核心规则如下：
* 分离：保持类鸟个体之间的最小距离；
* 列队：让每个类鸟个体指向其局部同伴的平均移动方向；
* 内聚：让每个类鸟个体朝其局部同伴的质量中心移动

对于群体中的所有类鸟个体，做以下几件事：
* 应用三大核心规则；
* 应用所有附加规则；
*  应用所有边界条件。
*  更新类鸟个体的位置和速度。
*  绘制新的位置和速度。
通过本项目，你将了解到
* 如何使用 numpy 数组，如何使用显式循环，以及用整个数组上的 numpy
方法来提高计算速度。
* 利用 scipy.spatial 模块来执行快速和方便的距离计算，实现了一个 matplotlib 技巧，利用两个记号来表示个体的位置和方向。
* 最后，增加了UI 交互，可以按下鼠标按钮来改变 matplotlib 的绘图

## 8. 三维立体画
本项目将用 Python 创建一张三维立体画。下面是本项目涉及的一些概念：
• 线性间距和深度知觉；
• 深度图；
• 用 Pillow 创建和编辑图像；
• 用 Pillow 绘制图像。
该项目的代码将遵循以下步骤：
* 读入深度图；
* 读入一幅平铺图像或创建一个“随机点”平铺图像；
* 通过重复平铺图像创建一幅新图像。该图像的尺寸与深度图一致；
* 对新图像中的每个像素，根据该像素相关联的深度值，将它按比例地向
右移；
* 将三维立体画写入一个文件。

## 9. 3D,2D 动画

*  使用python，matplotlib.pyplot和animation.artistanimation在一个图中组合两个2D动画
*  使用python，matplotlib.pyplot和animation.timedanimation在一个图中组合两个2D动画
*  使用python，matplotlib.pyplot和animation.artistanimation在一个图中组合一个3D和两个2D动画
*  使用python，matplotlib.pyplot和animation.timedanimation在一个图中组合一个3D和两个2D动画


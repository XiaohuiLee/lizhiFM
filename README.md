# lizhiFM
lizhiFM data analysis
## 1、目的：
抓取荔枝FM的热榜信息，发现最受欢迎的DJ，并且研究最受欢迎DJ具有的特征。
## 2、操作：
使用库包：
* urllib2:负责网页内容抓取
* re:负责匹配网页元素，抽取诸如FM列表，FM作者，收听量，播放量等的数据
* numpy\pandas:用于规约数据，数据整理
* plotly:负责数据可视化
* scikit-learn:负责数据分析（决策树，线性回归）以及数学建模的方差分析，置信分析。
* pydotplus:决策树结构的可视化
## 3、结果：
我们通过对抓取的数据进行简单地可视化，发现了荔枝FM热榜发现里最具影响力的TOP 20 DJ；并运用了决策树模型结合Ensemble方法，给出了判定DJ是否是影响力人物的判定规则，整体模型准确率在**89.81%~95.14%**之间，模型总体而言是令人满意的。
## 4、使用：
先执行lizhifmScrapper.ipynb爬取数据；
然后再执行visualization.ipynb呈现数据。

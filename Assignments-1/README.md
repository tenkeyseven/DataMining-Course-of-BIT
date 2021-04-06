# 第一周作业
## 选用数据集：
+ [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews): 130k wine reviews with variety, location, winery, price, and description.

## 处理代码：
+ 对 [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews) 数据集，处理代码为：[wine-reviews.ipynb](./wine-reviews.ipynb)
## 作业要求：
### 一、数据可视化和摘要
+ 数据摘要
  + 标称属性，给出每个可能取值的频数
  + 数值属性，给出5数概括及缺失值的个数
+ 数据可视化
  + 使用直方图、盒图等检查数据分布及离群点

### 二、缺失数据的处理
观察数据集中缺失数据，分析其缺失的原因。分别使用下列四种策略对缺失值进行处理:
+ 将缺失部分剔除
+ 用最高频率值来填补缺失值
+ 通过属性的相关关系来填补缺失值
+ 通过数据对象之间的相似性来填补缺失值


# 第一次作业
## 选用数据集：
+ [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews): 130k wine reviews with variety, location, winery, price, and description.
+ [Oakland Crime Statistics](https://www.kaggle.com/cityofoakland/oakland-crime-statistics-2011-to-2016): Oakland Crime Statistics 2011 to 2016.

## 处理代码：
+ 对 [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews) 数据集，处理代码为：[wine-reviews.ipynb](./wine-reviews.ipynb)
+ 对 [Oakland Crime Statistics](https://www.kaggle.com/cityofoakland/oakland-crime-statistics-2011-to-2016) 数据集，处理代码为：[oakland-crime.ipynb](./oakland-crime.ipynb)
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

### 环境配置
本项目使用 `Anaconda` 作为环境，相关配置和使用库如下：
+ 更新 `conda` 版本（本项目版本为 `conda 4.9.2`）
  ``` bash
  conda update -n base conda
  ```
+ 创建本数据挖掘项目所用的环境
  ``` bash
  conda create -n DataMining
  ```
+ 进入、激活环境
  ``` bash
  conda activate DataMining
  ```
+ 安装相应所需要的包，如下：
  ``` bash
  conda install <package we need>
  pip3 install <package we need>
  ```
+ 本项目使用包括但不限于以下这些库
  ``` 
  numpy                     1.19.2 
  pandas                    1.2.3
  scikit-learn              0.24.1
  matplotlib                3.4.1
  ```
  


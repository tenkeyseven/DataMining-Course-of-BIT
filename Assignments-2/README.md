# 第二次作业：频繁模式与关联规则挖掘
## 选用数据集：
+ [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews): 130k wine reviews with variety, location, winery, price, and description.

## 处理代码：
+ 对 [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews) 数据集，处理代码为：[wine-reviews-2.ipynb](./wine-reviews-2.ipynb)

## 作业要求：
+ 对数据集进行处理，转换成适合进行关联规则挖掘的形式
+ 找出频繁模式
+ 导出关联规则，支持其计算度和置信度
+ 对规则进行评价、可使用Lift、卡方和其他教材中提及的指标，至少两种
+ 对数据挖掘结果进行分析
+ 可视化展示

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
  seaborn                   0.11.1
  pymining                  0.2
  ```
  


# Refuse-Classification
## 项目使用说明

 1. 首先运行`train.py`代码得到训练模型
 2. 得到训练模型后，运行`main.py`代码，即可运行服务器端
 3. 部署好下面的前端项目，即可使用刚刚训练模型来判断垃圾图像类型

## 项目名称

拉拉队立大功

## 主要功能

1. 通过对垃圾训练数据集进行深度学习，产生训练结果；
2. 将训练结果用于测试数据集进行测试，判断训练结果的准确率；
3. 同时在界面中加入自己导入图片的操作，并使用训练结果来分析图片是哪种类型的垃圾。

## 项目包含两部分内容

1. 基于DenseNet模型的深度学习训练垃圾数据集的算法（`train.py`代码）
2. 垃圾分类系统的服务器端代码（`main.py`代码）

# 垃垃小分队项目的前端界面效果展示 

1. [基于PyQt5的前端界面](https://github.com/Vanish-Zeng/Refuse-Classification-qt5)

   ![image-20210617070858657](https://i.loli.net/2021/06/17/bf3gW2unz8MGKdx.png)

   ![image-20210617071041814](https://i.loli.net/2021/06/17/oH35PTeyrlO81x6.png)

   

2. [基于Android的前端界面](https://github.com/porphyra3/trash-Classification-Android)

   ![image-20210617070816934](https://i.loli.net/2021/06/17/92NvtXE5PhrABik.png)

3. [基于vue的前端界面](https://github.com/ywww128/refuse_classification_ui)

   ![image-20210617070943370](https://i.loli.net/2021/06/17/KfUGTyxO8sNMPFQ.png)

   ![image-20210617071013873](https://i.loli.net/2021/06/17/5rLTQJpbRtIOjUV.png)


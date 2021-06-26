![image-20210626160222604](figure/image-20210626160222604.png)

## Shopee - Price Match Guarantee

> 本次比赛的任务是给定一件商品，利用机器学习算法在数据集中寻找与之相同的商品。主要的特征包括图片，标题，image_phash（phash可以度量两张图片的相似程度）。同一件商品可以有完全不同的图片与标题，同一张图片也可能代表着不同的商品。此任务可以看作一个多模态检索任务，利用图像与文本信息检索出相同的商品

### 数据介绍

![image-20210626181553477](figure/image-20210626181553477.png)

+ label_group相同，表示属于同一个商品。训练集中一共有11014个不同商品。每个商品包含样本数量如下图所示，每个相同商品最多包括51个样本（不同的posting_id），每个商品包含两个样本最常见。

<img src="figure/image-20210626184643462.png" alt="image-20210626184643462" style="zoom:80%;" />

+ 更多的数据介绍参考[这里](https://github.com/BITprogramMan/kaggle_shopee/blob/master/data_analysis.md)
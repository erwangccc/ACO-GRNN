## Guide

### Setup for GRNN

1. Set available sigma number：

   At ACO_GRNN.py line 38, give a number range from 10-50.

● 设置需要样本的个数：

在ACO_GRNN.py 39行设置samples

**注意，当修改以上两个值之后，也相应修改ACO_ANT.py中的(city_num, ant_num)值**

● 设置ACO算法的初始化参数：

ACO_ANT.py 11行设置相应的初始化参数

● 设置Y输出值的个数：

在Grnn.py 146行，ACO_GRNN.py 19行设置对应Y输出值的个数

● 设置最大迭代次数：

在ACO_GRNN.py 45行设置最大迭代次数
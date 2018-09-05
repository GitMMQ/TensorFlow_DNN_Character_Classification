# 基于深层神经网络的面向社交媒体的用户性格分类
性格分类依据大五人格模型， 数据源采用开放的数据集essay。 在本文的实现中，
提取用户文本的 tfidf 特征、 LIWC 心理学特征和情感特征、 以及基于 doc2vec 的文本特征等，
建立 SVM 和深层神经网络的分类模型。

[参考](https://github.com/SenticNet/personality-detection)

version:
python 3.6
tensorflow 1.10
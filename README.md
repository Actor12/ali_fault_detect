# ali_fault_detect
天池异常日志监测
https://tianchi.aliyun.com/s/440c9bdf73fcd1aec4da0345b81581bd

思路1：利用drain3日志提取模板提取非结构日志数据转为结构化数据，并且基于提取的结构化数据做一些统计特征，然后做分类。
思路2：利用nlp算法例如doc2vec对日志信息提取embedding，然后做分类。

思路1效果比思路2高二十个点以上，可以融合。

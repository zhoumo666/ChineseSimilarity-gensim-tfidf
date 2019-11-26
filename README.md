# ChineseSimilarity-gensim-tfidf
"""   
基于gensim模块的中文句子相似度计算   
   
思路如下：   
1.文本预处理：中文分词，去除停用词   
2.计算词频   
3.创建字典（单词与编号之间的映射）   
4.将待比较的文档转换为向量（词袋表示方法）   
5.建立语料库   
6.初始化模型   
7.创建索引   
8.相似度计算并返回相似度最大的文本   
"""   
   
可直接运行ChineseSimilartyCaculation.py   
stopwords.txt为中文停用词表   


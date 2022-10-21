
<img src="logo.png" width=45%>

## 课件简介
西南财经大学国际联合实验室《利用Python学习NLP》系列课件针对0基础的NLP(Natural Language Processing)学习者，通过代码实践，详细的注释与示意图讲解，让初学者一步步从最基础的文本处理开始，进阶到当前主流的预训练**BERT**、**GPT**等，并在实践中完成**情感分析**，**语义理解**，**文本生成**等经典NLP任务，掌握使用对应模型来解决现实中各类问题的能力。

本课件使用**python**进行编写，面向实践应用，尽量调用主流的库例如`Pytorch`和`transformer`，为了加强理解和应用，同时针对难点重点详解对应的源代码。
课件中使用的示例问题与数据选自实际应用中金融相关的算法比赛，论文代码复现等场景。

## 章节简介

### 1. Chapter 1 NLP简介 - [NLP简介.ipynb](https://github.com/superlin30/NLP-with-Python/blob/main/Chapter%201%20NLP%E7%AE%80%E4%BB%8B/Chapter%201%20NLP%E7%AE%80%E4%BB%8B.ipynb)
此章节将介绍自然语言文本的内涵和当前的主要任务，例如**文本分类**、**情绪分析**、**命名实体识别 (NER)**、**文本摘要**、**文本生成**。并直接调用简单的代码直观实现当前的一些NLP任务。

- 1-1. 自然语言的性质  
- 1-2. 自然语言处理的流程
- 1-3. 自然语言处理的主要任务
 
### 2. Chapter 2 文本的基本处理 - [文本的基本处理.ipynb](https://github.com/superlin30/NLP-with-Python/blob/main/Chapter%202%20%E6%96%87%E6%9C%AC%E7%9A%84%E5%9F%BA%E6%9C%AC%E5%A4%84%E7%90%86/Chapter%202%20%E6%96%87%E6%9C%AC%E7%9A%84%E5%9F%BA%E6%9C%AC%E5%A4%84%E7%90%86.ipynb)
此章节将使用中文例子利用代码实现基本的文本字符串处理，文本清洗，简单的正则表达式，切词分词，词频统计，词云图等操作，掌握python处理文本的基本方法。

- 2-1. 基本的文本字符串处理方法  
- 2-2. 文本清洗与正则表达式
- 2-3. 中文切词分词方法
- 2-4. 词频统计
- 2-5. 绘制词云图

### 3. Chapter 3 经典文本向量化方法 - [经典文本向量化方法.ipynb](https://github.com/superlin30/NLP-with-Python/blob/main/Chapter%203%20%E7%BB%8F%E5%85%B8%E6%96%87%E6%9C%AC%E5%90%91%E9%87%8F%E5%8C%96%E6%96%B9%E6%B3%95/Chapter%203%20%E7%BB%8F%E5%85%B8%E6%96%87%E6%9C%AC%E5%90%91%E9%87%8F%E5%8C%96%E6%96%B9%E6%B3%95.ipynb)
此章节介绍文本向量化的基本概念并利用代码实现经典的文本向量化表示方法：one-hot，tfidf，基于语料库的词典方法。

- 3-1. one-hot
- 3-2. TF-IDF
- 3-3. 基于语料库的词典方法

### 4. Chapter 4 词嵌入与word2vec - [词嵌入与word2vec.ipynb](https://github.com/superlin30/NLP-with-Python/blob/main/Chapter%204%20%E8%AF%8D%E5%B5%8C%E5%85%A5%E4%B8%8Eword2vec/Chapter%204%20%E8%AF%8D%E5%B5%8C%E5%85%A5%E4%B8%8Eword2vec.ipynb)
此章节介绍将单词映射到向量表示的内涵并利用使用经典word2vec例子完成代码学习，降维并作图。

- 4-1. 词嵌入的概念与简单实现
- 4-2. 利用python实现word2vec方法
- 4-3. 利用PCA方法对词嵌入向量降至二维并可视化

### 5. Chapter 5 文本数据增强 - [文本数据增强.ipynb](https://github.com/superlin30/NLP-with-Python/blob/main/Chapter%205%20%E6%96%87%E6%9C%AC%E6%95%B0%E6%8D%AE%E5%A2%9E%E5%BC%BA/Chapter%205%20%E6%96%87%E6%9C%AC%E6%95%B0%E6%8D%AE%E5%A2%9E%E5%BC%BA.ipynb)
此章节介绍词汇替换，反译，噪声数据等文本增强技术的概念并利用中文实例使用代码掌握实现方法。

- 5-1. 文本截断
- 5-2. 文本数据扩充
- 5-3. 噪声技术(EDA)

### 6. Chapter 6 循环神经网络与NLP 
此章节将详细介绍经典的循环神经网络RNN与LSTM，并利用详细拆解的python代码实现其功能与架构，最后通过循环神经网络完成文本二分类任务。

### 7. Chapter 7 注意力机制与Transformer
此章节通过代码学习当前NLP领域主流的注意力机制与Transformer模型，并利用Transformer模型完成文本情感分析任务。

### 8. Chapter 8 预训练模型BERT
此章节介绍经典NLP预训练模型BERT，并利用代码实现基于BERT模型的新闻文本多标签分类任务，掌握从网络上调用各种经典的预训练模型进行微调并完成下游任务的基本流程。

### 9. Chapter 9 生成式语言模型GPT
此章节介绍经典NLP生成模型GPT,并利用代码实现基于GPT框架的新闻摘要生成任务，掌握生成式模型的基本原理与技术细节。

### 10. Chapter 10 机器翻译模型
(待补充)

### 11. Chapter 11 TTS文本到语音模型
(待补充)

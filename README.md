## 课件简介
西南大学国际联合实验室《利用Python学习NLP》系列课件针对0基础的NLP((Natural Language Processing))学习者，通过代码实践，详细的注释与示意图讲解，让初学者一步步从最基础的文本处理开始，进阶到当前主流的预训练bert，GPT等，并在实践中完成情感分析，语义理解，文本生成等经典NLP任务，掌握使用对应模型来解决现实中各类问题的能力。

本课件使用python进行编写，面向实践应用，尽量调用主流的库例如`Pytorch`和`transformer`，为了加强理解和应用，同时针对难点重点详解对应的源代码。
课件中使用的示例问题与数据选自实际应用中金融相关的算法比赛，论文代码复现等场景。

## 章节简介

### 1. [Chapter 1 NLP简介](https://github.com/superlin30/NLP-with-Python/blob/main/Chapter%201%20NLP%E7%AE%80%E4%BB%8B/Chapter%201%20NLP%E7%AE%80%E4%BB%8B.ipynb)
此章节将介绍自然语言文本的内涵和当前的主要任务，例如文本分类、情绪分析、命名实体识别 (NER)、文本摘要、文本生成。并直接调用简单的代码直观实现当前的一些NLP任务。


- 1-1. 自然语言的性质 - **Predict Next Word**
  - Paper -  [A Neural Probabilistic Language Model(2003)](http://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)
  - Colab - [NNLM.ipynb](https://github.com/superlin30/NLP-with-Python/blob/main/Chapter%201%20NLP%E7%AE%80%E4%BB%8B/Chapter%201%20NLP%E7%AE%80%E4%BB%8B.ipynb)
- 1-2. 自然语言处理的流程 - **Embedding Words and Show Graph**
  - Paper - [Distributed Representations of Words and Phrases
    and their Compositionality(2013)](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
  - Colab - [Word2Vec.ipynb](https://colab.research.google.com/github/graykode/nlp-tutorial/blob/master/1-2.Word2Vec/Word2Vec_Skipgram(Softmax).ipynb)
- 1-3. 自然语言处理的主要任务- **Sentence Classification**
  - Paper - [Bag of Tricks for Efficient Text Classification(2016)](https://arxiv.org/pdf/1607.01759.pdf)
  - Colab - [FastText.ipynb](https://colab.research.google.com/github/graykode/nlp-tutorial/blob/master/1-3.FastText/FastText.ipynb)

`nlp-tutorial` is a tutorial for who is studying NLP(Natural Language Processing) using **Pytorch**. Most of the models in NLP were implemented with less than **100 lines** of code.(except comments or blank lines)
* 自然语言的性质
* 自然语言处理的流程
* 自然语言处理的主要任务

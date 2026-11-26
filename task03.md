# all-in-rag-learningnotes

# 三、索引构建
- 什么是Embedding
- 相似度计算


## 3.1 什么是Embedding

Embedding是一种将真实世界中复杂、高维的数据对象（如文本、图像、音频、视频等）转换为数学上易于处理的、低维、稠密的连续数值向量的技术。

简单来说，就是将文本转换成向量表示。

工作流程：

```
输入文本
   ↓
Tokenizer
   ↓
Token Embedding
   ↓
Transformer Encoder
   ↓
Pooling / 特征聚合
   ↓
文本向量
```

## 3.2 相似度计算

- Cosine Similarity。
- Dot Product。
- Euclidean Distance。





---
title: Convolutional Nerual Network
categories: 技术干货
---

-- 关于 CNN 神经网络的零零碎碎。
<!-- more -->
## INPUT
1. One Hot Vector (分字)<br>
补足句子长度为100，input 为 len(vocab) &times; len(sentence) <br>
2. 词向量预训练 <br>
将文本转换为 id2word(list) 和 words2id(dict)。在 words2id(dict) 存放每个字以及其 id，在 id2word(list) 按 id 顺序存放



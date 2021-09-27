---
layout: default
---

## Multi-Task Retrieval for Knowledge-Intensive Tasks

Jean Maillard, Vladimir Karpukhin, Fabio Petroni, Wen-tau Yih, Barlas Oguz, Veselin Stoyanov, Gargi Ghosh; **ACL 2021**

[[link]](https://aclanthology.org/2021.acl-long.89.pdf)
---

**Summary**

Knowledge-intensive tasks require a lot of knowledge of the world by their nature. Therefore, an efficient information retrieval system (finding a small subset of relevant information) is needed for practical NLP engineering. It is largely divided into two methodologies. First, there are statistic based sparse representation methodologies such as tf-idf and BM25, and the others are dense representation methodologies such as ICT, DPR and RAG, which turned them into learnable modules through a neural network. In each specific knowledge-intensive task, the methodology through neural-networks exceeds statistics based(or count-based), but performance drops significantly in the out-of-distribution and low data regimes (few shot, zero shot). Therefore, universal neural retrieval method is required.

<img src="img/multi1.png">

Existing state-of-the-arts learned task-specific query encoders, but this proposed methodology seeks to obtain a regularization effect for generalization ability taking universal intuition obtained by only one multi-tasks trained encoder. For comparison, KILT dataset, consisting of five knowledge-intensive tasks (i.e., question answering, slot filling, fact checking, dialogue, entity linking), was experimented.

<img src="img/multi2.png">

From the experimental results, the shared query encoder was overall better than the task-specific query encoders. In particular, it was robust for more knowledge-intensive tasks that required multi-hop reasoning. This is because the regularization effect is strengthened by learning not only features for specific tasks but also universal features by performing multi-task learning internally in KILT.

<img src="img/multi3.png">

In addition, in the zero-shot and few-shot settings, where the neural net hardly exerts power, it was overall superior to the statistical algorithm methods such as BM25.

---
**My opinion**



<br/>
<br/>
<br/>

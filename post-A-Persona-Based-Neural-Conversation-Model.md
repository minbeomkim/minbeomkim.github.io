---
layout: default
---

## A Persona-Based Neural Conversational Model

Jiwei Li, Michel Galley, Chris Brockett, Georgios P. Spithourakis, Jianfeng Gao, William B. Dolan:; ACL 2016

[[link]](https://arxiv.org/pdf/2107.07566.pdf)
---

**Summary**


<!-- <img src="internet.png"> -->


---
**My opinion**

I think it's a monumental research. Considering the significance of this work, first of all, this paper aims to inject persona-consistency in order for meaningful role of language model, which is learned from the perplexity point of view. Second, considering the overall process of creating a chatbot, the reason why language model's learning methods with autoregressive or unsupervised settings are in the limelight is that it is too expensive human-cost for adding task-dependent labels to sentence-level supervision. Therefore, while the language model learns from the perspective of perplexity, if other meaningful characteristics are possessed through external representation, the possibility of attribute-controllable generation is also promised and human-cost efficient learning is possible for each detailed task. This work does not require any other human costs. The third significant part is that persona-consistency contributes to the robustness and compositional generalization of the chatbot through this methodology. Since persona is a dense representation, it can be used while maintaining attribute-consistency even to words that are not in context, and information (that is not explicitly provided) from a similar persona representation can be referenced and responded to in a good language generation.

<br/>
<br/>
<br/>

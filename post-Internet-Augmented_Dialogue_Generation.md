---
layout: default
---

## Internet-Augmented Dialogue Generation

Mojtaba Komeili, Kurt Shuster, Jason Weston; arxiv 2021

[[link]](https://arxiv.org/pdf/2107.07566.pdf)
---

**Summary**

Existing language models in chatbots sometimes cause 'Fact Hallucination' symptoms. This is a problem that arises from the limitation of large language models. Once pretrained model is learned from the point of view of language generation with static datasets, there are times when misconceptions and bias are stored, or the learning of new concepts that need to be updated occasionally is not being learned for a long time. To solve this problem, open-domain question&answering or augmentation of responses with a knowledge graph have been leveraged as borrowing external knowledge.

This research considers the Internet as external knowledge and augments the response through real-time search so that social chatbot can aggregate more general knowledge and reflect it in the Dialogue system.

<img src="internet.png">

The proposed method consists of two components, i) a search query generator and ii) a FiD-style encoder-decoder model. The search query generator is an encoder-decoder transformer that takes in the dialogue context as input, and generates a search query. Next the Internet, the sea of information, finds documents based on the search query in real time. With these rich knowledge, the FiD-style model encodes each document individually and concatenates them to the dialogue context encoding, then finally generates the next response with the decoder.

---
**My opinion**

Facebook AI Research published the latest chatbot [***'blender bot 2.0'***](https://ai.facebook.com/blog/blender-bot-2-an-open-source-chatbot-that-builds-long-term-memory-and-searches-the-internet/), and this paper is one of the research related to the chatbot. The large language model continues to be used in the direction of skillful response generation, whereas the customized service reflecting the user's taste is stored and leveraged in long-term memory. At the same time, accurate and up-to-date information is reflected to final responses through real-time Internet searches. The blender bot 2.0 seems to be researched in the direction of mixing the three modules for state-of-the-art chatbot. Furthermore, external knowledge seems to be studied with multimodal representation to aggregate images and other forms of information beyond short text scattered on the Internet. I agree and expect that this is the correct direction of the AI assistant in the future.

<br/>
<br/>
<br/>

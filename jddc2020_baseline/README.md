# 2020智源-京东多模态对话挑战大赛

## 大赛官网
[https://jddc.jd.com/](https://jddc.jd.com/)

## 任务简介

多模态人机交互需要综合自然语言处理、机器视觉等多项技术才能更加细致的理解用户的意图，从而给出准确而快速的回答。本次比赛聚焦于人机交互中对于多模态输入信息的理解，目的在于研究如何在对话过程中有效融合使用多模态用户问题信息，产生任务导向型对话的文本回答，使对话系统具备多模态语义理解的能力。
此次大赛将同步发布JDDC Corpus 2.0多模态多轮任务导向型对话数据集，共包含多品类约24万session的对话，每session平均交互轮次约为7轮, 其中用户问题涉及约40余万张图片。此外，数据集还提供一个约3万商品的小型商品知识库作为相关商品知识的补充。

## 基线模型

为促进广大参赛者相互学习交流，本次大赛也将同步发布基于检索方案和基于生成方案的基线比赛模型，参赛选手可以通过基线系统完成比赛数据预处理和模型训练，熟悉了解多模态对话系统的构建方式：

- [Multimodal Dialogue Dense Retriever模型](./mddr)，能够实现多模态多轮对话的检索，通过对海量多模态历史交互信息的检索召回与排序，实现对当前问题的应答。
- [Multimodal Hierarchical Encoder Decoder模型](./mhred)，能够实现多模态多轮对话的建模，端到端生成文本应答，实现多轮对话。该基线模型提供PyTorch框架和TensorFlow2框架的两种实现。

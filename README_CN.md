Hello World! This is codefuse-ai! 
<p align="left">
  <img src="./LOGO.png" width="100%" />
</p>
<div align="center">

[**English**](./README.md)|[**HF Repo**](https://huggingface.co/codefuse)

</div>

我们是来自蚂蚁集团的一支致力于开源项目的机器学习工程师团队。我们的使命是开发出专门支持整个软件开发生命周期的代码大语言模型（Code LLMs），包括设计、需求、编码、测试、部署、运维等方面的支持。


在本次发布中，我们开源了以下内容：1）**MFT（多任务微调）框架，也称为MFTcoder**；2）**两个用于增强LLMs编码能力的数据集**；3）**基于FasterTransformer的更快速、更可靠的部署框架**。由此产生的模型集合包括CodeFuse-13B和CodeFuse-CodeLlama-34B，支持多种与代码相关的任务，如代码补全、文本转代码、单元测试生成等。值得一提的是，CodeFuse-CodeLlama-34B基于CodeLlama作为基础模型，并利用我们提出的MFT框架进行微调，在HumanEval Python pass@1评估中取得高达的**74.4%（贪婪解码）**的好成绩，甚至**超过了GPT-4（71%）的表现**。我们计划在不久的将来将更多的基础LLMs纳入到我们的模型集合中。


我们相信我们的解决方案可以显著提升预训练LLMs在多个相关任务上的性能。我们将进一步探索这个方向，并提供更多的开源贡献。与此同时，我们诚邀志同道合的工程师和研究人员加入这个社区，共同构建CodeFuse。
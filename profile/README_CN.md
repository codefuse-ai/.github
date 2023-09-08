<p align="left">
  <img src="https://github.com/codefuse-ai/.github/blob/main/profile/LOGO.png" width="100%" />
</p>
<div align="center">

[**English**](https://github.com/codefuse-ai/.github/blob/main/profile/README.md)|[**HF Repo**](https://huggingface.co/codefuse)

</div>

Hello World! This is codefuse! 

CodeFuse的使命是开发专门设计用于支持整个软件开发生命周期的大型代码语言模型（Code LLMs），涵盖设计、需求、编码、测试、部署、运维等关键阶段。我们致力于打造创新的解决方案，让软件开发者们在研发的过程中如丝般顺滑。


在本次发布中，我们开源了以下内容：
1. [**MFT（多任务微调）框架，也称为MFTcoder**](https://github.com/codefuse-ai/MFTCoder)；
2. **两个用于增强LLMs编码能力的数据集**，包括[Code Exercise](https://huggingface.co/datasets/codefuse/CodeExercise-Python-27k)和[Evol-Instruction](https://huggingface.co/datasets/codefuse/Evol-instruction-66k)；
3. [**基于FasterTransformer的更快速、更可靠的部署框架**](https://github.com/codefuse-ai/FasterTransformer4CodeFuse);。

由此产生的模型集合包括[CodeFuse-13B](https://huggingface.co/codefuse/CodeFuse-13B)和[CodeFuse-CodeLlama-34B](https://huggingface.co/codefuse/CodeFuse-CodeLlama-34B)，支持多种与代码相关的任务，如代码补全、文本转代码、单元测试生成等。值得一提的是，[CodeFuse-CodeLlama-34B](https://huggingface.co/codefuse/CodeFuse-CodeLlama-34B)基于CodeLlama作为基础模型，并利用我们提出的MFT框架进行微调，在HumanEval Python pass@1评估中取得高达的**74.4%（贪婪解码）**的好成绩，甚至**超过了GPT-4（67%）的表现**。我们计划在不久的将来将更多的基础LLMs纳入到我们的模型集合中。


我们相信我们的解决方案可以显著提升预训练LLMs在多个相关任务上的性能。我们将进一步探索这个方向，并提供更多的开源贡献。与此同时，我们诚邀志同道合的工程师和研究人员加入这个社区，共同构建CodeFuse。

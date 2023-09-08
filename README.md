Hello World! This is codefuse-ai! 
<p align="left">
  <img src="./LOGO.png" width="100%" />
</p>


<div align="center">

[**简体中文**](README_CN.md)|[**HF Repo**](https://huggingface.co/codefuse)

</div>

We are a passionate team of machine learning engineers from Ant Group dedicated to open source projects. Our goal is to develop Code Large Language Models (Code LLMs) specifically designed to support the entire software development lifecycle, including design, requirements, coding, testing, deployment, operations, and maintenance.


In this release, we are open sourcing 1) **the MFT (Multi-Task Fine-Tuning) framework, known as MFTcoder**,  2) **two datasets for enhancing the coding capabilities of LLMs**, and 3) **a faster and more reliable deployment framework based on FasterTransformer.** The resulting model ensemble, which includes CodeFuse-13B and CodeFuse-CodeLlama-34B, supports various code-related tasks such as code completion, text-to-code conversion, and unit test generation. In particular, CodeFuse-CodeLlama-34B, built upon CodeLlama as the base model and fine-tuned using the proposed MFT framework, achieves an impressive score of **74.4% (greedy decoding)** in the HumanEval Python pass@1 evaluation, **even surpassing the performance of GPT-4 (71%)**. We have plans to incorporate additional base LLMs into the ensemble in the near future.


We believe that our solution can significantly enhance the performance of pretrained LLMs across multiple related tasks simultaneously. We are committed to further exploring this direction and providing more open-source contributions. We also encourage engineers and researchers within this community to join us in co-constructing CodeFuse.
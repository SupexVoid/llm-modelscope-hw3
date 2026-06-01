# LLM ModelScope HW3

本项目为“大语言模型部署体验”课程作业，基于 ModelScope DSW CPU Notebook 环境完成。

## 实验环境

- 平台：ModelScope DSW CPU Notebook
- Python 环境：Python 3.10
- 深度学习框架：PyTorch 2.3.0+cpu
- Transformers 版本：4.40.2

## 实验模型

- ChatGLM3-6B
- Qwen1.5-0.5B-Chat

## 实验说明

本实验完成了开源大语言模型的下载、部署和问答测试。由于免费 CPU Notebook 算力和内存有限，较大的 7B 模型推理速度较慢，因此最终使用轻量级 Qwen1.5-0.5B-Chat 完成实际问答测试。

## 测试结果

问题 1：冬天：能穿多少穿多少；夏天：能穿多少穿多少。区别是什么？

模型回答：冬天多穿，夏天少穿。

问题 2：单身狗产生的原因有两个，一是谁都看不上，二是谁都看不上。区别是什么？

模型回答：第一种是谁都看不上别人，第二种是谁都被别人看不上。

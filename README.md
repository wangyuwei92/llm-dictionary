# 大模型专业术语对照

## A

- ALiBi，Attention with Linear Biases的简写，带有线性偏差的注意力，一种相对位置编码方法
- Addition-based，增量式参数微调

## B

- BPE，Byte Pair Encoding的简写，一种子词分词算法
- BatchNorm，对一个batch中的样本做归一化
- batch size，一次训练的样本数目
- BGE，BAAI General Embedding的简写，智源开源的词向量模型，

## C

- causal decoder，因果解码器

## D

- decoder，解码器
- DeepSpeed，微软发布的基于PyTorch的分布式训练库
- Deep Norm，Deep Normalization的简写，一种层归一化方法
- DQN, Deep Q-Network的简写，DQN算法在2013年由DeepMind团队提出，通过使用深度神经网络来逼近Q函数的值，解决了状态空间规模大的问题。
- DPR, Dense Passage Retrieval的简写，稠密段落检索，用于检索增强

## E

- encoder，编码器

## F

- Flash Attention，Dao-AIlab提出的注意力机制，用于加速和节省内存
- FiD，Fusion in Decoder的简写，一种检索增强语言模型

## G

- GELU，Gaussian Error Linear Unit的简写，一种激活函数
- Grouped query attention，基于MQA改进的注意力机制
- GPTQ, Accurate Post-Training Quantization for Generative Pre-trained Transformers的简写，一种大模型量化方法

## H

- 

## K

- KV Cache，是大模型推理优化的一个常用技术，该技术以空间换时间的思想，通过使用上次推理的KV缓存，可以在不影响任何计算精度的前提下，提高推理性能

## L

- Layernorm，从隐藏层的维度做归一化
- 

## M

- MLM，Masked Language Model的简写，遮蔽语言模型
- MQA，Muti Query Attention，一种加快计算速度的注意力机制
- Muti-head Attention，多头注意力机制
- MC learning，Monte-Carlo Reinforcement Learning，蒙特卡洛强化学习

## O

- off-policy, the learning is from the data off the target policy，强化学习中将收集数据当做一个单独的任务
- on-policy, the target and the behavior polices are the same, 行为策略与目标策略相同

## P

- PEFT，Parameter-Efficient Fine-Tuning的简写，参数高效微调框架
- Paged Attention，一种注意力机制，在vLLM中得到使用
- policy-based, 强化学习中用梯度的方法直接学习策略
- PPO, Proximal Policy Optimization, 强化学习中近短策略优化算法
- prompt, 提示工程

## Q

- 

## R

- RoPE，Rotary Position Embedding的简写，旋转位置编码
- RMS Norm，Root Mean Square Layer Normalization的简写，一种层归一化方法
- Reward model，奖励模型
- RLHF，Reinforcement Learning from Human Feedback的简写，以强化学习方式依据人类反馈优化语言模型
- Reparameterization-based，重参数化微调
- RL，Reinforcement Learning的简写，强化学习
- RETRO, Retrieval-enhanced transformer，一种检索增强transformer语言模型

## S

- SFT，Supervised Fine-Tuning简写，有监督的微调
- sentencepiece，谷歌开源的分词框架，提供了两种切词算法，BPE和unigram词模型
- Swish，谷歌大脑提出的一种激活函数
- Specification-based，指定式参数微调

## T

- transformer，2017年的一篇论文《Attention is All You Need》提出的一种基于注意力机制的神经网络模型架构
- TD learning，Temporal Difference，时序差分强化学习
- TRPO, rust region policy optimization的简称, 强化学习中信赖域策略优化
- Triton, OpenAI开源的GPU编程语言
- text2vec, 一般指https://huggingface.co/GanymedeNil/text2vec-large-chinese

## U

- unilm, Uniﬁed Language Model的简写，统一语言模型，微软在BERT基础上提出的预训练语言模型

## V

- value-based, 基于值函数的强化学习

## W

- wordpiece，分词器，Schuster等人2012年在《Japanese and korean voice search》一文中提出

## Y

- 

## Z

- ZeRO，The Zero Redundancy Optimizer的简写，零冗余优化，deepspeed分布式训练的核心

# 注释

[1] 


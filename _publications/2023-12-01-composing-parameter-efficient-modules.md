---
title: "Composing Parameter-Efficient Modules with Arithmetic Operations"
collection: publications
category: conferences
permalink: /publication/2023-12-01-composing-parameter-efficient-modules
excerpt: 'We propose to compose parameter-efficient modules through linear arithmetic operations in the weight space (addition, negation, and multicombination), integrating different module capabilities with no additional training.'
date: 2023-12-01
venue: 'NeurIPS 2023'
paperurl: 'https://arxiv.org/abs/2306.14870'
citation: 'Jinghan Zhang, Shiqi Chen, Junteng Liu, Junxian He. (2023). &quot;Composing Parameter-Efficient Modules with Arithmetic Operations.&quot; <i>Advances in Neural Information Processing Systems (NeurIPS)</i>.'
---

In parameter-efficient finetuning (PEFT), a lightweight module is learned on a specific dataset while the underlying pretrained model remains unchanged, resulting in multiple compact modules representing diverse skills when applied to various domains and tasks. In this paper, we propose to compose these parameter-efficient modules through linear arithmetic operations in the weight space, thereby integrating different module capabilities. Specifically, we first define addition and negation operators for the module, and then further compose these two basic operators to perform flexible arithmetic. Our approach requires no additional training and enables highly flexible module composition. We apply different arithmetic operations to compose the parameter-efficient modules for (1) distribution generalization, (2) multitasking, (3) unlearning, and (4) domain transfer.

**Paper:** [https://arxiv.org/abs/2306.14870](https://arxiv.org/abs/2306.14870)
